project('lesson01', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
glut = compiler.find_library('glut', required: false)

executable(
    'lesson05',
    'lesson5.c',
    dependencies: [glut, glu, gl]
)
