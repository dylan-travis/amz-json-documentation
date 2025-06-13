# LIGHT_FIXTURE Schema Documentation

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
- `water_resistance_level.value` - Required when `water_resistance_level` is provided
- `special_size_type.value` - Required when `special_size_type` is provided
- `special_size_type.language_tag` - Required when `special_size_type` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `part_number.value` - Required when `part_number` is provided
- `warranty_type.value` - Required when `warranty_type` is provided
- `warranty_type.language_tag` - Required when `warranty_type` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `fixture_type.value` - Required when `fixture_type` is provided
- `fixture_type.language_tag` - Required when `fixture_type` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `light_color.value` - Required when `light_color` is provided
- `light_color.language_tag` - Required when `light_color` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `coverage.value` - Required when `coverage` is provided
- `coverage.language_tag` - Required when `coverage` is provided
- `color_temperature.value` - Required when `color_temperature` is provided
- `color_temperature.unit` - Required when `color_temperature` is provided
- `power_source_type.value` - Required when `power_source_type` is provided
- `power_source_type.language_tag` - Required when `power_source_type` is provided
- `is_assembly_required.value` - Required when `is_assembly_required` is provided
- `lighting_method.value` - Required when `lighting_method` is provided
- `lighting_method.language_tag` - Required when `lighting_method` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `specification_met.value` - Required when `specification_met` is provided
- `specification_met.language_tag` - Required when `specification_met` is provided
- `wattage.value` - Required when `wattage` is provided
- `wattage.unit` - Required when `wattage` is provided
- `voltage.value` - Required when `voltage` is provided
- `voltage.unit` - Required when `voltage` is provided
- `installation_type.value` - Required when `installation_type` is provided
- `installation_type.language_tag` - Required when `installation_type` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `mounting_type.value` - Required when `mounting_type` is provided
- `mounting_type.language_tag` - Required when `mounting_type` is provided
- `brightness.value` - Required when `brightness` is provided
- `brightness.language_tag` - Required when `brightness` is provided
- `finish_type.value` - Required when `finish_type` is provided
- `finish_type.language_tag` - Required when `finish_type` is provided
- `switch_type.value` - Required when `switch_type` is provided
- `switch_type.language_tag` - Required when `switch_type` is provided
- `base_type.value` - Required when `base_type` is provided
- `base_type.language_tag` - Required when `base_type` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `connectivity_protocol.value` - Required when `connectivity_protocol` is provided
- `connectivity_protocol.language_tag` - Required when `connectivity_protocol` is provided
- `controller_type.value` - Required when `controller_type` is provided
- `controller_type.language_tag` - Required when `controller_type` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `specific_uses_for_product.value` - Required when `specific_uses_for_product` is provided
- `specific_uses_for_product.language_tag` - Required when `specific_uses_for_product` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `temperature_rating_degrees.value` - Required when `temperature_rating_degrees` is provided
- `recommended_uses_for_product.value` - Required when `recommended_uses_for_product` is provided
- `recommended_uses_for_product.language_tag` - Required when `recommended_uses_for_product` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `hand_orientation.value` - Required when `hand_orientation` is provided
- `hand_orientation.language_tag` - Required when `hand_orientation` is provided
- `embellishment_feature.value` - Required when `embellishment_feature` is provided
- `embellishment_feature.language_tag` - Required when `embellishment_feature` is provided
- `matte_style.value` - Required when `matte_style` is provided
- `matte_style.language_tag` - Required when `matte_style` is provided
- `room_type.value` - Required when `room_type` is provided
- `room_type.language_tag` - Required when `room_type` is provided
- `number_of_light_sources.value` - Required when `number_of_light_sources` is provided
- `control_method.value` - Required when `control_method` is provided
- `indoor_outdoor_usage.value` - Required when `indoor_outdoor_usage` is provided
- `item_length_width_height.height` - Required when `item_length_width_height` is provided
- `item_length_width_height.length` - Required when `item_length_width_height` is provided
- `item_length_width_height.width` - Required when `item_length_width_height` is provided
- `light_fixture_form.value` - Required when `light_fixture_form` is provided
- `master_pack_dimensions.height` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.length` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.width` - Required when `master_pack_dimensions` is provided
- `master_pack_weight.value` - Required when `master_pack_weight` is provided
- `master_pack_weight.unit` - Required when `master_pack_weight` is provided
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
- `fcc_radio_frequency_emission_compliance.registration_status` - Required when `fcc_radio_frequency_emission_compliance` is provided
- `regulatory_compliance_certification.regulation_type` - Required when `regulatory_compliance_certification` is provided
- `regulatory_compliance_certification.value` - Required when `regulatory_compliance_certification` is provided
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
| `item_type_keyword` | array | Item type keywords are used to place new ASINs in the appropriate place(s) within the graph. Select the most specific accurate term for optimal placement. |
| `package_level` | array | Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy. |
| `package_contains_sku` | array | Provide the SKU and quantity of the child items contained in the next package level. |
| `model_number` | array | Product code assigned by the manufacturer; can be numbers, letters, or both |
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
| `water_resistance_level` | array | Provide the degree to which the item can resist water |
| `special_size_type` | array | Specify the special size type for the item |
| `display` | array | The attribute indicates the Display of the product |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `dial` | array | The attribute indicates Dial of the product |
| `warranty_type` | array | Enter the type of warranty for this item |
| `item_shape` | array | The shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `ring` | array | The attribute indicates Ring of the product |
| `fixture_type` | array | The attribute indicates the Fixture Type of the product |
| `edition` | array | Provide the version or edition of the item |
| `light_color` | array | Provide the color of the light generated by the product |
| `configuration` | array | Indicate the configuration of the item |
| `coverage` | array | Provide the amount or type of coverage the item has |
| `color_temperature` | array | Provide the color temperature of the product |
| `power_source_type` | array | The item's power source. |
| `is_assembly_required` | array | Indicate whether or not the item requires assembly by the customer |
| `lens` | array | The attribute indicates Lens of the product |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `lighting_method` | array | Specify the product's lighting method |
| `flavor` | array | What flavor is the product? |
| `specification_met` | array | Provide the standard or regulation the item meets, ensuring it complies with safety and quality requirements. |
| `wattage` | array | The wattage rating of the product. Input a number only--do not enter units. |
| `voltage` | array | If applicable, the Voltage of the product, if applicable. Input a number only--do not enter units. |
| `installation_type` | array | Specify the type of installation the item requires |
| `customer_package_type` | array | Provide the products package type |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `mounting_type` | array | Provide the way the item is installed or attached, how it is secured in place, relevant for proper lighting setup. |
| `brightness` | array | Provide the brightness of the product |
| `finish_type` | array | Specify the finish of the product's exterior surface |
| `switch_type` | array | Provide the type of switch used to control the item, how it turns on/off or adjusts brightness, relevant for operation. |
| `base_type` | array | Provide the type of base the product has or uses |
| `unit_count` | array | Provide the total number of units that make up the item, indicating its size or quantity. |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `connectivity_protocol` | array | Provide the wireless standard the item uses to connect to other devices, allowing control and communication. |
| `controller_type` | array | Provide the type of device or app used to control the item, like a smartphone app or computer software. |
| `included_components` | array | Which components are included? |
| `specific_uses_for_product` | array | Select from the list of suggested values the conditions, or usages for which the product is specifically intended. |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Please enter the team name of this product |
| `temperature_rating_degrees` | array | The temperature rating at which the item will continue to work. |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `scent` | array | Provide a description of the scent of the item |
| `hand_orientation` | array | Provide the hand orientation that the item is built for; left, right or both |
| `bulb` | array | The attribute indicates Bulb of the product |
| `band` | array | The attribute indicates Band of the product |
| `cup` | array | The attribute indicates Cup of the product |
| `embellishment_feature` | array | Provide the decorative elements or designs on the item, enhancing its appearance or style. |
| `light_source` | array | The attribute indicates Light Source of the product |
| `matte_style` | array | The type of matte on the product, typically furniture. |
| `room_type` | array | Provide the type of room the product is intended for. |
| `shade` | array | The attribute indicates Shade of the product |
| `number_of_light_sources` | array | Provide the number of light sources the product has |
| `control_method` | array | Provide the way the item is operated, like using an app or physical controls, to turn it on/off or adjust settings. |
| `indoor_outdoor_usage` | array | Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor. |
| `item_length_width_height` | array | Provide the length, width and height of the item in ready to use condition. |
| `light_fixture_form` | array | Provide the form type of the light fixture. The form type describes the overall shape and physical design of the light fixture. |
| `master_pack_dimensions` | array | Provide the width, height and depth measurements of the master pack. |
| `master_pack_weight` | array | Provide the weight measurement of the master pack item. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `country_of_origin` | array | The country in which the product was published. |
| `warranty_description` | array | Describe the warranty. |
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
| `item_weight` | array | Provide the weight of the item (not including the packaging) |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `fcc_radio_frequency_emission_compliance` | array | Provide details on compliance to FCC regulations for products that may emit radio frequencies. |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
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

Item type keywords are used to place new ASINs in the appropriate place(s) within the graph. Select the most specific accurate term for optimal placement.

**Type:** array

**Examples:**

- `Chandeliers`

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

- `C-50`

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

### item_package_quantity

Quantity of the item for sale in one package

**Type:** array

### water_resistance_level

Provide the degree to which the item can resist water

**Type:** array

**Examples:**

- `Water Resistant`

### special_size_type

Specify the special size type for the item

**Type:** array

**Examples:**

- `Husky, Petite`

### display

The attribute indicates the Display of the product

**Type:** array

**Examples:**

- `LCD`

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

### dial

The attribute indicates Dial of the product

**Type:** array

**Examples:**

- `Green`

### warranty_type

Enter the type of warranty for this item

**Type:** array

### item_shape

The shape of the item

**Type:** array

**Examples:**

- `Round; Oval; Square`

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

### fixture_type

The attribute indicates the Fixture Type of the product

**Type:** array

**Examples:**

- `Fixed`

### edition

Provide the version or edition of the item

**Type:** array

**Examples:**

- `Teacher's Edition, Unabridged Version`

### light_color

Provide the color of the light generated by the product

**Type:** array

**Examples:**

- `Green`

### configuration

Indicate the configuration of the item

**Type:** array

**Examples:**

- `AWD Configuration`

### coverage

Provide the amount or type of coverage the item has

**Type:** array

**Examples:**

- `56 Square Feet`

### color_temperature

Provide the color temperature of the product

**Type:** array

**Examples:**

- `3000.0 Kelvin`

### power_source_type

The item's power source.

**Type:** array

**Examples:**

- `AC, DC, Fuel Cell, Solar`

### is_assembly_required

Indicate whether or not the item requires assembly by the customer

**Type:** array

**Examples:**

- `Yes`

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

### lighting_method

Specify the product's lighting method

**Type:** array

**Examples:**

- `Downlight`

### flavor

What flavor is the product?

**Type:** array

**Examples:**

- `Double Rich Chocolate, Cherry, Chocolate, Vanilla`

### specification_met

Provide the standard or regulation the item meets, ensuring it complies with safety and quality requirements.

**Type:** array

**Examples:**

- `AMS, ASTM, MIL`

### wattage

The wattage rating of the product. Input a number only--do not enter units.

**Type:** array

### voltage

If applicable, the Voltage of the product, if applicable. Input a number only--do not enter units.

**Type:** array

### installation_type

Specify the type of installation the item requires

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

### mounting_type

Provide the way the item is installed or attached, how it is secured in place, relevant for proper lighting setup.

**Type:** array

**Examples:**

- `Clevis`

### brightness

Provide the brightness of the product

**Type:** array

**Examples:**

- `500 lm`

### finish_type

Specify the finish of the product's exterior surface

**Type:** array

### switch_type

Provide the type of switch used to control the item, how it turns on/off or adjusts brightness, relevant for operation.

**Type:** array

**Examples:**

- `Metal`

### base_type

Provide the type of base the product has or uses

**Type:** array

**Examples:**

- `Pedestal`

### unit_count

Provide the total number of units that make up the item, indicating its size or quantity.

**Type:** array

**Examples:**

- `72.0 Ounces`

### product_site_launch_date

Date you wish this detail page to launch.

**Type:** array

### connectivity_protocol

Provide the wireless standard the item uses to connect to other devices, allowing control and communication.

**Type:** array

**Examples:**

- `Arrayant`

### controller_type

Provide the type of device or app used to control the item, like a smartphone app or computer software.

**Type:** array

**Examples:**

- `Wimoto`

### included_components

Which components are included?

**Type:** array

**Examples:**

- `Camera Body, Battery Pack`

### specific_uses_for_product

Select from the list of suggested values the conditions, or usages for which the product is specifically intended.

**Type:** array

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

### temperature_rating_degrees

The temperature rating at which the item will continue to work.

**Type:** array

**Examples:**

- `15.0 °F, -5.0 °C`

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Examples:**

- `Cycling`

### scent

Provide a description of the scent of the item

**Type:** array

### hand_orientation

Provide the hand orientation that the item is built for; left, right or both

**Type:** array

**Examples:**

- `Left Hand`

### bulb

The attribute indicates Bulb of the product

**Type:** array

**Examples:**

- `Angstrom`

### band

The attribute indicates Band of the product

**Type:** array

**Examples:**

- `Angstrom`

### cup

The attribute indicates Cup of the product

**Type:** array

**Examples:**

- `B`

### embellishment_feature

Provide the decorative elements or designs on the item, enhancing its appearance or style.

**Type:** array

**Examples:**

- `Buckle`

### light_source

The attribute indicates Light Source of the product

**Type:** array

**Examples:**

- `LED`

### matte_style

The type of matte on the product, typically furniture.

**Type:** array

**Examples:**

- `Matte, Smooth Matte, Silk Matte, Textured Matte`

### room_type

Provide the type of room the product is intended for.

**Type:** array

**Examples:**

- `Bedroom`

### shade

The attribute indicates Shade of the product

**Type:** array

**Examples:**

- `Turquiose`

### number_of_light_sources

Provide the number of light sources the product has

**Type:** array

**Examples:**

- `1`

### control_method

Provide the way the item is operated, like using an app or physical controls, to turn it on/off or adjust settings.

**Type:** array

**Examples:**

- `App`

### indoor_outdoor_usage

Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor.

**Type:** array

**Examples:**

- `Indoor`

### item_length_width_height

Provide the length, width and height of the item in ready to use condition.

**Type:** array

**Examples:**

- `100 Inches`

### light_fixture_form

Provide the form type of the light fixture. The form type describes the overall shape and physical design of the light fixture.

**Type:** array

**Examples:**

- `Chandelier`

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

### warranty_description

Describe the warranty.

**Type:** array

**Examples:**

- `Manufacturer warranty for 90 days from date of purchase.`

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

