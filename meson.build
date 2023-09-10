project('libaco', 'c', default_options: ['default_library=static'])

libaco_incdir = include_directories('.')
libaco_libsources = files('aco.c', 'acosw.S')

libaco_dep = declare_dependency(
    include_directories : libaco_incdir,
    sources : libaco_libsources
)
