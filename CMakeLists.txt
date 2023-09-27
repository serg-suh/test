cmake_minimum_required (VERSION 3.13)

project(test)

add_executable(test aa.c)

enable_testing()
add_executable(tester tester.c)
add_test(Tester tester)
