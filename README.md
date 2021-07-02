# get_next_line | slucas-s

A function that allows you to read a file line by line.
```C
int	get_next_line(int fd, char **line)
```
This functions allocates memory and saves in _line_ the next line of the opened file with the _fd_ file descriptor. Returning 1, if there is still content to read in the file, 0 if the file has been completly returned and -1 if there was an error in the process.

The __bonus_ version allows you to interchange different fd. Using multiple fd in the other one before the file is fully readed is an undefined behaviour.