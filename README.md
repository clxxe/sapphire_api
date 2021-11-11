# sapphire script api.

callbacks:
- `on_gui()`
- `on_client_input(base_player, input_state)`

renderer functions:
- `draw_text(x, y, str, color, drop_shadow, outline, centered)`
- `draw_rect(x, y, w, h, color)`
- `draw_filled_rect(x, y, w, h, color)`
- `draw_line(x, y, x1, y1, color)`
- `world_to_screen( world_position )`

entity list functions:
- `get_entity_list()`
- `get_size()`
- `is_player(index)`
- `get_player(index)`
- `get_local_player()`

base player functions:
- `get_health()`
- `get_size()`
- `set_flags(flags)`
- `get_bone_position(bone_id)`
- `is_alive()`
- `get_name()`

misc functions:
- `load(script_file_path)`
- `color(r, g, b)`
- `color(r, g, b, a)`
- `vec3_t(x, y, z)`
