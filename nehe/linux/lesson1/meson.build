project('lesson01', 'c')

compiler = meson.get_compiler('c')

glu  = dependency('glu')
gl   = dependency('gl')
# m    = compiler.find_library('m', required : false)
glut = compiler.find_library('glut', required: false)

executable(
    'lesson01',
    'lesson1.c',
    # dependencies: [glut, glu, gl, m]
    dependencies: [glut, glu, gl]
)
