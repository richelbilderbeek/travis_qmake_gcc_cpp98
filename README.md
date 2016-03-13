# travis_qmake_gcc_cpp98

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98)

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++98`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`

More complex builds:
 * Use of C++11: [travis_qmake_gcc_cpp11](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11)
 * Use of C++14: [travis_qmake_gcc_cpp11](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14)
 * Use the Boost libraries: [travis_qmake_gcc_cpp98_boost](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_boost)
 * Code coverage: `codecov`: [travis_qmake_gcc_cpp98_gcov](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_gcov)
