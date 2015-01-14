Fishbowl
========

An enhanced interactive Shell for Common Lisp  (based on IPython)

```
 Fishbowl: an enhanced interactive Common Lisp Shell
(Version 0.4 - Ipython protocol v.4.1)
--> (C) 2014-2015 Frederic Peschanski (cf. LICENSE)
                                 __________       
                                /         /.      
     .-----------------.       /_________/ |      
    /                 / |      |         | |      
   /+================+\ |      | |====|  | |      
   ||Fishbowl        || |      |         | |      
   ||                || |      | |====|  | |      
   ||* (fact 5)      || |      |         | |      
   ||120             || |      |   ___   | |      
   ||                || |      |  |166|  | |      
   ||                ||/@@@    |   ---   | |      
   \+================+/    @   |_________|./.     
                         @           ..  ....'    
     ..................@      __.'. '  ''         
    /oooooooooooooooo//      ///                  
   /................//      /_/                   
   ------------------                          
```

**Important** : this is alpha version non-officially released software. **Use it at your own risk and peril !**

## Requirements ##

To try Fishbowl you need :

 - a Common lisp implementation: at the moment only SBCL 1.2.x (with native threads) is supported, more to come ...

 - Quicklisp (cf. http://www.quicklisp.org/)

 - Python 3.2 or above

 - IPython 2.1 or above

## Quick launch ##

For simple interactions on the console, just type:

    python3 ./run-fishbowl.py     (or directly ./run-fishbowl.py if python3 is in PATH)

```
In [1]: (* 2 21)
Out[1]: 42

In [2]: 
```

## Notebooks ##

The real interest of Fishbowl is its use conjointly
 with the IPython notebook frontend. For a try, type:

    python3 ./run-fishbowl.py notebook

The file `AboutFishbowl.ipynb` is an example of a Lisp-based notebook.

Its can be consulted on-line at the following adress :

http://nbviewer.ipython.org/github/fredokun/fishbowl/blob/master/AboutFishbowl.ipynb

The file `AboutFishbowl.pdf` is a printable PDF version of this notebook that can be
generated by the IPython `nbconvert` tool.

----

 ... have fun !

