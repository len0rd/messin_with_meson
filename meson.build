project('a6000_drv', 'c', 'cpp')
dep_gphoto = dependency('Gphoto2', method : 'cmake', cmake_module_path : 'CMakeModules/')
add_global_arguments('--std=c++11', language : 'cpp')

subdir('driver')
subdir('camera')
