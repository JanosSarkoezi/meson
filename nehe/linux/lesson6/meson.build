project('lesson01', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
glut = compiler.find_library('glut', required: false)

executable(
    'lesson06',
    sources: ['lesson6.c', 'Data/lesson6/NeHe.bmp'],
    dependencies: [glut, glu, gl],
)
