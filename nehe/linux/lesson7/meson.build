project('lesson07', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
glut = compiler.find_library('glut', required: false)

subdir('Data')

executable(
    'lesson07',
    sources: 'lesson7.c',
    dependencies: [glut, glu, gl],
)
