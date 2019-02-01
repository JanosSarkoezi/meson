project('lesson01', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
glut = compiler.find_library('glut', required: false)

executable(
    'lesson04',
    'lesson4.c',
    dependencies: [glut, glu, gl]
)
