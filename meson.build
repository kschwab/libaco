project('libaco', 'c')

libaco_incdir = include_directories('.')
libaco_libsources = ['aco.c', 'acosw.S']

libaco_dep = declare_dependency(
    include_directories : libaco_incdir,
    sources : libaco_libsources
)
