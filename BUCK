include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'regex', 
  header_only = True,
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  srcs = glob([
    'src/**/*.cpp', 
  ]), 
  deps = BUCKAROO_DEPS,
  visibility = [
    'PUBLIC',
  ],
)
