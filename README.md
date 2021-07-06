Calling your function get_next_line in a loop will then allow you to read the text
available on a file descriptor one line at a time until the EOF.

Programcompile with the flag -D BUFFER_SIZE=xx. which will be used
as the buffer size for the read calls.
