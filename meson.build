project('hippo-layout-tv')

gnome = import('gnome')
i18n = import('i18n')

uuid = 'hippo-layout-tv@djaquels'
rdnn = 'org.gnome.shell.extensions.hippo-layout-tv'

datadir = get_option('datadir')
extension_dir = datadir / 'gnome-shell' / 'extensions' / uuid

install_data(
  [
    'extension.js',
    'metadata.json',
    'prefs.js',
    'stylesheet.css',
  ],
  install_dir : extension_dir,
)

install_subdir('lib', install_dir : extension_dir)

subdir('schemas')
subdir('po')
