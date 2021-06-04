## 2.1.6

- in docker exec -it, -i makes sure STDIN is kept open, while -t flag allocates a psuedo terminal. I like to think of the combined flag as short for input terminal