project('lesson02', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
# m    = compiler.find_library('m', required : false)
glut = compiler.find_library('glut', required: false)

executable(
    'lesson02',
    'lesson2.c',
    # dependencies: [glut, glu, gl, m]
    dependencies: [glut, glu, gl]
)
