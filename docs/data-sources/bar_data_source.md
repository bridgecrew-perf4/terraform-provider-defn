---
page_title: "bar_data_source Data Source - terraform-provider-defn"
subcategory: ""
description: |-
  Sample data source in the Terraform provider defn.
---

# Data Source `bar_data_source`

Sample data source in the Terraform provider defn.

## Example Usage

```terraform
data "bar_data_source" "example" {
  sample_attribute = "bar"
}
```

## Schema

### Required

- **sample_attribute** (String) Sample attribute.

### Optional

- **id** (String) The ID of this resource.


