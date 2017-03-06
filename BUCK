include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'double-conversion',
  header_namespace = 'double-conversion',
  exported_headers = [
    'double-conversion/bignum.h',
    'double-conversion/bignum-dtoa.h',
    'double-conversion/cached-powers.h',
    'double-conversion/diy-fp.h',
    'double-conversion/double-conversion.h',
    'double-conversion/fast-dtoa.h',
    'double-conversion/fixed-dtoa.h',
    'double-conversion/ieee.h',
    'double-conversion/strtod.h',
  ],
  headers = [
    'double-conversion/utils.h',
  ],
  srcs = [
    'double-conversion/bignum.cc',
    'double-conversion/bignum-dtoa.cc',
    'double-conversion/cached-powers.cc',
    'double-conversion/diy-fp.cc',
    'double-conversion/double-conversion.cc',
    'double-conversion/fast-dtoa.cc',
    'double-conversion/fixed-dtoa.cc',
    'double-conversion/strtod.cc',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
