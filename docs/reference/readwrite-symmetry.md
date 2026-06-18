# Read/Write Symmetry Audit

- write-style actions scanned: **110**
- with a matching read: **59**
- `set_` actions with no `get_`/`list_` (real readback gaps): **12**

## High-signal gaps — `set_` with no read counterpart

- `set_cache`
- `set_caps_preset`
- `set_cdl`
- `set_clips_linked`
- `set_high_priority`
- `set_keyframe_interpolation`
- `set_mcp_update_policy`
- `set_name`
- `set_node_enabled`
- `set_title_text`
- `set_track_enable`
- `set_track_lock`

## Low-signal (create/add/insert/import — usually expected): 38

`add_clip_mattes`, `add_comp`, `add_subfolder`, `add_sync_event_markers`, `add_timeline_mattes`, `add_track`, `add_version`, `apply_arri_cdl_lut`, `apply_cuts`, `apply_fairlight_preset`, `apply_grade_from_drx`, `apply_look_to_items`, `apply_spec`, `create_compound_clip`, `create_fusion_clip`, `create_magic_mask`, `create_stereo_clip`, `create_subtitles`, `create_timeline`, `create_timeline_from_clips`, `create_variant_from_ranges`, `import_burnin`, `import_comp`, `import_folder`, `import_into_timeline`, `import_media`, `import_preset`, `import_project`, `import_render`, `import_timeline`, `import_to_pool`, `insert_audio`, `insert_fusion_composition`, `insert_fusion_generator`, `insert_fusion_title`, `insert_generator`, `insert_ofx_generator`, `insert_title`
