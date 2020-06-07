# PyInsxtractorMod
Modified version of Ming Loh/Countercepts Pyinstxtractory which will automatically prepend correct bytecode headers and then decompile the bytecode.

Requirements:
Python 3.8
Uncompyle6 for Python -3.6
Decompyle3 for Python 3.6+

This will automatically prepend correct bytecode headers by extracting the correct header from the pyc files in the PYZ_Extracted folder.

This will work for python 3.7 & python 3.8 and use the appropriate decompiler for the bytecode (Uncompyle6/Decompyle3).
