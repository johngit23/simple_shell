## Builtins
Our shell has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| env                 | Print the environment.                                                                    |
| setenv [var][value] | Set an environment variable and value. If the variable exists, the value will be updated. |
| alias[name[='value]]| Reads aliases name                                                                        |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Change the directory.                                                                     |
| help [built-in]     | Read documentation for a built-in.                                                        |

### usage:
- clone the repo
- `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
- `./hsh`

## Example:
```
ls -la
```
## Contributor :
Yohannes Mebrahtom <jhon.klaus2008@gmail.com>
