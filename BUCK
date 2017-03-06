include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'double-conversion',
  header_namespace = 'double-conversion',
  exported_headers = subdir_glob([
    ('src', 'src/*.h'), 
  ]),
  srcs = glob([
    'src/*.cc',
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
