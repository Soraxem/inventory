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
    width: 175.40000915527344
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  location:
    input: select
    accessorKey: location
    key: location
    id: location
    label: location
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 109
    options:
      - { label: "room", value: "room", color: "hsl(31, 95%, 90%)"}
      - { label: "attic", value: "attic", color: "hsl(140, 95%, 90%)"}
      - { label: "lent", value: "lent", color: "hsl(232, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  title:
    input: text
    accessorKey: title
    key: title
    id: title
    label: title
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 248
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  type:
    input: select
    accessorKey: type
    key: type
    id: type
    label: type
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "RL-KLT", value: "RL-KLT", color: "hsl(238,100%,50%)"}
      - { label: "F-KLT", value: "F-KLT", color: "hsl(293,100%,50%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: location
  remove_empty_folders: false
  automatically_group_files: true
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 200
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```