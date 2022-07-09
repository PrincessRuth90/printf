#printf**

The project consists of normal functions, derived functions a man page and a README.md file.


**Authorized functions and macros**

* write (man 2 write)
* malloc (man 3 malloc)
* free (man 3 free)
* va_start (man 3 va_start)
* va_end (man 3 va_end)
* va_copy (man 3 va_copy)
* va_arg (man 3 va_arg)


**This produces output according to a format specifiers,as shown below**

_printf("Length:[%d, %i]\n", len, len);


printf("Length:[%d, %i]\n", len2, len2);


_printf("Negative:[%d]\n", -762534);


printf("Negative:[%d]\n", -762534);


_printf("Unsigned:[%u]\n", ui);


printf("Unsigned:[%u]\n", ui);


_printf("Unsigned octal:[%o]\n", ui);


printf("Unsigned octal:[%o]\n", ui);


_printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);


printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);


_printf("Character:[%c]\n", 'H');


printf("Character:[%c]\n", 'H');


_printf("String:[%s]\n", "I am a string !");


printf("String:[%s]\n", "I am a string !");


_printf("Address:[%p]\n", addr);


printf("Address:[%p]\n", addr);


len = _printf("Percent:[%%]\n");


len2 = printf("Percent:[%%]\n");


_printf("Len:[%d]\n", len);


printf("Len:[%d]\n", len2);


_printf("Unknown:[%r]\n");


This project is developed by **Marcus Ruth** and **Micheal Oriyomi** **ALX cohort 7**
