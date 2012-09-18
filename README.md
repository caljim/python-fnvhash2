Python-fnvhash2
===============

The FNV Hash Python C extension module contains functions for fast computing string hash value with FNV algorithm


==INSTALL==

python setup.py build
python setup.py install


==USEAGE==

import fnvhash2
>>> fnvhash2.fnv_64a_str("hello")
12121257498555280600L

>>> fnvhash2.fnv_32a_str("hello world")
2552756796

That's all!