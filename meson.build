project('tdd-cpp', 'cpp')

add_project_arguments('-std=c++17', language : 'cpp')

src = []
inc = []

thread_dep = []
# thread_dep = dependency('thread')
gtest_dep = dependency('gtest')

subdir('inc')
subdir('src')
subdir('tests')