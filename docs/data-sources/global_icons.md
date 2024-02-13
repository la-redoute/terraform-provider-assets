---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "assets_global_icons Data Source - terraform-provider-assets"
subcategory: ""
description: |-
  
---

# assets_global_icons (Data Source)



## Example Usage

```terraform
data "assets_global_icons" "example" {
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `icons` (Attributes Set) All existing global icons (see [below for nested schema](#nestedatt--icons))

<a id="nestedatt--icons"></a>
### Nested Schema for `icons`

Read-Only:

- `id` (String)
- `name` (String)
- `url16` (String) A url to the icon to display with small resolution.
- `url48` (String) A url to the icon to display with large resolution