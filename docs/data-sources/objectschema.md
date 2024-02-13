---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "assets_objectschema Data Source - terraform-provider-assets"
subcategory: ""
description: |-
  
---

# assets_objectschema (Data Source)



## Example Usage

```terraform
data "assets_objectschema" "example" {
  id = "42"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) The object schema id

### Read-Only

- `can_manage` (Boolean)
- `created` (String)
- `description` (String)
- `global_id` (String)
- `name` (String)
- `object_count` (Number)
- `object_schema_key` (String)
- `object_type_count` (Number)
- `status` (String) Always 'Ok'
- `updated` (String)
- `workspace_id` (String)