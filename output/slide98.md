
* Create a new file `tests.py` with the following contents.

```
import unittest
from doubler import doubler
	
class HelperFunctionTests(unittest.TestCase):
    def test_001_valid_type_is_returned(self):
        print "Executing test {}".format(self)
        test = doubler(2)
        self.assertIsInstance(test, int)
	
	
    def test_002_double_4(self):
        print "Executing test {}".format(self)
        test = doubler(4)
        self.assertEqual(test, 8)
	
	
unittest.main()
```

