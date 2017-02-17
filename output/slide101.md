
* Add a new test to `tests.py` 

```
import unittest
from doubler import doubler
	
class HelperFunctionTests(unittest.TestCase):
    def test_001_valid_type_is_returned(self):
        test = doubler(2)
        self.assertIsInstance(test, int)
	
	
    def test_002_double_4(self):
        test = doubler(4)
        self.assertEqual(test, 8)
	
    def test_003_invalid_type_raises_error(self):
        with self.assertRaises(TypeError):
            test = doubler('2')
	
unittest.main()
	
```

