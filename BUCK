prebuilt_cxx_library(
  name = 'kashmir',
  header_only = True,
  header_namespace = 'kashmir',
  exported_headers = subdir_glob([
    ('kashmir', '**/*.h'),
  ]),
  licenses = [
    'LICENSE_1_0.txt',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'cli',
  srcs = [
    'cli.cpp',
  ],
  deps = [
    ':kashmir',
  ],
)
