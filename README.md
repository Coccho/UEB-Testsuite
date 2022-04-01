# UEB-Testsuite

A testsuite for the Übersetzterbau (Compilers) at [TU Wien](https://www.tuwien.at/en/) 2022S.

## Usage

1. `git clone https://github.com/flofriday/UEB-Testsuite.git ~/test`
2. Run the tests as described in the individual test-suite folders for the tasks

Every exercise has its own folder with a README.md for instructions on how to
use its tests.

## Other Tipps
[Compiler Explorer](https://godbolt.org/z/PjP4r1GqP) is a Website with which you can discover how different compilers translate code to machine instructions.

When compiling code generated with flex and `-Wall` you will get warnings that `input` and `yyunput` is unused. By adding the following lines to the top of the file you can fix those warnings.
```
%option noinput
%option nounput
```

## Contributing

Contributions are very welcome, feel free to just create a PR.
You are awesome 😊🎉
