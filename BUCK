include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'regex', 
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  preprocessor_flags = [
    '-DBOOST_HAS_ICU=1', 
  ], 
  srcs = glob([
    'src/**/*.cpp', 
  ]), 
  deps = BUCKAROO_DEPS,
  visibility = [
    'PUBLIC',
  ],
)
