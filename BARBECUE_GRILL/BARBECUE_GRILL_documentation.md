# BARBECUE_GRILL Schema Documentation

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
- `control_type.value` - Required when `control_type` is provided
- `control_type.language_tag` - Required when `control_type` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `part_number.value` - Required when `part_number` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `trade_size_name.value` - Required when `trade_size_name` is provided
- `trade_size_name.language_tag` - Required when `trade_size_name` is provided
- `series_number.value` - Required when `series_number` is provided
- `capacity.value` - Required when `capacity` is provided
- `capacity.unit` - Required when `capacity` is provided
- `number_of_racks.value` - Required when `number_of_racks` is provided
- `is_assembly_required.value` - Required when `is_assembly_required` is provided
- `number_of_shelves.value` - Required when `number_of_shelves` is provided
- `number_of_shelves.language_tag` - Required when `number_of_shelves` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `fuel_type.value` - Required when `fuel_type` is provided
- `fuel_type.language_tag` - Required when `fuel_type` is provided
- `wattage.value` - Required when `wattage` is provided
- `voltage.value` - Required when `voltage` is provided
- `heating_power.value` - Required when `heating_power` is provided
- `heating_power.unit` - Required when `heating_power` is provided
- `installation_type.value` - Required when `installation_type` is provided
- `installation_type.language_tag` - Required when `installation_type` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `item_torque.value` - Required when `item_torque` is provided
- `item_torque.unit` - Required when `item_torque` is provided
- `finish_type.value` - Required when `finish_type` is provided
- `finish_type.language_tag` - Required when `finish_type` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `recommended_uses_for_product.value` - Required when `recommended_uses_for_product` is provided
- `recommended_uses_for_product.language_tag` - Required when `recommended_uses_for_product` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `has_automatic_shutoff.value` - Required when `has_automatic_shutoff` is provided
- `matte_style.value` - Required when `matte_style` is provided
- `matte_style.language_tag` - Required when `matte_style` is provided
- `number_of_heating_elements.value` - Required when `number_of_heating_elements` is provided
- `number_of_power_levels.value` - Required when `number_of_power_levels` is provided
- `outside_diameter.unit` - Required when `outside_diameter` is provided
- `control_method.value` - Required when `control_method` is provided
- `item_depth_width_height.depth` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.height` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.width` - Required when `item_depth_width_height` is provided
- `side_burner_count.value` - Required when `side_burner_count` is provided
- `main_burner_count.value` - Required when `main_burner_count` is provided
- `cooking_surface_area.value` - Required when `cooking_surface_area` is provided
- `cooking_surface_area.unit` - Required when `cooking_surface_area` is provided
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
- `pesticide_marking.marking_type` - Required when `pesticide_marking` is provided
- `fcc_radio_frequency_emission_compliance.registration_status` - Required when `fcc_radio_frequency_emission_compliance` is provided
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
- `website_shipping_weight.value` - Required when `website_shipping_weight` is provided
- `website_shipping_weight.unit` - Required when `website_shipping_weight` is provided
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
- `number_of_boxes.value` - Required when `number_of_boxes` is provided
- `master_pack_layers_per_pallet_quantity.value` - Required when `master_pack_layers_per_pallet_quantity` is provided
- `master_packs_per_layer_quantity.value` - Required when `master_packs_per_layer_quantity` is provided

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
| `handmade_classification` | array | Select the value that best describes how the product was produced |
| `product_description` | array | The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum. |
| `bullet_point` | array | Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description. |
| `generic_keyword` | array | Provide specific search terms to help customers find your product. |
| `special_feature` | array | An additional text field where you can indicate any additional relevant product information. |
| `style` | array | The style of the item |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `control_type` | array | Indicates the control that the user has on the device. |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `item_shape` | array | The shape of the item |
| `frame` | array | The attribute indicates the Frame of the product |
| `edition` | array | Provide the version or edition of the item |
| `configuration` | array | Indicate the configuration of the item |
| `trade_size_name` | array | Trade Size |
| `series_number` | array | Provide the identifying number for the item's model or product line, distinguishing it from other similar items. |
| `capacity` | array | The capacity of the item. |
| `number_of_racks` | array | Enter the number of racks. |
| `handle` | array | The attribute indicates Handle of the product |
| `is_assembly_required` | array | Indicate whether or not the item requires assembly by the customer |
| `number_of_shelves` | array | Provide the number of horizontal surfaces inside the item for holding food or cooking accessories. |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `flavor` | array | What flavor is the product? |
| `fuel_type` | array | Provide the type of fuel needed to power the product. |
| `wattage` | array | The wattage rating of the product. Input a number only--do not enter units. |
| `voltage` | array | If applicable, the Voltage of the product, if applicable. Input a number only--do not enter units. |
| `heating_power` | array | Provide the power for the item's heating function. |
| `installation_type` | array | Provide the way the item is set up for use, whether portable, built-in, or freestanding. |
| `customer_package_type` | array | Provide the products package type |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `item_torque` | array | Torque |
| `finish_type` | array | The appearance of the product (brushed nickel, cherry wood, etc) |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `included_components` | array | Which components are included? |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Please enter the team name of this product |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `scent` | array | Provide a description of the scent of the item |
| `has_automatic_shutoff` | array | Does item include automatic shutoff feature? |
| `band` | array | The attribute indicates Band of the product |
| `matte_style` | array | The type of matte on the product, typically furniture. |
| `number_of_heating_elements` | array | Provide the number of heating elements that the item has |
| `number_of_power_levels` | array | Provide the number of power levels that the item offers |
| `outside_diameter` | array | Provide the item's outside diameter |
| `control_method` | array | Provide the mechanism used to control the item for standard operations. |
| `item_depth_width_height` | array | The depth and width of the item in ready to use condition. Ready to use is defined as out of packaging and displayed as used for example fully rolled out for a rug or blanket. |
| `side_burner_count` | array | Provide the number of side burners the item has. Side burners are additional cooking surfaces located on the side of the grill. |
| `main_burner_count` | array | Provide the number of main burners the item has. Main burners are used to heat up the primary grate section. |
| `cooking_surface_area` | array | Provide the total area of all effective cooking surfaces when the item is placed in the manner in which it is expected to be used. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `country_of_origin` | array | The country in which the product was published. |
| `warranty_description` | array | Provide a description of the product's warranty |
| `batteries_required` | array | Indicate if batteries are required. |
| `batteries_included` | array | Indicate if batteries are included with the product. |
| `battery` | array | Provide battery information |
| `num_batteries` | array | Provide the quantity and type of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided |
| `number_of_lithium_metal_cells` | array | Total number of Lithium cells (of type "Metal") in the product, where the cell isn't contained in an encased battery. |
| `number_of_lithium_ion_cells` | array | Total number of Lithium cells (of type "Ion") in the product, where the cell isn't contained in an encased battery. |
| `lithium_battery` | array | The attribute indicates the Lithium Battery of the product |
| `supplier_declared_dg_hz_regulation` | array | If the product is a Dangerous Good or Hazardous Material, Substance or Waste that is regulated for transportation, storage, and/or waste select from the list of valid values |
| `ghs` | array | Provide the Global Harmonized System (GHS) information |
| `hazmat` | array | Provide hazmat information that is relevant to the product based on the aspect selected |
| `safety_data_sheet_url` | array | Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances. |
| `item_weight` | array | The weight of the product without shipping material. |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `pesticide_marking` | array | Provide any pesticide marking on the item or packaging. |
| `fcc_radio_frequency_emission_compliance` | array | Provide details on compliance to FCC regulations for products that may emit radio frequencies. |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person to comply with the General Product Safety Regulation (GPSR). If you’ve already submitted this Responsible Person’s information in the past, make sure you use the same email or URL. |
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
| `item_dimensions_fraction` | array | Provide the item dimensions |
| `website_shipping_weight` | array | Weight of the product when packaged to ship |
| `item_dimensions` | array | Provide the item's dimensions |
| `item_package_dimensions` | array | Provide the item's package dimensions |
| `item_package_weight` | array | The weight in original package |
| `item_display_weight` | array | Provide the item weight if the product is a solid |
| `number_of_boxes` | array | Provide the number of boxes that the product comes in |
| `master_pack_layers_per_pallet_quantity` | array | Provide the number of layers of master packs held on a pallet packed for storage (known as Hi). |
| `master_packs_per_layer_quantity` | array | Provide the number of master packs of the product in each layer on a pallet (known as Ti). |

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

- `Charcoal grills`

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

### special_feature

An additional text field where you can indicate any additional relevant product information.

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

**Examples:**

- `5`

### item_package_quantity

Quantity of the item for sale in one package

**Type:** array

### control_type

Indicates the control that the user has on the device.

**Type:** array

**Examples:**

- `Elevation`

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

### frame

The attribute indicates the Frame of the product

**Type:** array

**Examples:**

- `Eucalyptus Wood`

### edition

Provide the version or edition of the item

**Type:** array

**Examples:**

- `Teacher's Edition, Unabridged Version`

### configuration

Indicate the configuration of the item

**Type:** array

**Examples:**

- `AWD Configuration`

### trade_size_name

Trade Size

**Type:** array

**Examples:**

- `Y-1280, 1922V256`

### series_number

Provide the identifying number for the item's model or product line, distinguishing it from other similar items.

**Type:** array

**Examples:**

- `4`

### capacity

The capacity of the item.

**Type:** array

**Examples:**

- `5.3`

### number_of_racks

Enter the number of racks.

**Type:** array

**Examples:**

- `3`

### handle

The attribute indicates Handle of the product

**Type:** array

**Examples:**

- `Stainless Steel`

### is_assembly_required

Indicate whether or not the item requires assembly by the customer

**Type:** array

**Examples:**

- `Yes`

### number_of_shelves

Provide the number of horizontal surfaces inside the item for holding food or cooking accessories.

**Type:** array

**Examples:**

- `7`

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

### fuel_type

Provide the type of fuel needed to power the product.

**Type:** array

**Examples:**

- `Nitro`

### wattage

The wattage rating of the product. Input a number only--do not enter units.

**Type:** array

### voltage

If applicable, the Voltage of the product, if applicable. Input a number only--do not enter units.

**Type:** array

### heating_power

Provide the power for the item's heating function.

**Type:** array

**Examples:**

- `500.0 British Thermal Units`

### installation_type

Provide the way the item is set up for use, whether portable, built-in, or freestanding.

**Type:** array

**Examples:**

- `Countertop`

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

### item_torque

Torque

**Type:** array

**Examples:**

- `.047 in-lbs, 3.5 in-lbs, 43.2 in-lbs, 3620 in-lbs, 100 in-oz, 200 in-oz`

### finish_type

The appearance of the product (brushed nickel, cherry wood, etc)

**Type:** array

**Examples:**

- `Brushed Nickel`

### unit_count

Specify the number of units and the unit type of the product

**Type:** array

**Examples:**

- `72.0 Ounces`

### product_site_launch_date

Date you wish this detail page to launch.

**Type:** array

**Examples:**

- `2004-08-18`

### included_components

Which components are included?

**Type:** array

**Examples:**

- `Camera Body, Battery Pack`

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

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Examples:**

- `Cycling`

### scent

Provide a description of the scent of the item

**Type:** array

**Examples:**

- `Lavender`

### has_automatic_shutoff

Does item include automatic shutoff feature?

**Type:** array

**Examples:**

- `Yes`

### band

The attribute indicates Band of the product

**Type:** array

**Examples:**

- `Angstrom`

### matte_style

The type of matte on the product, typically furniture.

**Type:** array

**Examples:**

- `Matte, Smooth Matte, Silk Matte, Textured Matte`

### number_of_heating_elements

Provide the number of heating elements that the item has

**Type:** array

**Examples:**

- `7`

### number_of_power_levels

Provide the number of power levels that the item offers

**Type:** array

**Examples:**

- `7`

### outside_diameter

Provide the item's outside diameter

**Type:** array

**Examples:**

- `40 millimeters`

### control_method

Provide the mechanism used to control the item for standard operations.

**Type:** array

**Examples:**

- `App`

### item_depth_width_height

The depth and width of the item in ready to use condition. Ready to use is defined as out of packaging and displayed as used for example fully rolled out for a rug or blanket.

**Type:** array

**Examples:**

- `40 Inches`

### side_burner_count

Provide the number of side burners the item has. Side burners are additional cooking surfaces located on the side of the grill.

**Type:** array

**Examples:**

- `2`

### main_burner_count

Provide the number of main burners the item has. Main burners are used to heat up the primary grate section.

**Type:** array

**Examples:**

- `5`

### cooking_surface_area

Provide the total area of all effective cooking surfaces when the item is placed in the manner in which it is expected to be used.

**Type:** array

**Examples:**

- `810.93 Square Inches`

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

**Examples:**

- `FR`

### warranty_description

Provide a description of the product's warranty

**Type:** array

**Examples:**

- `2 Year Manufacturer`

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

The weight of the product without shipping material.

**Type:** array

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

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

### item_dimensions_fraction

Provide the item dimensions

**Type:** array

**Examples:**

- `8.66 Inches`

### website_shipping_weight

Weight of the product when packaged to ship

**Type:** array

**Examples:**

- `50 pounds`

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

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

### number_of_boxes

Provide the number of boxes that the product comes in

**Type:** array

**Examples:**

- `5`

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

