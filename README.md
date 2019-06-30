GoogleTestResultReader

## PURPOSE
This will display the googletest result of execution from a compiled executable. Instead of manually scrolling through the prints of all the other testcases just to see the execution and result of a particular testcase, this script can help by displaying the result of a target testcase. But if wanted, it could also display the whole run too.

## REQUIREMENTS
1. GNU/Linux environment
    * Either:
        1. Full operating system
        2. Virtual machine (as a guest OS)
        3. Cygwin
        3. etc.
2. Git (optional if you just prefer to do a download and extract from GitHub)
    ~~~
    sudo apt install git
    ~~~

## USAGE
~~~
git clone https://github.com/nponcian/GoogleTestResultReader.git
cd GoogleTestResultReader
./readgtest --help
./readgtest ../Path/To/Compiled/Executable/Running/Tests
./readgtest ../Path/To/Compiled/Executable/Running/Tests --all
./readgtest ../Path/To/Compiled/Executable/Running/Tests --test FactorialTest
~~~
