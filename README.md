# Python27StandardLib-minimal
A stripped down python standard library, intended for embdedded projects that need to distribute a less bulky version of the Python Standard Library

Removed Libraries:
   idlelib     - IDLE isn't needed when working with embdded python.
   test        - Internal Python testing only. You don't need this in normal embedded distribution
   pydoc_data  - Not needed
   lib2to3     - Useful if you wanna migrate, but we're working with embdded sutff. So nope.

Libraries Questionallbly removed (we're unsure what these do):
   lib-tk      - ??? Doesn't break stuff when removed.
   bsddb       - 
   sqlite     -
