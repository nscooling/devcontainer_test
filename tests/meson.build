
widget_tests = executable(
  'widget_tests', sources
  : [ 'test_main.cpp', 'widget_tests.cpp', src ], include_directories
  : inc, dependencies
  : [ gtest_dep, thread_dep ])


test('buffer_tests', widget_tests)
