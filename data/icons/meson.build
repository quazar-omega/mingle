application_id = 'io.github.halfmexican.Mingle'

scalable_dir = 'hicolor' / 'scalable' / 'apps'
install_data(
  scalable_dir / ('@0@.svg').format(application_id),
  install_dir: get_option('datadir') / 'icons' / scalable_dir
)

symbolic_dir = 'hicolor' / 'symbolic' / 'apps'
install_data(
  symbolic_dir / ('@0@-symbolic.svg').format(application_id),
  install_dir: get_option('datadir') / 'icons' / symbolic_dir
)



action_dir = join_paths('hicolor', 'scalable', 'actions')
action_icons = [
    # each icon must be registered here
    join_paths(action_dir, 'dice3-symbolic.svg'),
    join_paths(action_dir, 'checkmark-small-symbolic.svg')
]

install_data(
  action_icons,
  install_dir: join_paths(get_option('datadir'), 'icons', action_dir)
)