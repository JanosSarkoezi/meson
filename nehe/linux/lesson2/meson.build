project('lesson02', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
glut = compiler.find_library('glut')

executable(
    'lesson02',
    'lesson2.c',
    dependencies: [glut, glu, gl]
)
