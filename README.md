# minigrep
A command line tool written in Idiomatic Rust for the grep command and Based on a tutorial provided by the Rust book. This is an exercise for learning basics of Rust and fouces on below areas-

* Reading and processing arguments from command line. Although there are crates for that.
* How to organise code to main and lib files
* Error handling using Result<T,E>
* Environment variables, Process and File handling
* Automated testing


# Usage
minigrep <text_to_search> <file_name>

eg. minigrep you poem.txt

returns the lines having the word 'you' in the poem.txt file (also committed)
