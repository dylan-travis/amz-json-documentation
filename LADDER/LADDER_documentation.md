# LADDER Schema Documentation

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
- `legal_compliance_certifications` - Required when selectors `regulatory_organization_name`, `value`, `language_tag`, `marketplace_id` are specified
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
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `part_number.value` - Required when `part_number` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `load_capacity.value` - Required when `load_capacity` is provided
- `load_capacity.unit` - Required when `load_capacity` is provided
- `wattage.value` - Required when `wattage` is provided
- `voltage.value` - Required when `voltage` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `item_form.value` - Required when `item_form` is provided
- `item_form.language_tag` - Required when `item_form` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `length_range.value` - Required when `length_range` is provided
- `length_range.language_tag` - Required when `length_range` is provided
- `width_range.value` - Required when `width_range` is provided
- `width_range.language_tag` - Required when `width_range` is provided
- `item_width_height.height` - Required when `item_width_height` is provided
- `item_width_height.width` - Required when `item_width_height` is provided
- `number_of_steps.value` - Required when `number_of_steps` is provided
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
- `required_product_compliance_certificate.value` - Required when `required_product_compliance_certificate` is provided
- `legal_compliance_certifications.regulatory_organization_name` - Required when `legal_compliance_certifications` is provided
- `legal_compliance_certifications.certification_status` - Required when `legal_compliance_certifications` is provided
- `legal_compliance_certifications.value` - Required when `legal_compliance_certifications` is provided
- `legal_compliance_certifications.language_tag` - Required when `legal_compliance_certifications` is provided
- `california_proposition_65.compliance_type` - Required when `california_proposition_65` is provided
- `pesticide_marking.marking_type` - Required when `pesticide_marking` is provided
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
- `maximum_height.value` - Required when `maximum_height` is provided
- `maximum_height.unit` - Required when `maximum_height` is provided
- `item_display_weight.value` - Required when `item_display_weight` is provided
- `item_display_weight.unit` - Required when `item_display_weight` is provided

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `item_name` | array | Max. 250 characters |
| `brand` | array | Max. 50 characters |
| `externally_assigned_product_identifier` | array | Provide the external ID (barcode) type and corresponding value that is being used to identify the product |
| `merchant_suggested_asin` | array | Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID. |
| `supplier_declared_has_product_identifier_exemption` | array | Please specify if the product is exempt from supplier declared external product identifiers. |
| `item_type_keyword` | array | What is the item that you are selling? |
| `package_level` | array | Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy. |
| `package_contains_sku` | array | Provide the SKU and quantity of the child items contained in the next package level. |
| `model_number` | array | Product code assigned by the manufacturer; can be numbers, letters, or both |
| `model_name` | array | Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size |
| `manufacturer` | array | The full name of the publisher who issued the product |
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
| `product_description` | array | Max. 2,000 characters. Use this to describe the product in detail. Please enter only product-related features here. You'll have a chance later on to enter item condition, price, and other seller-specific info. |
| `bullet_point` | array | Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description. |
| `generic_keyword` | array | Provide specific search terms to help customers find your product. |
| `special_feature` | array | Provide the unique characteristics that set this ladder apart from similar products, enhancing its functionality or appeal. |
| `style` | array | The style of the item |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `item_shape` | array | The shape of the item |
| `edition` | array | Provide the version or edition of the item |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `flavor` | array | What flavor is the product? |
| `load_capacity` | array | Provide the load capacity. |
| `wattage` | array | The wattage rating of the product. Input a number only--do not enter units. |
| `voltage` | array | Provide the item's voltage |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `item_form` | array | Provide a value that represents the form of the item |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Provide the name of the sports team associated with the ladder, indicating the team branding or affiliation of the product. |
| `scent` | array | Provide a description of the scent of the item |
| `length_range` | array | Length range for blinds |
| `width_range` | array | Width range for blinds |
| `item_width_height` | array | Provide the measurement of the width and height of the item in ready to use condition |
| `number_of_steps` | array | Provide the total number of steps, that this product has. A step, or rung, allows users to climb the product. |
| `master_pack_dimensions` | array | Provide the width, height and depth measurements of the master pack. |
| `master_pack_weight` | array | Provide the weight measurement of the master pack item. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
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
| `required_product_compliance_certificate` | array | Select the regulation/restriction your product is subject to that requires a certificate such as an EO Number or Judgement Order for compliance. If your product is not subject to any of these regulations, select Not Applicable |
| `legal_compliance_certifications` | array | Provide relevant compliance certifications for the product |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `pesticide_marking` | array | Provide any pesticide marking on the item or packaging. |
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
| `item_package_weight` | array | The weight in original package |
| `maximum_height` | array | Provide the maximum height of the product |
| `item_display_weight` | array | Provide the item weight if the product is a solid |

## Property Details

### item_name

Max. 250 characters

**Type:** array

**Examples:**

- `KitchenAid KFP670 Professional Food Processor, White`

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

- `Extension ladders`

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

Product code assigned by the manufacturer; can be numbers, letters, or both

**Type:** array

**Examples:**

- `KFP670`

### model_name

Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size

**Type:** array

**Examples:**

- `MacBook Pro`

### manufacturer

The full name of the publisher who issued the product

**Type:** array

**Examples:**

- `KitchenAid; Whirlpool; Krups; Sealy`

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

Max. 2,000 characters. Use this to describe the product in detail. Please enter only product-related features here. You'll have a chance later on to enter item condition, price, and other seller-specific info.

**Type:** array

**Examples:**

- `These durable nonstick baking sheets...`

### bullet_point

Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description.

**Type:** array

**Examples:**

- `Non-stick coating makes clean-up easy`

### generic_keyword

Provide specific search terms to help customers find your product.

**Type:** array

**Examples:**

- `Dark Chocolate, Apples, Cookies`

### special_feature

Provide the unique characteristics that set this ladder apart from similar products, enhancing its functionality or appeal.

**Type:** array

**Examples:**

- `max number of images 36,  Operating Time 6 hours`

### style

The style of the item

**Type:** array

**Examples:**

- `Mission; Art Deco; Jack Purcell`

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

**Examples:**

- `3`

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

### item_shape

The shape of the item

**Type:** array

**Examples:**

- `Round; Oval; Square`

### edition

Provide the version or edition of the item

**Type:** array

**Examples:**

- `Teacher's Edition, Unabridged Version`

### item_display_dimensions

Provide the dimensions of the product, without packaging and fully assembled

**Type:** array

**Examples:**

- `5.7 Inches x 3.5 Inches x 1.8 Inches`

### flavor

What flavor is the product?

**Type:** array

**Examples:**

- `Double Rich Chocolate, Cherry, Chocolate, Vanilla`

### load_capacity

Provide the load capacity.

**Type:** array

**Examples:**

- `6 Pounds`

### wattage

The wattage rating of the product. Input a number only--do not enter units.

**Type:** array

### voltage

Provide the item's voltage

**Type:** array

**Examples:**

- `28 Volts`

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Examples:**

- `Floral, Geometric, Polka Dot`

### item_form

Provide a value that represents the form of the item

**Type:** array

**Examples:**

- `Sticks`

### unit_count

Specify the number of units and the unit type of the product

**Type:** array

**Examples:**

- `72.0 Ounces`

### product_site_launch_date

Date you wish this detail page to launch.

**Type:** array

### league_name

Name of league associated with this event

**Type:** array

**Examples:**

- `NBA`

### team_name

Provide the name of the sports team associated with the ladder, indicating the team branding or affiliation of the product.

**Type:** array

**Examples:**

- `Seattle Seahawks`

### scent

Provide a description of the scent of the item

**Type:** array

### length_range

Length range for blinds

**Type:** array

**Examples:**

- `24-60" long`

### width_range

Width range for blinds

**Type:** array

**Examples:**

- `24-60" wide`

### item_width_height

Provide the measurement of the width and height of the item in ready to use condition

**Type:** array

**Examples:**

- `40 Inches`

### number_of_steps

Provide the total number of steps, that this product has. A step, or rung, allows users to climb the product.

**Type:** array

**Examples:**

- `3`

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

### required_product_compliance_certificate

Select the regulation/restriction your product is subject to that requires a certificate such as an EO Number or Judgement Order for compliance. If your product is not subject to any of these regulations, select Not Applicable

**Type:** array

**Examples:**

- `California Air Resources Board (CARB), Not Applicable`

### legal_compliance_certifications

Provide relevant compliance certifications for the product

**Type:** array

**Examples:**

- `California Air Resources Board (CARB)`

**Conditionally Required**

**Conditionally Required based on selectors:** `regulatory_organization_name`, `value`, `language_tag`, `marketplace_id`

### california_proposition_65

Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required

**Type:** array

**Examples:**

- `Furniture; Lead`

### pesticide_marking

Provide any pesticide marking on the item or packaging.

**Type:** array

**Examples:**

- `EPA Establishment Number`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `marking_type`

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

The weight in original package

**Type:** array

**Examples:**

- `14.89`

### maximum_height

Provide the maximum height of the product

**Type:** array

**Examples:**

- `8.0 Feet`

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

