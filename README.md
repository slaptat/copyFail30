# CopyFail for Python versions > 3.10 

Os did not contain splice() before version 3.10. This version of copyFail uses ctypes to make the syscall between descriptors without a utilizing the splice wrapper.

Works on both older and current versions of python3. 