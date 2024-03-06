code = files('module.c')

dep_curl = dependency('curl')
lib = static_library('fscl-netwark-c',
    code,
    dependencies : dep_curl,
    include_directories: dir)

fscl_c_dep = declare_dependency(
    link_with: lib,
    dependencies : dep_curl,
    include_directories: dir)
