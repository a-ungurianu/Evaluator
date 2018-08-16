# Evaluator

Small python script I used to cycle through some tests in a folder and execute a binary to check if that solution is correct.


## Usage
    evaluate [-h] [--time-limit time_limit]
                  [--first-test first_test]
                  name no_t

* name - The name of the binary (also used as basename for test files and input files)

* no_t - The number of tests to be executed.

* time_limit - The time that allocated to run the solution

* first_test - Used to indicate the id of the first test (in case it starts at a number other than 0)


This program assumes that all the tests are in a folder called 'tests' and that they are named as such:

* {no}-{name}.in - for the input file

* {no}-{name}.ok - for the correct output file

where `no` is the number of the file and name is the `name` of the binary
