---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
  Tags:
    input: tags
    key: Tags
    accessorKey: Tags
    label: Tags
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "GM_Screen", backgroundColor: "hsl(149, 95%, 90%)"}
      - { label: "Combat_Rules", backgroundColor: "hsl(180, 95%, 90%)"}
      - { label: "AC", backgroundColor: "hsl(331, 95%, 90%)"}
      - { label: "Attack", backgroundColor: "hsl(179, 95%, 90%)"}
      - { label: "Combat_Maneuvers", backgroundColor: "hsl(11, 95%, 90%)"}
      - { label: "Concentration", backgroundColor: "hsl(119, 95%, 90%)"}
      - { label: "2Weapons", backgroundColor: "hsl(141, 95%, 90%)"}
      - { label: "Conditions", backgroundColor: "hsl(2, 95%, 90%)"}
      - { label: "Equipment_Rules", backgroundColor: "hsl(101, 95%, 90%)"}
      - { label: "Gamemastering", backgroundColor: "hsl(305, 95%, 90%)"}
      - { label: "Experience", backgroundColor: "hsl(166, 95%, 90%)"}
      - { label: "Treasure", backgroundColor: "hsl(111, 95%, 90%)"}
      - { label: "Character_Creation", backgroundColor: "hsl(274, 95%, 90%)"}
      - { label: "Skills", backgroundColor: "hsl(86, 95%, 90%)"}
      - { label: "Acrobatics", backgroundColor: "hsl(248, 95%, 90%)"}
      - { label: "Bluff", backgroundColor: "hsl(312, 95%, 90%)"}
      - { label: "Climb", backgroundColor: "hsl(181, 95%, 90%)"}
      - { label: "Diplomacy", backgroundColor: "hsl(318, 95%, 90%)"}
      - { label: "Disable_Device", backgroundColor: "hsl(60, 95%, 90%)"}
      - { label: "Fly", backgroundColor: "hsl(245, 95%, 90%)"}
      - { label: "Heal", backgroundColor: "hsl(118, 95%, 90%)"}
      - { label: "Knowledge", backgroundColor: "hsl(167, 95%, 90%)"}
      - { label: "Perception", backgroundColor: "hsl(58, 95%, 90%)"}
      - { label: "Ride", backgroundColor: "hsl(131, 95%, 90%)"}
      - { label: "Spellcraft", backgroundColor: "hsl(294, 95%, 90%)"}
      - { label: "Survival", backgroundColor: "hsl(290, 95%, 90%)"}
      - { label: "Swim", backgroundColor: "hsl(117, 95%, 90%)"}
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  source_data: current_folder
  source_form_result: root
  source_destination_path: /
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: 
  pagination_size: 10
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
filters:
  enabled: false
  conditions:
```