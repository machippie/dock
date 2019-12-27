
## Default Variables

### dock_auto_hide

Auto hide

#### Default value

```yaml
dock_auto_hide: true
```

### dock_general_apps

Apps listed on main area within dock

#### Default value

```yaml
dock_general_apps:
  - /System/Applications/Launchpad.app
```

### dock_hot_corner_bottom_left

Bottom left corner action

#### Default value

```yaml
dock_hot_corner_bottom_left: 3
```

### dock_hot_corner_bottom_right

Bottom right corner action

#### Default value

```yaml
dock_hot_corner_bottom_right: 3
```

### dock_hot_corner_top_left

Top left corner action

#### Default value

```yaml
dock_hot_corner_top_left: 2
```

### dock_hot_corner_top_right

Top right corner action

#### Default value

```yaml
dock_hot_corner_top_right: 2
```

### dock_interface_style

Apple interface style

#### Default value

```yaml
dock_interface_style: Dark
```

### dock_large_size

Large size

#### Default value

```yaml
dock_large_size: 60
```

### dock_launch_animation

Launch animation

#### Default value

```yaml
dock_launch_animation: true
```

### dock_magnification

Enable magnification

#### Default value

```yaml
dock_magnification: true
```

### dock_minimize_to_app

Minimize to application

#### Default value

```yaml
dock_minimize_to_app: true
```

### dock_other_apps

Apps listed on other area within dock

#### Default value

```yaml
dock_other_apps:
  - /Users/${USER}/Downloads
```

### dock_show_hidden

Show hidden

#### Default value

```yaml
dock_show_hidden: true
```

### dock_show_process_indicator

Show process indicator

#### Default value

```yaml
dock_show_process_indicator: false
```

### dock_show_recent_apps

Show recent apps

#### Default value

```yaml
dock_show_recent_apps: false
```

### dock_tile_size

Tile size

#### Default value

```yaml
dock_tile_size: 30
```

### dock_user

User to run user-specific commands

#### Default value

```yaml
dock_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
