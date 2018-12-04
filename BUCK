load('//:subdir_glob.bzl', 'subdir_glob')
load('//:buckaroo_macros.bzl', 'buckaroo_deps')

cxx_library(
  name = 'aws-c-event-stream', 
  header_namespace = '', 
  exported_headers = subdir_glob([
    ('include', '**/*.h'), 
  ]), 
  srcs = glob([
    'source/**/*.c', 
  ]), 
  deps = buckaroo_deps(), 
  visibility = [
    'PUBLIC', 
  ], 
)
