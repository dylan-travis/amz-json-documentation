# CASSEROLES Schema Documentation

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
- `generic_keyword.value` - Required when `generic_keyword` is provided
- `generic_keyword.language_tag` - Required when `generic_keyword` is provided
- `style.value` - Required when `style` is provided
- `style.language_tag` - Required when `style` is provided
- `age_range_description.value` - Required when `age_range_description` is provided
- `age_range_description.language_tag` - Required when `age_range_description` is provided
- `material.value` - Required when `material` is provided
- `material.language_tag` - Required when `material` is provided
- `number_of_items.value` - Required when `number_of_items` is provided
- `item_package_quantity.value` - Required when `item_package_quantity` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `part_number.value` - Required when `part_number` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `care_instructions.value` - Required when `care_instructions` is provided
- `care_instructions.language_tag` - Required when `care_instructions` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `is_dishwasher_safe.value` - Required when `is_dishwasher_safe` is provided
- `capacity.value` - Required when `capacity` is provided
- `capacity.unit` - Required when `capacity` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `volume_capacity_name.value` - Required when `volume_capacity_name` is provided
- `volume_capacity_name.language_tag` - Required when `volume_capacity_name` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `finish_type.value` - Required when `finish_type` is provided
- `finish_type.language_tag` - Required when `finish_type` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `has_lid.value` - Required when `has_lid` is provided
- `is_oven_safe.value` - Required when `is_oven_safe` is provided
- `item_depth_width_height.depth` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.height` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.width` - Required when `item_depth_width_height` is provided
- `interior_color.language_tag` - Required when `interior_color` is provided
- `interior_color.value` - Required when `interior_color` is provided
- `manufacture_year.value` - Required when `manufacture_year` is provided
- `master_pack_dimensions.height` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.length` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.width` - Required when `master_pack_dimensions` is provided
- `master_pack_weight.value` - Required when `master_pack_weight` is provided
- `master_pack_weight.unit` - Required when `master_pack_weight` is provided
- `parentage_level.value` - Required when `parentage_level` is provided
- `child_parent_sku_relationship.child_relationship_type` - Required when `child_parent_sku_relationship` is provided
- `variation_theme.name` - Required when `variation_theme` is provided
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
- `contains_pfas.value` - Required when `contains_pfas` is provided
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
- `item_dimensions.length` - Required when `item_dimensions` is provided
- `item_dimensions.width` - Required when `item_dimensions` is provided
- `item_dimensions.height` - Required when `item_dimensions` is provided
- `item_package_dimensions.length` - Required when `item_package_dimensions` is provided
- `item_package_dimensions.width` - Required when `item_package_dimensions` is provided
- `item_package_dimensions.height` - Required when `item_package_dimensions` is provided
- `item_package_weight.value` - Required when `item_package_weight` is provided
- `item_package_weight.unit` - Required when `item_package_weight` is provided
- `item_display_weight.value` - Required when `item_display_weight` is provided
- `item_display_weight.unit` - Required when `item_display_weight` is provided
- `master_pack_layers_per_pallet_quantity.value` - Required when `master_pack_layers_per_pallet_quantity` is provided
- `master_packs_per_layer_quantity.value` - Required when `master_packs_per_layer_quantity` is provided

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
| `product_description` | array | Provide a text description of the product. This information will appear in paragraph form on the detail page of your product. Include unique product features, product line details, and product specifications. Do not use all caps. |
| `bullet_point` | array | Brief descriptive text, called out via a bullet point, regarding a specific aspect of the product. These display directly under or next to your product photo, it is useful to put interesting information in these fields. Do NOT use all caps or abbreviations. Please do NOT use for fabric content, care instructions or country as these are populated in different fields. |
| `generic_keyword` | array | Provide any terms that may be relevant to customer searches. No repetition, no competitor brand names or ASINs. |
| `style` | array | Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product |
| `age_range_description` | array | Specify an appropriate age range description for the item |
| `material` | array | Specify the primary material used for manufacturing the item |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Provide the number of packages sold as part of a single item. An ASIN selling 5 boxes of paperclips with 100 paperclips per box would have item package quantity = '5' |
| `color` | array | Provide the color of the product |
| `size` | array | Provide the size of the item |
| `part_number` | array | Provide the part number. For many products, this will be identical to the model number however some manufacturers distinguish part number from model number |
| `dial` | array | The attribute indicates Dial of the product |
| `item_shape` | array | Specify the shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `ring` | array | The attribute indicates Ring of the product |
| `care_instructions` | array | Provide instructions related to how to care for the item |
| `configuration` | array | Indicate the configuration of the item |
| `is_dishwasher_safe` | array | If the item is dishwasher safe select yes, if it is not select no |
| `capacity` | array | Provide the capacity of the item |
| `flavor` | array | What flavor is the product? |
| `volume_capacity_name` | array | Provide the volume capacity of the item |
| `customer_package_type` | array | Provide the products package type |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `finish_type` | array | Specify the finish of the product's exterior surface |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Provide the name of the sports team associated with the casserole dish, indicating a themed or licensed product design. |
| `scent` | array | Provide a description of the scent of the item |
| `band` | array | The attribute indicates Band of the product |
| `has_lid` | array | Item includes a lid |
| `inside` | array | The attribute indicates Inside of the product |
| `is_oven_safe` | array | Item is oven safe |
| `lid` | array | The attribute indicates Lid of the product |
| `item_depth_width_height` | array | The depth and width of the item in ready to use condition. Ready to use is defined as out of packaging and displayed as used for example fully rolled out for a rug or blanket. |
| `interior_color` | array | The attribute indicates the Interior Color of the product |
| `manufacture_year` | array | Provide the year the item was manufactured. |
| `master_pack_dimensions` | array | Provide the width, height and depth measurements of the master pack. |
| `master_pack_weight` | array | Provide the weight measurement of the master pack item. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `country_of_origin` | array | Select the product's country of origin |
| `supplier_declared_dg_hz_regulation` | array | Provide the regulations that apply to the item if it is classified as a dangerous good, hazardous material, substance, or waste. |
| `ghs` | array | Provide the Global Harmonized System (GHS) information |
| `hazmat` | array | Provide hazmat information that is relevant to the product based on the aspect selected |
| `safety_data_sheet_url` | array | Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances. |
| `item_weight` | array | Provide the weight of the item (not including the packaging) |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations. |
| `compliance_media` | array | Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager. |
| `gpsr_safety_attestation` | array | Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it. |
| `gpsr_manufacturer_reference` | array | Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL. |
| `contains_pfas` | array | Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals. |
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
| `item_dimensions` | array | Provide the item's dimensions |
| `item_package_dimensions` | array | Provide the item's package dimensions |
| `item_package_weight` | array | Provide the weight of the item plus the packaging |
| `item_display_weight` | array | Provide the item weight if the product is a solid |
| `master_pack_layers_per_pallet_quantity` | array | Provide the number of layers of master packs held on a pallet packed for storage (known as Hi). |
| `master_packs_per_layer_quantity` | array | Provide the number of master packs of the product in each layer on a pallet (known as Ti). |

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

- `Lasagna pans`

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

### model_name

Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size

**Type:** array

**Examples:**

- `MacBook Pro`

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

### supplemental_condition_information

Provide the additional condition information on the non-new product.

**Type:** array

**Examples:**

- `iPhone 14, Open Box Never Used, OEM, Original, Greater than 90%, With Tags, Pristine, Fully Functional`

### product_description

Provide a text description of the product. This information will appear in paragraph form on the detail page of your product. Include unique product features, product line details, and product specifications. Do not use all caps.

**Type:** array

**Examples:**

- `This summer, boots by Jette made from high quality suede leather are real gems. They visually highlight the craftsmanship and fine leather braid positioned at the top of the shaft`

### bullet_point

Brief descriptive text, called out via a bullet point, regarding a specific aspect of the product. These display directly under or next to your product photo, it is useful to put interesting information in these fields. Do NOT use all caps or abbreviations. Please do NOT use for fabric content, care instructions or country as these are populated in different fields.

**Type:** array

**Examples:**

- `Breathable Leather Lining`

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

### age_range_description

Specify an appropriate age range description for the item

**Type:** array

**Examples:**

- `Baby`

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

### part_number

Provide the part number. For many products, this will be identical to the model number however some manufacturers distinguish part number from model number

**Type:** array

**Examples:**

- `RIV001`

### dial

The attribute indicates Dial of the product

**Type:** array

**Examples:**

- `Green`

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

### care_instructions

Provide instructions related to how to care for the item

**Type:** array

**Examples:**

- `Hand Wash`

### configuration

Indicate the configuration of the item

**Type:** array

**Examples:**

- `AWD Configuration`

### is_dishwasher_safe

If the item is dishwasher safe select yes, if it is not select no

**Type:** array

**Examples:**

- `Yes`

### capacity

Provide the capacity of the item

**Type:** array

**Examples:**

- `5.3 Liters`

### flavor

What flavor is the product?

**Type:** array

**Examples:**

- `Double Rich Chocolate, Cherry, Chocolate, Vanilla`

### volume_capacity_name

Provide the volume capacity of the item

**Type:** array

**Examples:**

- `7 liters, 16 ounces`

### customer_package_type

Provide the products package type

**Type:** array

**Examples:**

- `Standard Packaging`

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Examples:**

- `Floral, Geometric, Polka Dot`

### finish_type

Specify the finish of the product's exterior surface

**Type:** array

**Examples:**

- `Enamel`

### unit_count

Specify the number of units and the unit type of the product

**Type:** array

**Examples:**

- `72.0 Ounces`

### league_name

Name of league associated with this event

**Type:** array

**Examples:**

- `NBA`

### team_name

Provide the name of the sports team associated with the casserole dish, indicating a themed or licensed product design.

**Type:** array

**Examples:**

- `Seattle Seahawks`

### scent

Provide a description of the scent of the item

**Type:** array

**Examples:**

- `Lavender`

### band

The attribute indicates Band of the product

**Type:** array

**Examples:**

- `Angstrom`

### has_lid

Item includes a lid

**Type:** array

**Examples:**

- `Yes`

### inside

The attribute indicates Inside of the product

**Type:** array

**Examples:**

- `Angstrom`

### is_oven_safe

Item is oven safe

**Type:** array

**Examples:**

- `Yes`

### lid

The attribute indicates Lid of the product

**Type:** array

**Examples:**

- `Plastic`

### item_depth_width_height

The depth and width of the item in ready to use condition. Ready to use is defined as out of packaging and displayed as used for example fully rolled out for a rug or blanket.

**Type:** array

**Examples:**

- `40 Inches`

### interior_color

The attribute indicates the Interior Color of the product

**Type:** array

### manufacture_year

Provide the year the item was manufactured.

**Type:** array

**Examples:**

- `2023`

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

Provide the weight of the item plus the packaging

**Type:** array

**Examples:**

- `0.65 Pounds`

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

**Examples:**

- `20.0 Pounds, 50.0 Kilograms`

### master_pack_layers_per_pallet_quantity

Provide the number of layers of master packs held on a pallet packed for storage (known as Hi).

**Type:** array

**Examples:**

- `5`

### master_packs_per_layer_quantity

Provide the number of master packs of the product in each layer on a pallet (known as Ti).

**Type:** array

**Examples:**

- `9`

