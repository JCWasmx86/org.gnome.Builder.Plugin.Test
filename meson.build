project('testplugin', 'c')

dependencies = [
    dependency('gnome-builder-44.0')
]
shared_module('testplugin',
              'test.c',
              dependencies: dependencies,
              install: true)
configure_file(input: 'test.plugin',
               output: 'test.plugin',
               copy: true)
