PyTribe
=======

Python wrapper for the EyeTribe SDK by Edwin Dalmaijer. Version 2, 02-07-2014.


example
-------

    import pytribe
    
    # initialize connectiom
    c = pytribe.connection()
    t = pytribe.tracker(c)
    
    # ask for something
    t.get_version()
