# DECORATIVE_SIGNAGE Schema Documentation

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
- `compliance_media` - Required when selectors `marketplace_id`, `content_type`, `content_language` are specified
- `externally_assigned_product_identifier.type` - Required when `externally_assigned_product_identifier` is provided
- `externally_assigned_product_identifier.value` - Required when `externally_assigned_product_identifier` is provided
- `merchant_suggested_asin.value` - Required when `merchant_suggested_asin` is provided
- `supplier_declared_has_product_identifier_exemption.value` - Required when `supplier_declared_has_product_identifier_exemption` is provided
- `package_level.value` - Required when `package_level` is provided
- `package_contains_sku.quantity` - Required when `package_contains_sku` is provided
- `package_contains_sku.sku` - Required when `package_contains_sku` is provided
- `model_number.value` - Required when `model_number` is provided
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
- `handmade_classification.value` - Required when `handmade_classification` is provided
- `generic_keyword.value` - Required when `generic_keyword` is provided
- `generic_keyword.language_tag` - Required when `generic_keyword` is provided
- `style.value` - Required when `style` is provided
- `style.language_tag` - Required when `style` is provided
- `material.value` - Required when `material` is provided
- `material.language_tag` - Required when `material` is provided
- `number_of_items.value` - Required when `number_of_items` is provided
- `item_package_quantity.value` - Required when `item_package_quantity` is provided
- `special_size_type.value` - Required when `special_size_type` is provided
- `special_size_type.language_tag` - Required when `special_size_type` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `item_diameter.unit` - Required when `item_diameter` is provided
- `metal_type.value` - Required when `metal_type` is provided
- `metal_type.language_tag` - Required when `metal_type` is provided
- `part_number.value` - Required when `part_number` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `occasion.value` - Required when `occasion` is provided
- `occasion.language_tag` - Required when `occasion` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `wattage.value` - Required when `wattage` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `mounting_type.value` - Required when `mounting_type` is provided
- `mounting_type.language_tag` - Required when `mounting_type` is provided
- `item_form.value` - Required when `item_form` is provided
- `item_form.language_tag` - Required when `item_form` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `athlete.value` - Required when `athlete` is provided
- `athlete.language_tag` - Required when `athlete` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `length_range.value` - Required when `length_range` is provided
- `length_range.language_tag` - Required when `length_range` is provided
- `optical_power.value` - Required when `optical_power` is provided
- `item_length_width.length` - Required when `item_length_width` is provided
- `item_length_width.width` - Required when `item_length_width` is provided
- `master_pack_dimensions.height` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.length` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.width` - Required when `master_pack_dimensions` is provided
- `master_pack_weight.value` - Required when `master_pack_weight` is provided
- `master_pack_weight.unit` - Required when `master_pack_weight` is provided
- `parentage_level.value` - Required when `parentage_level` is provided
- `child_parent_sku_relationship.child_relationship_type` - Required when `child_parent_sku_relationship` is provided
- `variation_theme.name` - Required when `variation_theme` is provided
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
- `fcc_radio_frequency_emission_compliance.registration_status` - Required when `fcc_radio_frequency_emission_compliance` is provided
- `dsa_responsible_party_address.value` - Required when `dsa_responsible_party_address` is provided
- `compliance_media.content_type` - Required when `compliance_media` is provided
- `compliance_media.content_language` - Required when `compliance_media` is provided
- `compliance_media.source_location` - Required when `compliance_media` is provided
- `gpsr_safety_attestation.value` - Required when `gpsr_safety_attestation` is provided
- `has_multiple_battery_powered_components.value` - Required when `has_multiple_battery_powered_components` is provided
- `ships_globally.value` - Required when `ships_globally` is provided
- `contains_battery_or_cell.value` - Required when `contains_battery_or_cell` is provided
- `battery_contains_free_unabsorbed_liquid.value` - Required when `battery_contains_free_unabsorbed_liquid` is provided
- `is_battery_non_spillable.value` - Required when `is_battery_non_spillable` is provided
- `non_lithium_battery_packaging.value` - Required when `non_lithium_battery_packaging` is provided
- `has_replaceable_battery.value` - Required when `has_replaceable_battery` is provided
- `non_lithium_battery_energy_content.value` - Required when `non_lithium_battery_energy_content` is provided
- `non_lithium_battery_energy_content.unit` - Required when `non_lithium_battery_energy_content` is provided
- `has_less_than_30_percent_state_of_charge.value` - Required when `has_less_than_30_percent_state_of_charge` is provided
- `battery_installation_device_type.value` - Required when `battery_installation_device_type` is provided
- `is_oem_sourced_product.value` - Required when `is_oem_sourced_product` is provided
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
| `brand` | array | Provide the brand name of the product |
| `externally_assigned_product_identifier` | array | Provide the external ID (barcode) type and corresponding value that is being used to identify the product |
| `merchant_suggested_asin` | array | Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID. |
| `supplier_declared_has_product_identifier_exemption` | array | Please specify if the product is exempt from supplier declared external product identifiers. |
| `item_type_keyword` | array | Item type keywords are used to place new ASINs in the appropriate place(s) within the graph. Select the most specific accurate term for optimal placement. |
| `package_level` | array | Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy. |
| `package_contains_sku` | array | Provide the SKU and quantity of the child items contained in the next package level. |
| `model_number` | array | Provide the manufacturer 's model number for the item |
| `manufacturer` | array | Provide the company that manufactures the product. |
| `skip_offer` | array | Please indicate whether the offer should be skipped and a buyable offer should not be created. A value of "Yes", means no offer will be created. |
| `fulfillment_availability` | array | For those merchants using Amazon fulfillment services, please provide associated logistical information. |
| `map_policy` | array | Select one. |
| `purchasable_offer` | array | The attribute indicates the Purchasable Offer of the product |
| `condition_type` | array | Provide the actual condition type of the product |
| `condition_note` | array | Provide descriptive text explaining the actual condition of the item |
| `list_price` | array | Provide the list price for the product. List Price is the suggested retail price of a product as provided by a manufacturer, supplier, or seller. This is not the offering or cost price. |
| `product_tax_code` | array | Enter the product tax code supplied to you by Amazon.com |
| `merchant_release_date` | array | Provide the merchant release date using YYYY-MM-DD format |
| `merchant_shipping_group` | array | The ship configuration group for an offer. The ship configuration group is created and managed by the seller through the ship setting UI. |
| `max_order_quantity` | array | Max order quantity. |
| `gift_options` | array | Provide gift card options |
| `main_offer_image_locator` | array | Provide the location of the image |
| `other_offer_image_locator_1` | array | Provide the location of the image |
| `other_offer_image_locator_2` | array | Provide the location of the image |
| `other_offer_image_locator_3` | array | Provide the location of the image |
| `other_offer_image_locator_4` | array | Provide the location of the image |
| `other_offer_image_locator_5` | array | Provide the location and source of the image |
| `handmade_classification` | array | Select the value that best describes how the product was produced |
| `product_description` | array | Provide a text description of the product. This information will appear in paragraph form on the detail page of your product. Include unique product features, product line details, and product specifications. Do not use all caps. |
| `bullet_point` | array | Provide only information that describes the features of the product in general and not information that is specific to your particular offer (for example: do not provide item condition, shipping or promotional information) |
| `generic_keyword` | array | Provide any terms that may be relevant to customer searches. No repetition, no competitor brand names or ASINs. |
| `style` | array | Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product |
| `material` | array | Specify the primary material used for manufacturing the item |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Provide the number of packages sold as part of a single item. An ASIN selling 5 boxes of paperclips with 100 paperclips per box would have item package quantity = '5' |
| `special_size_type` | array | Specify the special size type for the item |
| `color` | array | Provide the color of the product |
| `size` | array | Provide the size of the item |
| `item_diameter` | array | Provide the diameter of the item |
| `metal_type` | array | Provide the type of metal on the item. |
| `part_number` | array | Provide the part number. For many products, this will be identical to the model number however some manufacturers distinguish part number from model number |
| `item_shape` | array | Specify the shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `ring` | array | The attribute indicates Ring of the product |
| `edition` | array | Provide the version or edition of the item |
| `lens` | array | The attribute indicates Lens of the product |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `occasion` | array | Indicate the occasion of use for the product |
| `flavor` | array | What flavor is the product? |
| `wattage` | array | Provide the item's wattage rating |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `mounting_type` | array | Provide the way the item is designed to be attached or supported, how it can be displayed or installed. |
| `item_form` | array | Provide a value that represents the form of the item |
| `unit_count` | array | Provide the total number of units the item contains, indicating the quantity and type of units included. |
| `included_components` | array | Specify the items that are included with this product |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Please enter the team name of this product |
| `athlete` | array | Name of athlete participating in the event |
| `scent` | array | Provide a description of the scent of the item |
| `base` | array | Enter the specifications for the base |
| `cup` | array | The attribute indicates Cup of the product |
| `ink` | array | The attribute indicates Ink of the product |
| `length_range` | array | Length range for blinds |
| `optical_power` | array | Provide the item's optical power |
| `item_length_width` | array | Provide the length and width of the item when fully set up for use, like a rolled out rug or blanket. |
| `master_pack_dimensions` | array | Provide the width, height and depth measurements of the master pack. |
| `master_pack_weight` | array | Provide the weight measurement of the master pack item. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `country_of_origin` | array | Select the product's country of origin |
| `batteries_required` | array | Select "yes" if batteries are required to power the item (or if the item is a battery) or no if they are not. Please note that an internal rechargeable battery is also considered a battery |
| `batteries_included` | array | Select "yes" if batteries are contained in the product (e.g. batteries inside a pair of Bluetooth headphones) and/or included with the product (e.g. batteries packed separately with a camera), otherwise select "no" |
| `battery` | array | Provide battery information |
| `num_batteries` | array | Provide the quantity and type of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided |
| `number_of_lithium_metal_cells` | array | Specify the total number of Lithium Metal cells in the product where the cell isn't contained in an encased battery (e.g. coin cells) |
| `number_of_lithium_ion_cells` | array | Specify the total number of Lithium-ion cells in the product where the cell isn't contained in an encased battery. For example, an AA battery is considered a cell |
| `lithium_battery` | array | The attribute indicates the Lithium Battery of the product |
| `supplier_declared_dg_hz_regulation` | array | If the product is a Dangerous Good or Hazardous Material, Substance or Waste that is regulated for transportation, storage, and/or waste select from the list of valid values |
| `ghs` | array | Provide the Global Harmonized System (GHS) information |
| `hazmat` | array | Provide hazmat information that is relevant to the product based on the aspect selected |
| `safety_data_sheet_url` | array | Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances. |
| `item_weight` | array | Provide the weight of the item (not including the packaging) |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `fcc_radio_frequency_emission_compliance` | array | Provide details on compliance to FCC regulations for products that may emit radio frequencies. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person to comply with the General Product Safety Regulation (GPSR). If you’ve already submitted this Responsible Person’s information in the past, make sure you use the same email or URL. |
| `compliance_media` | array | Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager. |
| `gpsr_safety_attestation` | array | Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it. |
| `gpsr_manufacturer_reference` | array | Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL. |
| `has_multiple_battery_powered_components` | array | Provide whether the item consits of more than one battery powered components. |
| `ships_globally` | array | Provide whether the item can be shipped globally by Amazon  |
| `contains_battery_or_cell` | array | Provide whether the item uses cells with a single electrochemical unit or batteries with multiple connected cells within a casing. |
| `battery_contains_free_unabsorbed_liquid` | array | Provides certification that your battery meets transport regulations for free-flowing liquid: no unabsorbed liquid at 55°C & no leakage. |
| `is_battery_non_spillable` | array | Provides certification confirming your battery meets transport regulations for non-spillable status, including vibration and pressure tests |
| `non_lithium_battery_packaging` | array | Provide "in equipment" for batteries installed in devices, "with equipment" for those packed separately with the device, and "only" for standalone batteries. |
| `has_replaceable_battery` | array | Provide whether the item's battery is replaceable. |
| `non_lithium_battery_energy_content` | array | Provide the item's energy content for non-lithium batteries. The attribute refers to the total amount of energy that a battery can store. |
| `has_less_than_30_percent_state_of_charge` | array | Provide whether the item's battery contains less than 30 percent charge during shipping. |
| `battery_installation_device_type` | array | Provide the item's battery installation type. Specifying whether a battery is installed in a vehicle, vessel, or not installed in any device. |
| `is_oem_sourced_product` | array | Provide whether the item is directly sourced from the original equipment manufacturer (OEM). |
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
| `item_package_weight` | array | Provide the weight of the item plus the packaging |
| `item_display_weight` | array | Provide the item weight if the product is a solid |

## Property Details

### item_name

Provide a title for the item that may be customer facing

**Type:** array

**Examples:**

- `Adidas Blue Sneakers`

### brand

Provide the brand name of the product

**Type:** array

**Examples:**

- `Sony`

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

Item type keywords are used to place new ASINs in the appropriate place(s) within the graph. Select the most specific accurate term for optimal placement.

**Type:** array

**Examples:**

- `Lighted and neon signs`

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

### model_number

Provide the manufacturer 's model number for the item

**Type:** array

**Examples:**

- `RXZER23`

### manufacturer

Provide the company that manufactures the product.

**Type:** array

**Examples:**

- `Nike, Procter & Gamble`

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

Provide the merchant release date using YYYY-MM-DD format

**Type:** array

**Examples:**

- `2017-07-20`

### merchant_shipping_group

The ship configuration group for an offer. The ship configuration group is created and managed by the seller through the ship setting UI.

**Type:** array

### max_order_quantity

Max order quantity.

**Type:** array

**Examples:**

- `3`

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

### handmade_classification

Select the value that best describes how the product was produced

**Type:** array

**Examples:**

- `Hand-Altered`

### product_description

Provide a text description of the product. This information will appear in paragraph form on the detail page of your product. Include unique product features, product line details, and product specifications. Do not use all caps.

**Type:** array

**Examples:**

- `This summer, boots by Jette made from high quality suede leather are real gems. They visually highlight the craftsmanship and fine leather braid positioned at the top of the shaft`

### bullet_point

Provide only information that describes the features of the product in general and not information that is specific to your particular offer (for example: do not provide item condition, shipping or promotional information)

**Type:** array

**Examples:**

- `Delicious honey-apricot glaze`

### generic_keyword

Provide any terms that may be relevant to customer searches. No repetition, no competitor brand names or ASINs.

**Type:** array

**Examples:**

- `Water sport shoes; Derek Rose; Electric; Wi-Fi; Banana`

### style

Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product

**Type:** array

**Examples:**

- `Art Deco`

### material

Specify the primary material used for manufacturing the item

**Type:** array

**Examples:**

- `Plastic`

### number_of_items

Provide the total number of identical items in the selling unit to the customer

**Type:** array

**Examples:**

- `5`

### item_package_quantity

Provide the number of packages sold as part of a single item. An ASIN selling 5 boxes of paperclips with 100 paperclips per box would have item package quantity = '5'

**Type:** array

**Examples:**

- `1`

### special_size_type

Specify the special size type for the item

**Type:** array

**Examples:**

- `Husky, Petite`

### color

Provide the color of the product

**Type:** array

**Examples:**

- `Cranberry`

### size

Provide the size of the item

**Type:** array

**Examples:**

- `Extra Large`

### item_diameter

Provide the diameter of the item

**Type:** array

**Examples:**

- `5 inches`

### metal_type

Provide the type of metal on the item.

**Type:** array

**Examples:**

- `Bronze`

### part_number

Provide the part number. For many products, this will be identical to the model number however some manufacturers distinguish part number from model number

**Type:** array

**Examples:**

- `RIV001`

### item_shape

Specify the shape of the item

**Type:** array

**Examples:**

- `Round`

### theme

Provide the primary high-level subject, concept, topic, motif, or idea of an item.

**Type:** array

**Examples:**

- `Sports`

### ring

The attribute indicates Ring of the product

**Type:** array

**Examples:**

- `One Size`

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

### occasion

Indicate the occasion of use for the product

**Type:** array

**Examples:**

- `Halloween`

### flavor

What flavor is the product?

**Type:** array

**Examples:**

- `Double Rich Chocolate, Cherry, Chocolate, Vanilla`

### wattage

Provide the item's wattage rating

**Type:** array

**Examples:**

- `50 Watts`

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Examples:**

- `Floral, Geometric, Polka Dot`

### mounting_type

Provide the way the item is designed to be attached or supported, how it can be displayed or installed.

**Type:** array

**Examples:**

- `Clevis`

### item_form

Provide a value that represents the form of the item

**Type:** array

**Examples:**

- `Sticks`

### unit_count

Provide the total number of units the item contains, indicating the quantity and type of units included.

**Type:** array

**Examples:**

- `72.0 Ounces`

### included_components

Specify the items that are included with this product

**Type:** array

**Examples:**

- `Camera Body`

### league_name

Name of league associated with this event

**Type:** array

**Examples:**

- `NBA`

### team_name

Please enter the team name of this product

**Type:** array

**Examples:**

- `Seattle Seahawks`

### athlete

Name of athlete participating in the event

**Type:** array

**Examples:**

- `Michael Jordan`

### scent

Provide a description of the scent of the item

**Type:** array

**Examples:**

- `Lavender`

### base

Enter the specifications for the base

**Type:** array

**Examples:**

- `Stainless Steel`

### cup

The attribute indicates Cup of the product

**Type:** array

**Examples:**

- `B`

### ink

The attribute indicates Ink of the product

**Type:** array

**Examples:**

- `Multicolor`

### length_range

Length range for blinds

**Type:** array

**Examples:**

- `24-60" long`

### optical_power

Provide the item's optical power

**Type:** array

**Examples:**

- `5 Milliwatts`

### item_length_width

Provide the length and width of the item when fully set up for use, like a rolled out rug or blanket.

**Type:** array

**Examples:**

- `40 Inches`

### master_pack_dimensions

Provide the width, height and depth measurements of the master pack.

**Type:** array

**Examples:**

- `32.4 inches`

### master_pack_weight

Provide the weight measurement of the master pack item.

**Type:** array

**Examples:**

- `25.3 Pounds`

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

Select the product's country of origin

**Type:** array

**Examples:**

- `China`

### batteries_required

Select "yes" if batteries are required to power the item (or if the item is a battery) or no if they are not. Please note that an internal rechargeable battery is also considered a battery

**Type:** array

**Examples:**

- `Yes`

### batteries_included

Select "yes" if batteries are contained in the product (e.g. batteries inside a pair of Bluetooth headphones) and/or included with the product (e.g. batteries packed separately with a camera), otherwise select "no"

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

Specify the total number of Lithium Metal cells in the product where the cell isn't contained in an encased battery (e.g. coin cells)

**Type:** array

**Examples:**

- `7`

### number_of_lithium_ion_cells

Specify the total number of Lithium-ion cells in the product where the cell isn't contained in an encased battery. For example, an AA battery is considered a cell

**Type:** array

**Examples:**

- `7`

### lithium_battery

The attribute indicates the Lithium Battery of the product

**Type:** array

**Examples:**

- `Milligrams`

### supplier_declared_dg_hz_regulation

If the product is a Dangerous Good or Hazardous Material, Substance or Waste that is regulated for transportation, storage, and/or waste select from the list of valid values

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

Provide the weight of the item (not including the packaging)

**Type:** array

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

### california_proposition_65

Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required

**Type:** array

**Examples:**

- `Furniture; Lead`

### fcc_radio_frequency_emission_compliance

Provide details on compliance to FCC regulations for products that may emit radio frequencies.

**Type:** array

### dsa_responsible_party_address

Provide the email address or URL for the EU Responsible Person to comply with the General Product Safety Regulation (GPSR). If you’ve already submitted this Responsible Person’s information in the past, make sure you use the same email or URL.

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

### has_multiple_battery_powered_components

Provide whether the item consits of more than one battery powered components.

**Type:** array

**Examples:**

- `Yes`

### ships_globally

Provide whether the item can be shipped globally by Amazon 

**Type:** array

**Examples:**

- `Yes`

### contains_battery_or_cell

Provide whether the item uses cells with a single electrochemical unit or batteries with multiple connected cells within a casing.

**Type:** array

**Examples:**

- `Battery`

### battery_contains_free_unabsorbed_liquid

Provides certification that your battery meets transport regulations for free-flowing liquid: no unabsorbed liquid at 55°C & no leakage.

**Type:** array

**Examples:**

- `Yes`

### is_battery_non_spillable

Provides certification confirming your battery meets transport regulations for non-spillable status, including vibration and pressure tests

**Type:** array

**Examples:**

- `Yes`

### non_lithium_battery_packaging

Provide "in equipment" for batteries installed in devices, "with equipment" for those packed separately with the device, and "only" for standalone batteries.

**Type:** array

**Examples:**

- `Batteries Only`

### has_replaceable_battery

Provide whether the item's battery is replaceable.

**Type:** array

**Examples:**

- `Yes`

### non_lithium_battery_energy_content

Provide the item's energy content for non-lithium batteries. The attribute refers to the total amount of energy that a battery can store.

**Type:** array

**Examples:**

- `2.6 Watts`

### has_less_than_30_percent_state_of_charge

Provide whether the item's battery contains less than 30 percent charge during shipping.

**Type:** array

**Examples:**

- `Yes`

### battery_installation_device_type

Provide the item's battery installation type. Specifying whether a battery is installed in a vehicle, vessel, or not installed in any device.

**Type:** array

**Examples:**

- `Installed In Vessel`

### is_oem_sourced_product

Provide whether the item is directly sourced from the original equipment manufacturer (OEM).

**Type:** array

**Examples:**

- `Yes`

### ghs_chemical_h_code

Provide the GHS chemical hazard codes for the chemical substance/mixture in order to display warnings to customers.

**Type:** array

**Examples:**

- `H200`

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

Provide the weight of the item plus the packaging

**Type:** array

**Examples:**

- `0.65 Pounds`

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

**Examples:**

- `20.0 Pounds, 50.0 Kilograms`

