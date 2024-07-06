# Math Library

The Math project is an implementation of the standard `math.h` library in C, developed according to the principles of structured programming. It is implemented as a static library with the following features:

- **Total verifiable accuracy**: 16 significant digits
- **Verifiable accuracy of the fractional part**: up to 6 decimal places

## Included Functions

The library includes a variety of mathematical functions:

- `abs` - Computes the absolute value of an integer value
- `acos` - Computes the arc cosine
- `asin` - Computes the arc sine
- `atan` - Computes the arc tangent
- `ceil` - Returns the nearest integer not less than the given value
- `cos` - Computes the cosine
- `exp` - Returns e raised to the given power
- `fabs` - Computes the absolute value of a floating-point value
- `floor` - Returns the nearest integer not greater than the given value
- `fmod` - Computes the remainder of the floating-point division operation
- `log` - Computes the natural logarithm
- `pow` - Raises a number to the given power
- `sin` - Computes the sine
- `sqrt` - Computes the square root
- `tan` - Computes the tangent

## Makefile Commands

The following commands are available in the `Makefile`:

- **all**: Builds the static library `s21_math.a` and runs the library tests.
- **s21_math.a**: Compiles the source files and creates the static library `s21_math.a`.
- **test**: Compiles and runs the test suite using the Check testing framework, with code coverage enabled.
- **gcov_report**: Generates a code coverage report.
- **lint**: Runs code analysis and formatting checks using `cppcheck`, `cpplint`, and `clang-format`.
- **g_clean**: Cleans up code coverage report files.
- **clean**: Removes object files, static library files, and code coverage files.
- **rebuild**: Cleans the build directory and rebuilds the static library.

### Example Usage

1. To build the library and run tests, use the following command:

```sh
make all
```

2. Creates the static library `s21_math.a`:

```sh
make s21_math.a
```

3. Compiles and runs the unit tests:

```sh
make test
```

4. To generate a code coverage report:

```sh
make gcov_report
```

5. To clean the build directory:

```sh
make clean
```

***

This project was developed by a students of School 21: jereyji, hallietw, banefort.