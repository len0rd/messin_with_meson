dir_inc_gphoto_drv = include_directories('inc')
srcs_gphoto_drv = ['src/capture.c',
    'src/config.c',
    'src/context.c',
    'src/trigger_capture.c']

lib_gphoto_drv = static_library('gphoto_drv',
    srcs_gphoto_drv,
    include_directories : dir_inc_gphoto_drv,
    dependencies : dep_gphoto)
