---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "assets_objecttype Resource - terraform-provider-assets"
subcategory: ""
description: |-
  
---

# assets_objecttype (Resource)



## Example Usage

```terraform
resource "assets_objecttype" "example" {
  name             = "example"
  icon_id          = "42"
  object_schema_id = "42"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `icon_id` (String)
- `name` (String)
- `object_schema_id` (String)

### Optional

- `abstract_object_type` (Boolean)
- `description` (String)
- `inherited` (Boolean) Describes if this object type is configured for inheritance i.e. it's children inherits the attributes of this object type
- `parent_object_type_id` (String) The id of the parent object type

### Read-Only

- `created` (String)
- `global_id` (String)
- `id` (String) The ID of this resource.
- `object_count` (Number)
- `parent_object_type_inherited` (Boolean) Describes if this object types parent is inherited i.e. this object type has attributes that are inherited from one or more parents
- `position` (Number)
- `updated` (String)
- `workspace_id` (String)

## Import

Import is supported using the following syntax:

```shell
# Objecttype can be imported by specifying the identifier
terraform import assets_objecttype.example 42
```