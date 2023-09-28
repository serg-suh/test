cmake_minimum_required (VERSION 3.13)

project(mytest)

add_executable(mytest aa.c)

enable_testing()
add_executable(tester tester.c)
add_test(Tester tester)
