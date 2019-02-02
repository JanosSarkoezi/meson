project('lesson01', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
glut = compiler.find_library('glut', required: false)

subdir('Data')

executable(
    'lesson06',
    sources: 'lesson6.c',
    dependencies: [glut, glu, gl],
)
