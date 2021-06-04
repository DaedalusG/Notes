## 2.1.6

- in docker exec -it, -i makes sure STDIN is kept open, while -t flag allocates a psuedo terminal. I like to think of the combined flag as short for input terminal (without -i you can't type inputs into the shell, without -t terminal errors will occur and no cursor will appear in the "pseudo terminal")

## 2.2

