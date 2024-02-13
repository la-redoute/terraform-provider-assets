---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "assets_icon Data Source - terraform-provider-assets"
subcategory: ""
description: |-
  
---

# assets_icon (Data Source)



## Example Usage

```terraform
data "assets_icon" "example" {
  id = "42"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `id` (String) The ID of this resource.
- `name` (String)
- `url16` (String) A url to the icon to display with small resolution
- `url48` (String) A url to the icon to display with large resolution