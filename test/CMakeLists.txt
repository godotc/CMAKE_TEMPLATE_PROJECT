
project(test)

add_executable(TestHello)
target_sources(TestHello PRIVATE ./hello.cc)
add_test(NAME HelloWorld COMMAND TestHello)
