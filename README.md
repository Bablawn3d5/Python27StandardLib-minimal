# Python27StandardLib-minimal
A stripped down python standard library, intended for embdedded projects that need to distribute a less bulky version of the Python Standard Library

Removed Libraries:
```
   idlelib     - IDLE isn't needed when working with embedded python.
   test        - Internal Python testing only.
   pydoc_data  - Not needed.
   lib2to3     - Only useful if you need to migrate from Python 2 to 3.
```
Libraries Questionably removed (we're unsure what these are needed for):

```
   plat-*   
   lib-tk   
   lib-old
   bsddb      
   sqlite    
   hotshot
```

The distribution comes with a builds a ZIPs of library.

You can then pragmatically include the standard lib by calling:

```
   sys.path.import(0, 'PythonLib27-minimal.zip')
```
