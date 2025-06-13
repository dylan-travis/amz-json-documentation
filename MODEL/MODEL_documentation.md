# MODEL Schema Documentation

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
- `pesticide_marking` - Required when selectors `marketplace_id`, `marking_type` are specified
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
- `target_audience_keyword.value` - Required when `target_audience_keyword` is provided
- `target_audience_keyword.language_tag` - Required when `target_audience_keyword` is provided
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
- `handmade_classification.value` - Required when `handmade_classification` is provided
- `generic_keyword.value` - Required when `generic_keyword` is provided
- `generic_keyword.language_tag` - Required when `generic_keyword` is provided
- `style.value` - Required when `style` is provided
- `style.language_tag` - Required when `style` is provided
- `target_gender.value` - Required when `target_gender` is provided
- `age_range_description.value` - Required when `age_range_description` is provided
- `age_range_description.language_tag` - Required when `age_range_description` is provided
- `material.value` - Required when `material` is provided
- `material.language_tag` - Required when `material` is provided
- `number_of_items.value` - Required when `number_of_items` is provided
- `item_package_quantity.value` - Required when `item_package_quantity` is provided
- `subject_character.value` - Required when `subject_character` is provided
- `subject_character.language_tag` - Required when `subject_character` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `part_number.value` - Required when `part_number` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `sub_brand.value` - Required when `sub_brand` is provided
- `sub_brand.language_tag` - Required when `sub_brand` is provided
- `number_of_players.value` - Required when `number_of_players` is provided
- `number_of_players.language_tag` - Required when `number_of_players` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `power_source_type.value` - Required when `power_source_type` is provided
- `power_source_type.language_tag` - Required when `power_source_type` is provided
- `is_assembly_required.value` - Required when `is_assembly_required` is provided
- `assembly_time.value` - Required when `assembly_time` is provided
- `operation_mode.value` - Required when `operation_mode` is provided
- `operation_mode.language_tag` - Required when `operation_mode` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `manufacturer_minimum_age.value` - Required when `manufacturer_minimum_age` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `educational_objective.value` - Required when `educational_objective` is provided
- `educational_objective.language_tag` - Required when `educational_objective` is provided
- `indoor_outdoor_usage.value` - Required when `indoor_outdoor_usage` is provided
- `publisher.value` - Required when `publisher` is provided
- `publisher.language_tag` - Required when `publisher` is provided
- `master_pack_dimensions.height` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.length` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.width` - Required when `master_pack_dimensions` is provided
- `master_pack_weight.value` - Required when `master_pack_weight` is provided
- `master_pack_weight.unit` - Required when `master_pack_weight` is provided
- `parentage_level.value` - Required when `parentage_level` is provided
- `child_parent_sku_relationship.child_relationship_type` - Required when `child_parent_sku_relationship` is provided
- `variation_theme.name` - Required when `variation_theme` is provided
- `safety_warning.value` - Required when `safety_warning` is provided
- `safety_warning.language_tag` - Required when `safety_warning` is provided
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
- `cpsia_cautionary_statement.value` - Required when `cpsia_cautionary_statement` is provided
- `pesticide_marking.marking_type` - Required when `pesticide_marking` is provided
- `fcc_radio_frequency_emission_compliance.registration_status` - Required when `fcc_radio_frequency_emission_compliance` is provided
- `regulatory_compliance_certification.regulation_type` - Required when `regulatory_compliance_certification` is provided
- `regulatory_compliance_certification.value` - Required when `regulatory_compliance_certification` is provided
- `dsa_responsible_party_address.value` - Required when `dsa_responsible_party_address` is provided
- `compliance_media.content_type` - Required when `compliance_media` is provided
- `compliance_media.content_language` - Required when `compliance_media` is provided
- `compliance_media.source_location` - Required when `compliance_media` is provided
- `gpsr_safety_attestation.value` - Required when `gpsr_safety_attestation` is provided
- `contains_pfas.value` - Required when `contains_pfas` is provided
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
- `item_dimensions.length` - Required when `item_dimensions` is provided
- `item_dimensions.width` - Required when `item_dimensions` is provided
- `item_dimensions.height` - Required when `item_dimensions` is provided
- `item_package_dimensions.length` - Required when `item_package_dimensions` is provided
- `item_package_dimensions.width` - Required when `item_package_dimensions` is provided
- `item_package_dimensions.height` - Required when `item_package_dimensions` is provided
- `item_package_weight.value` - Required when `item_package_weight` is provided
- `item_package_weight.unit` - Required when `item_package_weight` is provided
- `number_of_boxes.value` - Required when `number_of_boxes` is provided

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `item_name` | array | Provide a title for the item that may be customer facing |
| `brand` | array | Max. 50 characters |
| `externally_assigned_product_identifier` | array | Provide the external ID (barcode) type and corresponding value that is being used to identify the product |
| `merchant_suggested_asin` | array | Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID. |
| `supplier_declared_has_product_identifier_exemption` | array | Please specify if the product is exempt from supplier declared external product identifiers. |
| `item_type_keyword` | array | What is the item that you are selling? |
| `package_level` | array | Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy. |
| `package_contains_sku` | array | Provide the SKU and quantity of the child items contained in the next package level. |
| `target_audience_keyword` | array | For whom is the product intended? |
| `model_name` | array | Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size |
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
| `supplemental_condition_information` | array | Provide the additional condition information on the non-new product. |
| `handmade_classification` | array | Select the value that best describes how the product was produced |
| `product_description` | array | The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum. |
| `bullet_point` | array | Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description. |
| `generic_keyword` | array | Provide specific search terms to help customers find your product. |
| `style` | array | Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product |
| `target_gender` | array | Provide the target gender for the product |
| `age_range_description` | array | Provide the age range the item is designed for, indicating the appropriate ages for safe and engaging play. |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `subject_character` | array | Provide the main character represented by the toy or game, indicating the primary figure or personality associated with the item. |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `sub_brand` | array | Provide the secondary brand or franchise the item is associated with, such as licensed characters or themes. |
| `number_of_players` | array | Specify the maximum number of players for the game. |
| `edition` | array | Product's version or edition |
| `power_source_type` | array | Provide the type of power source the item uses, such as batteries or electricity, to operate and function. |
| `is_assembly_required` | array | Select: true or false |
| `assembly_time` | array | A positive whole number. |
| `operation_mode` | array | Provide the way the item functions, indicating whether it operates manually or automatically for play purposes. |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `manufacturer_minimum_age` | array | Provide the recommended minimum age for the product in months |
| `included_components` | array | Specify the items that are included with this product |
| `educational_objective` | array | Provide the learning goal or skill the item aims to develop, such as problem-solving or hand-eye coordination. |
| `indoor_outdoor_usage` | array | Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor. |
| `publisher` | array | Provide the publisher for the product |
| `master_pack_dimensions` | array | Provide the width, height and depth measurements of the master pack. |
| `master_pack_weight` | array | Provide the weight measurement of the master pack item. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `safety_warning` | array | List safety information customers should know. |
| `country_of_origin` | array | The country in which the product was published. |
| `batteries_required` | array | Indicate if batteries are required. |
| `batteries_included` | array | Indicate if batteries are included with the product. |
| `battery` | array | Provide battery information |
| `num_batteries` | array | Provide the quantity and type of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided |
| `number_of_lithium_metal_cells` | array | Total number of Lithium cells (of type "Metal") in the product, where the cell isn't contained in an encased battery. |
| `number_of_lithium_ion_cells` | array | Total number of Lithium cells (of type "Ion") in the product, where the cell isn't contained in an encased battery. |
| `lithium_battery` | array | The attribute indicates the Lithium Battery of the product |
| `supplier_declared_dg_hz_regulation` | array | Provide the regulations that apply to the item if it is classified as a dangerous good, hazardous material, substance, or waste. |
| `ghs` | array | Provide the Global Harmonized System (GHS) information |
| `hazmat` | array | Provide hazmat information that is relevant to the product based on the aspect selected |
| `safety_data_sheet_url` | array | Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances. |
| `item_weight` | array | Provide the weight of the item (not including the packaging) |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `cpsia_cautionary_statement` | array | You must select any applicable warning for choking hazards of children’s toys and games, or "no_warning_applicable". To verify warnings, contact the manufacturer or check the packaging. |
| `pesticide_marking` | array | Provide any pesticide marking on the item or packaging. |
| `fcc_radio_frequency_emission_compliance` | array | Provide details on compliance to FCC regulations for products that may emit radio frequencies. |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations. |
| `compliance_media` | array | Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager. |
| `gpsr_safety_attestation` | array | Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it. |
| `gpsr_manufacturer_reference` | array | Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL. |
| `contains_pfas` | array | Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals. |
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
| `item_dimensions` | array | Provide the item's dimensions |
| `item_package_dimensions` | array | Provide the item's package dimensions |
| `item_package_weight` | array | The weight in original package |
| `number_of_boxes` | array | Provide the number of boxes that the product comes in |

## Property Details

### item_name

Provide a title for the item that may be customer facing

**Type:** array

**Examples:**

- `Adidas Blue Sneakers`

### brand

Max. 50 characters

**Type:** array

**Examples:**

- `Sonny Brook Hams`

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

- `Clay model`

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

### target_audience_keyword

For whom is the product intended?

**Type:** array

**Examples:**

- `teens, toddlers, cats`

### model_name

Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size

**Type:** array

**Examples:**

- `MacBook Pro`

### manufacturer

Provide the company that manufactures the product.

**Type:** array

**Examples:**

- `Sony, Kitchen Aid, Microsoft`

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

The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum.

**Type:** array

**Examples:**

- `This ham has been smoked for 12 hours...`

### bullet_point

Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description.

**Type:** array

**Examples:**

- `Delicious honey-apricot glaze`

### generic_keyword

Provide specific search terms to help customers find your product.

**Type:** array

**Examples:**

- `Dark Chocolate, Apples, Cookies`

### style

Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product

**Type:** array

**Examples:**

- `Art Deco`

### target_gender

Provide the target gender for the product

**Type:** array

### age_range_description

Provide the age range the item is designed for, indicating the appropriate ages for safe and engaging play.

**Type:** array

**Examples:**

- `Baby`

### material

What material is the product made out of?

**Type:** array

**Examples:**

- `nylon, wood, steel`

### number_of_items

Provide the total number of identical items in the selling unit to the customer

**Type:** array

### item_package_quantity

Quantity of the item for sale in one package

**Type:** array

### subject_character

Provide the main character represented by the toy or game, indicating the primary figure or personality associated with the item.

**Type:** array

**Examples:**

- `Batman`

### color

Provide the color of the product

**Type:** array

**Examples:**

- `Cranberry`

### size

The numeric or text version of the item's size.

**Type:** array

**Examples:**

- `2T, 6X, 12, Small, X-Large, 18 months, 14 Tall, 28Wx32L`

### part_number

For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number.

**Type:** array

**Examples:**

- `LE`

### theme

Provide the primary high-level subject, concept, topic, motif, or idea of an item.

**Type:** array

**Examples:**

- `Sports`

### sub_brand

Provide the secondary brand or franchise the item is associated with, such as licensed characters or themes.

**Type:** array

**Examples:**

- `Princesses, Star Wars, Bountiful Harvest, 501`

### number_of_players

Specify the maximum number of players for the game.

**Type:** array

**Examples:**

- `3`

### edition

Product's version or edition

**Type:** array

**Examples:**

- `Teacher's Edition, Unabridged Version, etc.`

### power_source_type

Provide the type of power source the item uses, such as batteries or electricity, to operate and function.

**Type:** array

**Examples:**

- `AC, DC, Fuel Cell, Solar`

### is_assembly_required

Select: true or false

**Type:** array

**Examples:**

- `false`

### assembly_time

A positive whole number.

**Type:** array

**Examples:**

- `12`

### operation_mode

Provide the way the item functions, indicating whether it operates manually or automatically for play purposes.

**Type:** array

**Examples:**

- `Inverse`

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Examples:**

- `Floral, Geometric, Polka Dot`

### product_site_launch_date

Date you wish this detail page to launch.

**Type:** array

### manufacturer_minimum_age

Provide the recommended minimum age for the product in months

**Type:** array

**Examples:**

- `18`

### included_components

Specify the items that are included with this product

**Type:** array

**Examples:**

- `Camera Body`

### educational_objective

Provide the learning goal or skill the item aims to develop, such as problem-solving or hand-eye coordination.

**Type:** array

### indoor_outdoor_usage

Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor.

**Type:** array

**Examples:**

- `Indoor`

### publisher

Provide the publisher for the product

**Type:** array

**Examples:**

- `Tom Ford`

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

### safety_warning

List safety information customers should know.

**Type:** array

**Examples:**

- `Consult with a doctor before using this product.`

### country_of_origin

The country in which the product was published.

**Type:** array

### batteries_required

Indicate if batteries are required.

**Type:** array

### batteries_included

Indicate if batteries are included with the product.

**Type:** array

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

Total number of Lithium cells (of type "Metal") in the product, where the cell isn't contained in an encased battery.

**Type:** array

### number_of_lithium_ion_cells

Total number of Lithium cells (of type "Ion") in the product, where the cell isn't contained in an encased battery.

**Type:** array

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

Provide the weight of the item (not including the packaging)

**Type:** array

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

### california_proposition_65

Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required

**Type:** array

**Examples:**

- `Furniture; Lead`

### cpsia_cautionary_statement

You must select any applicable warning for choking hazards of children’s toys and games, or "no_warning_applicable". To verify warnings, contact the manufacturer or check the packaging.

**Type:** array

### pesticide_marking

Provide any pesticide marking on the item or packaging.

**Type:** array

**Examples:**

- `EPA Establishment Number`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `marking_type`

### fcc_radio_frequency_emission_compliance

Provide details on compliance to FCC regulations for products that may emit radio frequencies.

**Type:** array

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

### contains_pfas

Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals.

**Type:** array

**Examples:**

- `Yes`

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

### item_dimensions

Provide the item's dimensions

**Type:** array

**Examples:**

- `10 inches`

### item_package_dimensions

Provide the item's package dimensions

**Type:** array

**Examples:**

- `10 x 2 x 2.7 inches`

### item_package_weight

The weight in original package

**Type:** array

**Examples:**

- `14.89`

### number_of_boxes

Provide the number of boxes that the product comes in

**Type:** array

**Examples:**

- `5`

