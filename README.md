https://m.youtube.com/watch?v=Ia5jyz8sOCM  

how does Linux run executables ?  

exec is using syscall family.  

int * execve(const char * path_name,  
    char const * argument_value[ ],  
    char const * environment_variable)
