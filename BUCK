load('//:buckaroo_macros.bzl', 'buckaroo_deps')
load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'websocketpp',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', 'websocketpp/**/*.hpp'),
  ]),
  # srcs = glob([
  #   'websocketpp/**/*.cpp',
  # ]),
  deps = buckaroo_deps(),
  visibility = [
    'PUBLIC',
  ],
)
