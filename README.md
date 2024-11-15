# OpenGL loader generator
OpenGL loader for C++ using Python  
See sample_project for usage.  
Can be used with both C and C++  
Shows function signature in tooltip window when hovered over function pointer or macro name, since function prototype is above function pointer declaration as comment in generated header.  
  
For OpenGL -  
Generates loaders for both core & compatibility profiles, but only one can be used at a time due to same function pointer names.  
Uses function pointers name directly starting with gl for OpenGL, if macros are desired for glfunc names instead of function pointers of same name set:  
"with_glfn_func_name = True" in gl_loader_gen.py  