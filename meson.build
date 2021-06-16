project('date', ['cpp'],
         version         : '3.0.1',
         license         : ['MIT'],
         meson_version   : '>= 0.49.0')


date_dep = declare_dependency(
  include_directories: include_directories('include')
)


install_subdir('include/date',
                install_dir : 'include')

install_data(['LICENSE.txt'],
               rename      : ['LICENSE'],
               install_dir :  'share/licenses/date')

if get_option('install_docs')
    install_subdir('doc/api', install_dir : 'share/docs/date')
    install_data(['doc/manual.pdf'], install_dir :  'share/docs/date')
endif
