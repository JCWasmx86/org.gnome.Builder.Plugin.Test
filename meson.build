project('testplugin', 'c')

dependencies = [
    dependency('gnome-builder-44.0')
]
shared_module('testplugin',
              'test.c',
              dependencies: dependencies,
              #install_dir: get_option('prefix') / 'lib/gnome-builder/plugins',
              install: true)
install_data('test.plugin',
             #install_dir: get_option('prefix') / 'lib/gnome-builder/plugins'
)
configure_file(input: 'test.plugin',
               output: 'test.plugin',
               copy: true)
