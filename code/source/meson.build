code = files('module.c')

curl = dependency('curl-8.6.0')
lib = static_library('fscl-netwark-c',
    code,
    dependencies : curl,
    include_directories: dir)

fscl_c_dep = declare_dependency(
    link_with: lib,
    dependencies : curl,
    include_directories: dir)
