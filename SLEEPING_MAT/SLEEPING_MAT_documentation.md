# SLEEPING_MAT Schema Documentation

**Schema Version:** https://schemas.amazon.com/selling-partners/definitions/product-types/meta-schema/v1

## Required Fields

- `brand`
- `bullet_point`
- `country_of_origin`
- `item_name`
- `item_type_keyword`
- `product_description`
- `supplier_declared_dg_hz_regulation`

## Conditionally Required Fields

- `externally_assigned_product_identifier` - Required when selectors `marketplace_id`, `type` are specified
- `merchant_suggested_asin` - Required when selectors `marketplace_id`, `value` are specified
- `package_contains_sku` - Required when selectors `marketplace_id`, `sku` are specified
- `fulfillment_availability` - Required when selectors `fulfillment_channel_code` are specified
- `purchasable_offer` - Required when selectors `marketplace_id`, `currency`, `audience` are specified
- `list_price` - Required when selectors `marketplace_id`, `currency` are specified
- `num_batteries` - Required when selectors `marketplace_id`, `type` are specified
- `hazmat` - Required when selectors `marketplace_id`, `aspect` are specified
- `regulatory_compliance_certification` - Required when selectors `marketplace_id`, `regulation_type` are specified
- `compliance_media` - Required when selectors `marketplace_id`, `content_type`, `content_language` are specified
- `ghs_chemical_h_code` - Required when selectors `marketplace_id`, `value` are specified
- `externally_assigned_product_identifier.type` - Required when `externally_assigned_product_identifier` is provided
- `externally_assigned_product_identifier.value` - Required when `externally_assigned_product_identifier` is provided
- `merchant_suggested_asin.value` - Required when `merchant_suggested_asin` is provided
- `supplier_declared_has_product_identifier_exemption.value` - Required when `supplier_declared_has_product_identifier_exemption` is provided
- `package_level.value` - Required when `package_level` is provided
- `package_contains_sku.quantity` - Required when `package_contains_sku` is provided
- `package_contains_sku.sku` - Required when `package_contains_sku` is provided
- `target_audience.value` - Required when `target_audience` is provided
- `target_audience.language_tag` - Required when `target_audience` is provided
- `model_number.value` - Required when `model_number` is provided
- `model_name.value` - Required when `model_name` is provided
- `model_name.language_tag` - Required when `model_name` is provided
- `manufacturer.value` - Required when `manufacturer` is provided
- `manufacturer.language_tag` - Required when `manufacturer` is provided
- `skip_offer.value` - Required when `skip_offer` is provided
- `fulfillment_availability.fulfillment_channel_code` - Required when `fulfillment_availability` is provided
- `map_policy.value` - Required when `map_policy` is provided
- `condition_type.value` - Required when `condition_type` is provided
- `condition_note.value` - Required when `condition_note` is provided
- `condition_note.language_tag` - Required when `condition_note` is provided
- `list_price.value` - Required when `list_price` is provided
- `list_price.currency` - Required when `list_price` is provided
- `product_tax_code.value` - Required when `product_tax_code` is provided
- `merchant_release_date.value` - Required when `merchant_release_date` is provided
- `merchant_shipping_group.value` - Required when `merchant_shipping_group` is provided
- `max_order_quantity.value` - Required when `max_order_quantity` is provided
- `main_offer_image_locator.media_location` - Required when `main_offer_image_locator` is provided
- `other_offer_image_locator_1.media_location` - Required when `other_offer_image_locator_1` is provided
- `other_offer_image_locator_2.media_location` - Required when `other_offer_image_locator_2` is provided
- `other_offer_image_locator_3.media_location` - Required when `other_offer_image_locator_3` is provided
- `other_offer_image_locator_4.media_location` - Required when `other_offer_image_locator_4` is provided
- `other_offer_image_locator_5.media_location` - Required when `other_offer_image_locator_5` is provided
- `import_designation.value` - Required when `import_designation` is provided
- `import_designation.language_tag` - Required when `import_designation` is provided
- `handmade_classification.value` - Required when `handmade_classification` is provided
- `generic_keyword.value` - Required when `generic_keyword` is provided
- `generic_keyword.language_tag` - Required when `generic_keyword` is provided
- `special_feature.value` - Required when `special_feature` is provided
- `special_feature.language_tag` - Required when `special_feature` is provided
- `style.value` - Required when `style` is provided
- `style.language_tag` - Required when `style` is provided
- `material.value` - Required when `material` is provided
- `material.language_tag` - Required when `material` is provided
- `number_of_items.value` - Required when `number_of_items` is provided
- `item_package_quantity.value` - Required when `item_package_quantity` is provided
- `water_resistance_level.value` - Required when `water_resistance_level` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `part_number.value` - Required when `part_number` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `voltage.value` - Required when `voltage` is provided
- `tension_level.value` - Required when `tension_level` is provided
- `tension_level.language_tag` - Required when `tension_level` is provided
- `volume_capacity_name.value` - Required when `volume_capacity_name` is provided
- `volume_capacity_name.language_tag` - Required when `volume_capacity_name` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `golf_club_flex.value` - Required when `golf_club_flex` is provided
- `golf_club_flex.language_tag` - Required when `golf_club_flex` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `golf_club_loft.value` - Required when `golf_club_loft` is provided
- `golf_club_loft.unit` - Required when `golf_club_loft` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `hand_orientation.value` - Required when `hand_orientation` is provided
- `hand_orientation.language_tag` - Required when `hand_orientation` is provided
- `display_maximum_weight_recommendation.value` - Required when `display_maximum_weight_recommendation` is provided
- `seating_group.value` - Required when `seating_group` is provided
- `seating_group.language_tag` - Required when `seating_group` is provided
- `variety.value` - Required when `variety` is provided
- `variety.language_tag` - Required when `variety` is provided
- `item_length_width_thickness.length` - Required when `item_length_width_thickness` is provided
- `item_length_width_thickness.thickness` - Required when `item_length_width_thickness` is provided
- `item_length_width_thickness.width` - Required when `item_length_width_thickness` is provided
- `parentage_level.value` - Required when `parentage_level` is provided
- `child_parent_sku_relationship.child_relationship_type` - Required when `child_parent_sku_relationship` is provided
- `variation_theme.name` - Required when `variation_theme` is provided
- `warranty_description.value` - Required when `warranty_description` is provided
- `warranty_description.language_tag` - Required when `warranty_description` is provided
- `batteries_required.value` - Required when `batteries_required` is provided
- `batteries_included.value` - Required when `batteries_included` is provided
- `num_batteries.quantity` - Required when `num_batteries` is provided
- `num_batteries.type` - Required when `num_batteries` is provided
- `number_of_lithium_metal_cells.value` - Required when `number_of_lithium_metal_cells` is provided
- `number_of_lithium_ion_cells.value` - Required when `number_of_lithium_ion_cells` is provided
- `hazmat.aspect` - Required when `hazmat` is provided
- `hazmat.value` - Required when `hazmat` is provided
- `safety_data_sheet_url.value` - Required when `safety_data_sheet_url` is provided
- `safety_data_sheet_url.language_tag` - Required when `safety_data_sheet_url` is provided
- `item_weight.value` - Required when `item_weight` is provided
- `item_weight.unit` - Required when `item_weight` is provided
- `california_proposition_65.compliance_type` - Required when `california_proposition_65` is provided
- `regulatory_compliance_certification.regulation_type` - Required when `regulatory_compliance_certification` is provided
- `regulatory_compliance_certification.value` - Required when `regulatory_compliance_certification` is provided
- `dsa_responsible_party_address.value` - Required when `dsa_responsible_party_address` is provided
- `compliance_media.content_type` - Required when `compliance_media` is provided
- `compliance_media.content_language` - Required when `compliance_media` is provided
- `compliance_media.source_location` - Required when `compliance_media` is provided
- `gpsr_safety_attestation.value` - Required when `gpsr_safety_attestation` is provided
- `ships_globally.value` - Required when `ships_globally` is provided
- `ghs_chemical_h_code.value` - Required when `ghs_chemical_h_code` is provided
- `main_product_image_locator.media_location` - Required when `main_product_image_locator` is provided
- `other_product_image_locator_1.media_location` - Required when `other_product_image_locator_1` is provided
- `other_product_image_locator_2.media_location` - Required when `other_product_image_locator_2` is provided
- `other_product_image_locator_3.media_location` - Required when `other_product_image_locator_3` is provided
- `other_product_image_locator_4.media_location` - Required when `other_product_image_locator_4` is provided
- `other_product_image_locator_5.media_location` - Required when `other_product_image_locator_5` is provided
- `other_product_image_locator_6.media_location` - Required when `other_product_image_locator_6` is provided
- `other_product_image_locator_7.media_location` - Required when `other_product_image_locator_7` is provided
- `other_product_image_locator_8.media_location` - Required when `other_product_image_locator_8` is provided
- `swatch_product_image_locator.media_location` - Required when `swatch_product_image_locator` is provided
- `item_package_dimensions.length` - Required when `item_package_dimensions` is provided
- `item_package_dimensions.width` - Required when `item_package_dimensions` is provided
- `item_package_dimensions.height` - Required when `item_package_dimensions` is provided
- `item_package_weight.value` - Required when `item_package_weight` is provided
- `item_package_weight.unit` - Required when `item_package_weight` is provided
- `item_display_weight.value` - Required when `item_display_weight` is provided
- `item_display_weight.unit` - Required when `item_display_weight` is provided

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `item_name` | array | Provide a title for the item that may be customer facing |
| `brand` | array | An alphanumeric string; 50 characters maximum. |
| `externally_assigned_product_identifier` | array | Provide the external ID (barcode) type and corresponding value that is being used to identify the product |
| `merchant_suggested_asin` | array | Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID. |
| `supplier_declared_has_product_identifier_exemption` | array | Please specify if the product is exempt from supplier declared external product identifiers. |
| `item_type_keyword` | array | What is the item that you are selling? |
| `package_level` | array | Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy. |
| `package_contains_sku` | array | Provide the SKU and quantity of the child items contained in the next package level. |
| `target_audience` | array | Specify the target audience that the product is intended for |
| `model_number` | array | Provide the manufacturer 's model number for the item |
| `model_name` | array | Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size |
| `manufacturer` | array | An alphanumeric string; 50 characters maximum. |
| `skip_offer` | array | Please indicate whether the offer should be skipped and a buyable offer should not be created. A value of "Yes", means no offer will be created. |
| `fulfillment_availability` | array | For those merchants using Amazon fulfillment services, please provide associated logistical information. |
| `map_policy` | array | Select one. |
| `purchasable_offer` | array | The attribute indicates the Purchasable Offer of the product |
| `condition_type` | array | Provide the actual condition type of the product |
| `condition_note` | array | Provide descriptive text explaining the actual condition of the item |
| `list_price` | array | Provide the list price for the product. List Price is the suggested retail price of a product as provided by a manufacturer, supplier, or seller. This is not the offering or cost price. |
| `product_tax_code` | array | Enter the product tax code supplied to you by Amazon.com |
| `merchant_release_date` | array | A date in this format: yyyy-mm-dd. |
| `merchant_shipping_group` | array | The ship configuration group for an offer. The ship configuration group is created and managed by the seller through the ship setting UI. |
| `max_order_quantity` | array | Max order quantity. |
| `gift_options` | array | Provide gift card options |
| `main_offer_image_locator` | array | Provide the location of the image |
| `other_offer_image_locator_1` | array | Provide the location of the image |
| `other_offer_image_locator_2` | array | Provide the location of the image |
| `other_offer_image_locator_3` | array | Provide the location of the image |
| `other_offer_image_locator_4` | array | Provide the location of the image |
| `other_offer_image_locator_5` | array | Provide the location and source of the image |
| `import_designation` | array | Provide the country of origin to assist in import classification and duties for the item. |
| `supplemental_condition_information` | array | Provide the additional condition information on the non-new product. |
| `handmade_classification` | array | Select the value that best describes how the product was produced |
| `product_description` | array | A text string; 2000 characters maximum in length. Note: Type 1 High ASCII characters (®, ©, ™, etc.) or other special characters are not supported. |
| `bullet_point` | array | An alphanumeric string; 500 characters maximum length per bullet point. Please do not include an actual bullet point object, just the text used to describe your product.  Note: Type 1 High ASCII characters (®, ©, ™, etc.) or other special characters are not supported. |
| `generic_keyword` | array | A text string; 50 characters maximum in length.  This is in addition to the valid values that you must submit for your product. |
| `special_feature` | array | Use the column SpecialFeatures in the Valid Values list. An alphanumeric string; 50 characters maximum. |
| `style` | array | The style of the item |
| `material` | array | Use the column MaterialType in the Valid Values list. An alphanumeric string; 50 characters maximum. |
| `number_of_items` | array | A positive whole number. |
| `item_package_quantity` | array | A positive integer |
| `wheel` | array | Provide wheel information |
| `water_resistance_level` | array | An alphanumeric string; 50 characters maximum. |
| `color` | array | Provide the color of the product |
| `size` | array | Please refer to the Sporting Goods Style Guide . An alphanumeric string; 50 characters maximum. |
| `part_number` | array | An alphanumeric string; 40 characters maximum. |
| `item_shape` | array | An alphanumeric string; 50 characters maximum. |
| `shaft` | array | The attribute indicates Shaft of the product |
| `edition` | array | Provide the version or edition of the item |
| `lens` | array | The attribute indicates Lens of the product |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `voltage` | array | Provide the item's voltage |
| `tension_level` | array | An alphanumeric string; 50 characters maximum. |
| `volume_capacity_name` | array | An alphanumeric string; 50 characters maximum. |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | A date in this format: yyyy-mm-dd. |
| `golf_club_flex` | array | Flex type for golf clubs |
| `included_components` | array | A text string; 1,000 characters maximum in length. |
| `golf_club_loft` | array | Golf club loft |
| `league_name` | array | Name of league associated with this event. |
| `team_name` | array | Provide the name of the sports team associated with the sleeping mat, indicating the product's affiliation or branding. |
| `scent` | array | Provide a description of the scent of the item |
| `hand_orientation` | array | Is this item built for lefties or righties? |
| `display_maximum_weight_recommendation` | array | The attribute indicates the Display Maximum Weight Recommendation of the product |
| `grip` | array | The attribute indicates Grip of the product |
| `head` | array | The attribute indicates Head of the product |
| `insulation` | array | The attribute indicates Insulation of the product |
| `seating_group` | array |  |
| `variety` | array | Describes what variety of item this is. |
| `item_length_width_thickness` | array | The length, width and thickness of the item in ready to use condition. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `country_of_origin` | array | Use the column CountryOfOrigin in the Valid Values list. An alphanumeric string; 2 characters maximum. |
| `warranty_description` | array | An alphanumeric string; 50 characters maximum. |
| `batteries_required` | array | Select: true or false |
| `batteries_included` | array | Select: true or false |
| `battery` | array | Provide battery information |
| `num_batteries` | array | Provide the quantity and type of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided |
| `number_of_lithium_metal_cells` | array | A positive whole number. |
| `number_of_lithium_ion_cells` | array | A positive whole number. |
| `lithium_battery` | array | The attribute indicates the Lithium Battery of the product |
| `supplier_declared_dg_hz_regulation` | array | Provide the regulations that apply to the item if it is classified as a dangerous good, hazardous material, substance, or waste. |
| `ghs` | array | Provide the Global Harmonized System (GHS) information |
| `hazmat` | array | Provide hazmat information that is relevant to the product based on the aspect selected |
| `safety_data_sheet_url` | array | Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances. |
| `item_weight` | array | A number with up to 10 digits allowed to the left of the decimal point and 2 digits to the right of the decimal point. Please do not use commas. |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations. |
| `compliance_media` | array | Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager. |
| `gpsr_safety_attestation` | array | Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it. |
| `gpsr_manufacturer_reference` | array | Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL. |
| `ships_globally` | array | Provide whether the item can be shipped globally by Amazon  |
| `ghs_chemical_h_code` | array | Provide the GHS chemical hazard codes for the chemical substance/mixture in order to display warnings to customers. |
| `main_product_image_locator` | array | The attribute indicates the Main Product Image Locator of the product |
| `other_product_image_locator_1` | array | The attribute indicates the Other Product Image Locator 1 of the product |
| `other_product_image_locator_2` | array | The attribute indicates the Other Product Image Locator 2 of the product |
| `other_product_image_locator_3` | array | The attribute indicates the Other Product Image Locator 3 of the product |
| `other_product_image_locator_4` | array | The attribute indicates the Other Product Image Locator 4 of the product |
| `other_product_image_locator_5` | array | The attribute indicates the Other Product Image Locator 5 of the product |
| `other_product_image_locator_6` | array | The attribute indicates the Other Product Image Locator 6 of the product |
| `other_product_image_locator_7` | array | The attribute indicates the Other Product Image Locator 7 of the product |
| `other_product_image_locator_8` | array | The attribute indicates the Other Product Image Locator 8 of the product |
| `swatch_product_image_locator` | array | The attribute indicates the Swatch Product Image Locator of the product |
| `item_package_dimensions` | array | Provide the item's package dimensions |
| `item_package_weight` | array | A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point. |
| `item_display_weight` | array | A number with up to 10 digits allowed to the left of the decimal point and 2 digits to the right of the decimal point. Please do not use commas. |

## Property Details

### item_name

Provide a title for the item that may be customer facing

**Type:** array

**Examples:**

- `Adidas Blue Sneakers`

### brand

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `Reebok, Nike`

### externally_assigned_product_identifier

Provide the external ID (barcode) type and corresponding value that is being used to identify the product

**Type:** array

**Examples:**

- `714532191586`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `type`

### merchant_suggested_asin

Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID.

**Type:** array

**Examples:**

- `B007KQBXN0`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `value`

### supplier_declared_has_product_identifier_exemption

Please specify if the product is exempt from supplier declared external product identifiers.

**Type:** array

**Examples:**

- `Y, N`

### item_type_keyword

What is the item that you are selling?

**Type:** array

**Examples:**

- `Foam sleeping pads`

### package_level

Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy.

**Type:** array

**Examples:**

- `Unit, Case`

### package_contains_sku

Provide the SKU and quantity of the child items contained in the next package level.

**Type:** array

**Examples:**

- `SKU: ABC123, Quanitity: 1`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `sku`

### target_audience

Specify the target audience that the product is intended for

**Type:** array

### model_number

Provide the manufacturer 's model number for the item

**Type:** array

**Examples:**

- `RXZER23`

### model_name

Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size

**Type:** array

**Examples:**

- `Camedia`

### manufacturer

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `All-Star, Johnson & Johnson`

### skip_offer

Please indicate whether the offer should be skipped and a buyable offer should not be created. A value of "Yes", means no offer will be created.

**Type:** array

**Examples:**

- `Yes`

### fulfillment_availability

For those merchants using Amazon fulfillment services, please provide associated logistical information.

**Type:** array

**Conditionally Required**

**Conditionally Required based on selectors:** `fulfillment_channel_code`

### map_policy

Select one.

**Type:** array

**Examples:**

- `Policy 9`

### purchasable_offer

The attribute indicates the Purchasable Offer of the product

**Type:** array

**Examples:**

- `EUR`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `currency`, `audience`

### condition_type

Provide the actual condition type of the product

**Type:** array

**Examples:**

- `New`

### condition_note

Provide descriptive text explaining the actual condition of the item

**Type:** array

**Examples:**

- `Small dent in left side panel.`

### list_price

Provide the list price for the product. List Price is the suggested retail price of a product as provided by a manufacturer, supplier, or seller. This is not the offering or cost price.

**Type:** array

**Examples:**

- `64 USD, 69 GBP, 98 EUR`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `currency`

### product_tax_code

Enter the product tax code supplied to you by Amazon.com

**Type:** array

**Examples:**

- `A_GEN_NOTAX`

### merchant_release_date

A date in this format: yyyy-mm-dd.

**Type:** array

**Examples:**

- `2004-05-01`

### merchant_shipping_group

The ship configuration group for an offer. The ship configuration group is created and managed by the seller through the ship setting UI.

**Type:** array

### max_order_quantity

Max order quantity.

**Type:** array

### gift_options

Provide gift card options

**Type:** array

**Examples:**

- `Yes`

### main_offer_image_locator

Provide the location of the image

**Type:** array

**Examples:**

- `Feed`

### other_offer_image_locator_1

Provide the location of the image

**Type:** array

**Examples:**

- `Feed`

### other_offer_image_locator_2

Provide the location of the image

**Type:** array

**Examples:**

- `Feed`

### other_offer_image_locator_3

Provide the location of the image

**Type:** array

**Examples:**

- `Feed`

### other_offer_image_locator_4

Provide the location of the image

**Type:** array

**Examples:**

- `Feed`

### other_offer_image_locator_5

Provide the location and source of the image

**Type:** array

**Examples:**

- `Feed`

### import_designation

Provide the country of origin to assist in import classification and duties for the item.

**Type:** array

**Examples:**

- `Made in USA, Made in USA or Imported`

### supplemental_condition_information

Provide the additional condition information on the non-new product.

**Type:** array

**Examples:**

- `iPhone 14, Open Box Never Used, OEM, Original, Greater than 90%, With Tags, Pristine, Fully Functional`

### handmade_classification

Select the value that best describes how the product was produced

**Type:** array

**Examples:**

- `Hand-Altered`

### product_description

A text string; 2000 characters maximum in length. Note: Type 1 High ASCII characters (®, ©, ™, etc.) or other special characters are not supported.

**Type:** array

**Examples:**

- `Sturdy basketball hoop made for indoor or outdoor play.`

### bullet_point

An alphanumeric string; 500 characters maximum length per bullet point. Please do not include an actual bullet point object, just the text used to describe your product.  Note: Type 1 High ASCII characters (®, ©, ™, etc.) or other special characters are not supported.

**Type:** array

**Examples:**

- `Ideal for building and toning bicep muscles`

### generic_keyword

A text string; 50 characters maximum in length.

This is in addition to the valid values that you must submit for your product.

**Type:** array

**Examples:**

- `gun lock, kids sleeping bags`

### special_feature

Use the column SpecialFeatures in the Valid Values list. An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `150`

### style

The style of the item

**Type:** array

**Examples:**

- `Mission; Art Deco; Jack Purcell`

### material

Use the column MaterialType in the Valid Values list. An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `aluminum`

### number_of_items

A positive whole number.

**Type:** array

**Examples:**

- `3`

### item_package_quantity

A positive integer

**Type:** array

**Examples:**

- `5`

### wheel

Provide wheel information

**Type:** array

**Examples:**

- `In-Line Skate`

### water_resistance_level

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `Yes/No`

### color

Provide the color of the product

**Type:** array

**Examples:**

- `Cranberry`

### size

Please refer to the Sporting Goods Style Guide . An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `Small, Large, X-Large`

### part_number

An alphanumeric string; 40 characters maximum.

**Type:** array

**Examples:**

- `1-203988AAA, 5LLL`

### item_shape

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `Round, concave, flat`

### shaft

The attribute indicates Shaft of the product

**Type:** array

**Examples:**

- `Knee High`

### edition

Provide the version or edition of the item

**Type:** array

**Examples:**

- `Teacher's Edition, Unabridged Version`

### lens

The attribute indicates Lens of the product

**Type:** array

**Examples:**

- `Chemical Resistant Coating`

### item_display_dimensions

Provide the dimensions of the product, without packaging and fully assembled

**Type:** array

**Examples:**

- `5.7 Inches x 3.5 Inches x 1.8 Inches`

### voltage

Provide the item's voltage

**Type:** array

**Examples:**

- `28 Volts`

### tension_level

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `55 lbs`

### volume_capacity_name

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `175/12`

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Examples:**

- `Floral, Geometric, Polka Dot`

### unit_count

Specify the number of units and the unit type of the product

**Type:** array

**Examples:**

- `72.0 Ounces`

### product_site_launch_date

A date in this format: yyyy-mm-dd.

**Type:** array

**Examples:**

- `2003-08-11`

### golf_club_flex

Flex type for golf clubs

**Type:** array

**Examples:**

- `Regular, Stiff, Senior, X-Stiff`

### included_components

A text string; 1,000 characters maximum in length.

**Type:** array

**Examples:**

- `Instructions, team sports accessory components, batteries, cover`

### golf_club_loft

Golf club loft

**Type:** array

**Examples:**

- `8.5 Degrees, 9.5 Degrees`

### league_name

Name of league associated with this event.

**Type:** array

**Examples:**

- `NBA`

### team_name

Provide the name of the sports team associated with the sleeping mat, indicating the product's affiliation or branding.

**Type:** array

**Examples:**

- `Seattle Seahawks, Wisconsin Badgers`

### scent

Provide a description of the scent of the item

**Type:** array

**Examples:**

- `Lavender`

### hand_orientation

Is this item built for lefties or righties?

**Type:** array

**Examples:**

- `left, right`

### display_maximum_weight_recommendation

The attribute indicates the Display Maximum Weight Recommendation of the product

**Type:** array

### grip

The attribute indicates Grip of the product

**Type:** array

**Examples:**

- `Rubber`

### head

The attribute indicates Head of the product

**Type:** array

**Examples:**

- `Horse Hair`

### insulation

The attribute indicates Insulation of the product

**Type:** array

**Examples:**

- `Down`

### seating_group

**Type:** array

### variety

Describes what variety of item this is.

**Type:** array

**Examples:**

- `Indian Head`

### item_length_width_thickness

The length, width and thickness of the item in ready to use condition.

**Type:** array

**Examples:**

- `40 Inches`

### parentage_level

Specify whether a SKU is a parent or child

**Type:** array

**Examples:**

- `Parent`

### child_parent_sku_relationship

The attribute indicates the Child Parent Sku Relationship of the product

**Type:** array

**Examples:**

- `Accessory`

### variation_theme

Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping.

**Type:** array

**Examples:**

- `Size/Color`

### country_of_origin

Use the column CountryOfOrigin in the Valid Values list. An alphanumeric string; 2 characters maximum.

**Type:** array

**Examples:**

- `US, FR`

### warranty_description

An alphanumeric string; 50 characters maximum.

**Type:** array

**Examples:**

- `1 Year, 3 Years, 5 Years, etc.`

### batteries_required

Select: true or false

**Type:** array

**Examples:**

- `No`

### batteries_included

Select: true or false

**Type:** array

**Examples:**

- `Yes`

### battery

Provide battery information

**Type:** array

**Examples:**

- `Alkaline`

### num_batteries

Provide the quantity and type of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided

**Type:** array

**Examples:**

- `1 AA, 2 AAA`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `type`

### number_of_lithium_metal_cells

A positive whole number.

**Type:** array

**Examples:**

- `1, 2, 3`

### number_of_lithium_ion_cells

A positive whole number.

**Type:** array

**Examples:**

- `1, 2, 3`

### lithium_battery

The attribute indicates the Lithium Battery of the product

**Type:** array

**Examples:**

- `Milligrams`

### supplier_declared_dg_hz_regulation

Provide the regulations that apply to the item if it is classified as a dangerous good, hazardous material, substance, or waste.

**Type:** array

**Examples:**

- `GHS, Storage, Transportation`

### ghs

Provide the Global Harmonized System (GHS) information

**Type:** array

**Examples:**

- `NGK`

### hazmat

Provide hazmat information that is relevant to the product based on the aspect selected

**Type:** array

**Examples:**

- `UN1993`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `aspect`

### safety_data_sheet_url

Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances.

**Type:** array

**Examples:**

- `www.safetysheetsRus.com/hazardous_substance/msds.pdf`

### item_weight

A number with up to 10 digits allowed to the left of the decimal point and 2 digits to the right of the decimal point. Please do not use commas.

**Type:** array

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

### california_proposition_65

Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required

**Type:** array

**Examples:**

- `Furniture; Lead`

### regulatory_compliance_certification

Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers.

**Type:** array

**Examples:**

- `FDA 510(k) Number,
F2345G234`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `regulation_type`

### dsa_responsible_party_address

Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations.

**Type:** array

**Examples:**

- `rsp-email@example.com`

### compliance_media

Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager.

**Type:** array

**Examples:**

- `Installation Manual`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `content_type`, `content_language`

### gpsr_safety_attestation

Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it.

**Type:** array

**Examples:**

- `Yes`

### gpsr_manufacturer_reference

Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL.

**Type:** array

**Examples:**

- `abc@example.com`

### ships_globally

Provide whether the item can be shipped globally by Amazon 

**Type:** array

**Examples:**

- `Yes`

### ghs_chemical_h_code

Provide the GHS chemical hazard codes for the chemical substance/mixture in order to display warnings to customers.

**Type:** array

**Examples:**

- `H200`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `value`

### main_product_image_locator

The attribute indicates the Main Product Image Locator of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_1

The attribute indicates the Other Product Image Locator 1 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_2

The attribute indicates the Other Product Image Locator 2 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_3

The attribute indicates the Other Product Image Locator 3 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_4

The attribute indicates the Other Product Image Locator 4 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_5

The attribute indicates the Other Product Image Locator 5 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_6

The attribute indicates the Other Product Image Locator 6 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_7

The attribute indicates the Other Product Image Locator 7 of the product

**Type:** array

**Examples:**

- `Feed`

### other_product_image_locator_8

The attribute indicates the Other Product Image Locator 8 of the product

**Type:** array

**Examples:**

- `Feed`

### swatch_product_image_locator

The attribute indicates the Swatch Product Image Locator of the product

**Type:** array

**Examples:**

- `Feed`

### item_package_dimensions

Provide the item's package dimensions

**Type:** array

**Examples:**

- `10 x 2 x 2.7 inches`

### item_package_weight

A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point.

**Type:** array

**Examples:**

- `10`

### item_display_weight

A number with up to 10 digits allowed to the left of the decimal point and 2 digits to the right of the decimal point. Please do not use commas.

**Type:** array

**Examples:**

- `25 Lbs`

