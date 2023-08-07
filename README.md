# hex_to_dec

hex to dec function without any subfunctions, loop ...

After I had googeled hours I found sowewhere in the deepness of the net-ocean a very simple, short and fast method to get the decimal value of a hex variable.

sscanf(hex, "%dec", &dec);

hex , of course is a string where the hex variable is in, dec will give a decimal variable back. I only neede it for int-variables with a length of 32 bits/ 8 characters (00000000 ... FFFFFFFF)

It's simple, short, fast.

How does it work?

sscanf writes the hex digit into a null-terminated character string buffer and scan it again into a dec variable!
