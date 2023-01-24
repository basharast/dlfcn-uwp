# dlfcn-uwp

UWP version of [dlfcn-win32](https://github.com/dlfcn-win32/dlfcn-win32) (ARM32)
 
## Content

- dlfcn-uwp.h
- dlfcn-uwp.dll
- dlfcn-uwp.lib
- dlfcn-uwp.pdb


## Usage

- Link `dlfcn-uwp.lib` with your project
- Include `dlfcn-uwp.h` in your code
- Use it as normal no changes made on the usage.
- Note that `mode` in `dlopen` is not active.
- You should be able to load DLLs from package location and localstate with full path


## Credits

Original project Written by Ramiro Polla in 2007. 

Maintained by Tiancheng "Timothy" Gu from 2013.

Thanks to [Gustave Monce](https://github.com/gus33000) for dynamic DLL load solution