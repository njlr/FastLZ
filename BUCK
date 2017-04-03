cxx_library(
  name = 'fastlz',
  header_namespace = '',
  exported_headers = [
    'fastlz.h',
  ],
  srcs = [
    'fastlz.c',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = '6pack',
  srcs = [
    '6pack.c',
  ],
  deps = [
    ':fastlz',
  ],
)

cxx_binary(
  name = '6unpack',
  srcs = [
    '6unpack.c',
  ],
  deps = [
    ':fastlz',
  ],
)
