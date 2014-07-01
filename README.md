PyTribe
=======

Python wrapper for the EyeTribe SDK by Edwin Dalmaijer. Version 1, 01-06-2014.


example
-------

import pytribe

# initialize connectiom
c = connection()
t = tracker(c)

# ask for something
t.get_version()
