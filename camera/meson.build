dir_inc_camera = include_directories('inc', '../driver/inc')
srcs_camera_lib = ['src/camera_config_defs.cpp',
    'src/camera_connector.cpp',
    'src/exif.cpp']

lib_camera = static_library('a6000_camera',
    srcs_camera_lib,
    include_directories : dir_inc_camera,
    link_with : lib_gphoto_drv)

exec_test_camera = executable('exec_test_camera',
    'test/main.cpp',
    include_directories : dir_inc_camera,
    link_with : lib_camera)

test('camera test', exec_test_camera)

