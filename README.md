Testing what I have learnt so far to build a mini version of the grep tool in Rust
The grep tool basically takes in two arguments which are a file we want to search, and a string we want to search for. So my mini grep program has to be able to do the following:
1. It has to be able to read command line arguments
2. It has to be able to read from the file passed in as an argument
3. It has to be able to search for the query string in the contents of the file line by line
4. It has to be able to print the lines that contain the query string out to the screen
5. It has to be able to send error messages to the stderr stream and accurate output messages to the stdout stream
