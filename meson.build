project('DistanceCalculator', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3', 'cpp_std=c++20'])

dep = dependency('libcurl')
executable('DistanceCalculator',
           'main.cpp',
           dependencies : dep,
           override_options : ['cpp_std=c++20'])
