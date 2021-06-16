project('date', ['cpp'],
         version         : '3.0.1',
         license         : ['MIT'],
         meson_version   : '>= 0.49.0')


date_dep = declare_dependency(
  include_directories: include_directories('include')
)


install_subdir('include/date',
                install_dir : 'include')

install_subdir('docs',
 			   strip_directory : true,
			   install_dir     : 'share/docs/date')

install_data(['LICENSE.txt'],
               rename      : ['LICENSE'],
               install_dir :  'share/licenses/date')
