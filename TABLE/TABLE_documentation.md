# TABLE Schema Documentation

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
- `language` - Required when selectors `marketplace_id`, `type` are specified
- `num_batteries` - Required when selectors `marketplace_id`, `type` are specified
- `hazmat` - Required when selectors `marketplace_id`, `aspect` are specified
- `regulatory_compliance_certification` - Required when selectors `marketplace_id`, `regulation_type` are specified
- `compliance_media` - Required when selectors `marketplace_id`, `content_type`, `content_language` are specified
- `ghs_chemical_h_code` - Required when selectors `marketplace_id`, `value` are specified
- `externally_assigned_product_identifier.type` - Required when `externally_assigned_product_identifier` is provided
- `externally_assigned_product_identifier.value` - Required when `externally_assigned_product_identifier` is provided
- `merchant_suggested_asin.value` - Required when `merchant_suggested_asin` is provided
- `supplier_declared_has_product_identifier_exemption.value` - Required when `supplier_declared_has_product_identifier_exemption` is provided
- `edge_style.value` - Required when `edge_style` is provided
- `edge_style.language_tag` - Required when `edge_style` is provided
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
- `age_range_description.value` - Required when `age_range_description` is provided
- `age_range_description.language_tag` - Required when `age_range_description` is provided
- `material.value` - Required when `material` is provided
- `material.language_tag` - Required when `material` is provided
- `number_of_items.value` - Required when `number_of_items` is provided
- `item_package_quantity.value` - Required when `item_package_quantity` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `item_diameter.unit` - Required when `item_diameter` is provided
- `part_number.value` - Required when `part_number` is provided
- `warranty_type.value` - Required when `warranty_type` is provided
- `warranty_type.language_tag` - Required when `warranty_type` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `is_resizable.value` - Required when `is_resizable` is provided
- `care_instructions.value` - Required when `care_instructions` is provided
- `care_instructions.language_tag` - Required when `care_instructions` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `paper_size.value` - Required when `paper_size` is provided
- `paper_size.language_tag` - Required when `paper_size` is provided
- `line_size.value` - Required when `line_size` is provided
- `line_size.language_tag` - Required when `line_size` is provided
- `hardware_platform.value` - Required when `hardware_platform` is provided
- `hardware_platform.language_tag` - Required when `hardware_platform` is provided
- `platform_for_display.value` - Required when `platform_for_display` is provided
- `platform_for_display.language_tag` - Required when `platform_for_display` is provided
- `language.type` - Required when `language` is provided
- `language.value` - Required when `language` is provided
- `is_customizable.value` - Required when `is_customizable` is provided
- `number_of_racks.value` - Required when `number_of_racks` is provided
- `number_of_doors.value` - Required when `number_of_doors` is provided
- `is_foldable.value` - Required when `is_foldable` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `assembly_instructions.value` - Required when `assembly_instructions` is provided
- `assembly_instructions.language_tag` - Required when `assembly_instructions` is provided
- `feet_type.value` - Required when `feet_type` is provided
- `feet_type.language_tag` - Required when `feet_type` is provided
- `access_method.value` - Required when `access_method` is provided
- `access_method.language_tag` - Required when `access_method` is provided
- `furniture_finish.value` - Required when `furniture_finish` is provided
- `furniture_finish.language_tag` - Required when `furniture_finish` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `base_type.value` - Required when `base_type` is provided
- `base_type.language_tag` - Required when `base_type` is provided
- `item_form.value` - Required when `item_form` is provided
- `item_form.language_tag` - Required when `item_form` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `specific_uses_for_product.value` - Required when `specific_uses_for_product` is provided
- `specific_uses_for_product.language_tag` - Required when `specific_uses_for_product` is provided
- `league_name.value` - Required when `league_name` is provided
- `league_name.language_tag` - Required when `league_name` is provided
- `team_name.value` - Required when `team_name` is provided
- `team_name.language_tag` - Required when `team_name` is provided
- `athlete.value` - Required when `athlete` is provided
- `athlete.language_tag` - Required when `athlete` is provided
- `recommended_uses_for_product.value` - Required when `recommended_uses_for_product` is provided
- `recommended_uses_for_product.language_tag` - Required when `recommended_uses_for_product` is provided
- `is_fragile.value` - Required when `is_fragile` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `is_stain_resistant.value` - Required when `is_stain_resistant` is provided
- `has_tilting.value` - Required when `has_tilting` is provided
- `length_range.value` - Required when `length_range` is provided
- `length_range.language_tag` - Required when `length_range` is provided
- `room_type.value` - Required when `room_type` is provided
- `room_type.language_tag` - Required when `room_type` is provided
- `width_range.value` - Required when `width_range` is provided
- `width_range.language_tag` - Required when `width_range` is provided
- `extended_length.value` - Required when `extended_length` is provided
- `extended_length.unit` - Required when `extended_length` is provided
- `maximum_weight_recommendation.value` - Required when `maximum_weight_recommendation` is provided
- `maximum_weight_recommendation.unit` - Required when `maximum_weight_recommendation` is provided
- `number_of_height_positions.value` - Required when `number_of_height_positions` is provided
- `minimum_required_door_width.value` - Required when `minimum_required_door_width` is provided
- `minimum_required_door_width.unit` - Required when `minimum_required_door_width` is provided
- `indoor_outdoor_usage.value` - Required when `indoor_outdoor_usage` is provided
- `table_design.value` - Required when `table_design` is provided
- `item_length_width_height.height` - Required when `item_length_width_height` is provided
- `item_length_width_height.length` - Required when `item_length_width_height` is provided
- `item_length_width_height.width` - Required when `item_length_width_height` is provided
- `furniture_base_movement.value` - Required when `furniture_base_movement` is provided
- `decorative_plating.value` - Required when `decorative_plating` is provided
- `item_depth_width_height.depth` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.height` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.width` - Required when `item_depth_width_height` is provided
- `item_width.value` - Required when `item_width` is provided
- `item_width.unit` - Required when `item_width` is provided
- `tabletop_thickness.value` - Required when `tabletop_thickness` is provided
- `tabletop_thickness.unit` - Required when `tabletop_thickness` is provided
- `recommended_number_of_people_for_assembly.value` - Required when `recommended_number_of_people_for_assembly` is provided
- `ground_to_item_distance.value` - Required when `ground_to_item_distance` is provided
- `ground_to_item_distance.unit` - Required when `ground_to_item_distance` is provided
- `tools_recommended_for_assembly.value` - Required when `tools_recommended_for_assembly` is provided
- `number_of_leaves.value` - Required when `number_of_leaves` is provided
- `table_extension_mechanism.value` - Required when `table_extension_mechanism` is provided
- `table_extension_mechanism.language_tag` - Required when `table_extension_mechanism` is provided
- `collapsed_length_minimum.value` - Required when `collapsed_length_minimum` is provided
- `collapsed_length_minimum.unit` - Required when `collapsed_length_minimum` is provided
- `natural_variation_type.value` - Required when `natural_variation_type` is provided
- `natural_variation_type.language_tag` - Required when `natural_variation_type` is provided
- `unextended_seating_capacity.value` - Required when `unextended_seating_capacity` is provided
- `umbrella_hole_diameter.value` - Required when `umbrella_hole_diameter` is provided
- `umbrella_hole_diameter.unit` - Required when `umbrella_hole_diameter` is provided
- `includes_all_assembly_tools.value` - Required when `includes_all_assembly_tools` is provided
- `base_to_top_distance.value` - Required when `base_to_top_distance` is provided
- `base_to_top_distance.unit` - Required when `base_to_top_distance` is provided
- `bench_quantity.value` - Required when `bench_quantity` is provided
- `set_name.value` - Required when `set_name` is provided
- `set_name.language_tag` - Required when `set_name` is provided
- `parentage_level.value` - Required when `parentage_level` is provided
- `child_parent_sku_relationship.child_relationship_type` - Required when `child_parent_sku_relationship` is provided
- `variation_theme.name` - Required when `variation_theme` is provided
- `safety_warning.value` - Required when `safety_warning` is provided
- `safety_warning.language_tag` - Required when `safety_warning` is provided
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
| `edge_style` | array | Provide the style of the edge of the item |
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
| `product_description` | array | The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum. |
| `bullet_point` | array | Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description. |
| `generic_keyword` | array | Provide specific search terms to help customers find your product. |
| `special_feature` | array | An additional text field where you can indicate any additional relevant product information. |
| `style` | array | The style of the item |
| `age_range_description` | array | Provide the age group the item is suitable for, describing who can safely use or interact with it. |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `item_diameter` | array | Provide the width across the item's circular top, the distance from one side to the other through the center. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `warranty_type` | array | Enter the type of warranty for this item |
| `item_shape` | array | The shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `is_resizable` | array | If the item is resizable select yes, if it is not select no |
| `ring` | array | The attribute indicates Ring of the product |
| `care_instructions` | array | Provide instructions related to how to care for the item |
| `frame` | array | The attribute indicates the Frame of the product |
| `edition` | array | Provide the version or edition of the item |
| `configuration` | array | Indicate the configuration of the item |
| `paper_size` | array | Specify the size of the paper |
| `line_size` | array | Provide the product's line or point size |
| `hardware_platform` | array | Provide the product's hardware platform |
| `platform_for_display` | array | Provide the platform associated with the product. |
| `language` | array | Select the appropriate language from the list of valid values |
| `is_customizable` | array | Is customizable? |
| `number_of_racks` | array | Enter the number of racks. |
| `handle` | array | The attribute indicates Handle of the product |
| `number_of_doors` | array | Provide the number of doors the product has |
| `is_foldable` | array | Provide whether the structural feature of the product can be folded or not. |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `flavor` | array | What flavor is the product? |
| `assembly_instructions` | array | Provide the step-by-step directions needed for a user to assemble the product. |
| `feet_type` | array | The type of feet on the item |
| `access_method` | array | Provide the access method |
| `furniture_finish` | array | the finish of furniture |
| `customer_package_type` | array | Provide the products package type |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `base_type` | array | Provide the type of base the product has or uses |
| `item_form` | array | Provide a value that represents the form of the item |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `included_components` | array | Which components are included? |
| `specific_uses_for_product` | array | Select from the list of suggested values the conditions, or usages for which the product is specifically intended. |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Provide the name of the sports team associated with the furniture item, indicating the team-themed design or branding. |
| `athlete` | array | Name of athlete participating in the event |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `is_fragile` | array | Is the item fragile? |
| `scent` | array | Provide a description of the scent of the item |
| `is_stain_resistant` | array | Is the item made of a stain resistant material or has it been treated to be stain resistant |
| `base` | array | Enter the specifications for the base |
| `has_tilting` | array | Provide whether the item can change its angle or orientation, allowing adjustment of viewing or positioning. |
| `length_range` | array | Length range for blinds |
| `maximum_lifting_height` | array | Provide the maximum lifting height |
| `room_type` | array | Provide the type of room the table is designed for, influencing its size, features, and aesthetics. |
| `shelf` | array | The attribute indicates Shelf of the product |
| `top` | array | The attribute indicates Top of the product |
| `width_range` | array | Width range for blinds |
| `extended_length` | array | Enter the length of the item when extended. Do not include modifier. |
| `maximum_weight_recommendation` | array | Provide the highest weight the item can safely support, the maximum load it can bear without issues. |
| `number_of_height_positions` | array | Specify the number of height positions |
| `minimum_required_door_width` | array | Provide the minimum width of a doorway needed for the piece of furniture to fit through. This information is typically used as a measurement for delivery. |
| `furniture_leg` | array | Describes the furniture item's legs |
| `indoor_outdoor_usage` | array | Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor. |
| `table_design` | array | Provide the design type of the table. The table design represents a standard form of the table based around the specific user needs for example the structure of the surface. |
| `item_length_width_height` | array | Provide the length, width and height of the item in ready to use condition. |
| `furniture_base_movement` | array | Provide the way the item's base allows it to move, enabling stability and mobility, like gliding or swiveling. |
| `decorative_plating` | array | Provide the decorative metal coating on the item, used to enhance appearance, prevent corrosion, or improve durability. |
| `item_depth_width_height` | array | Provide the dimensions of the item when ready for use, like a fully unrolled rug or blanket, excluding packaging. |
| `item_width` | array | Provide the width of the item in ready to use condition. |
| `tabletop_thickness` | array | Provide the dimensional thickness of the product's tabletop. A tabletop is the raised flat surface on top of a furniture table. |
| `recommended_number_of_people_for_assembly` | array | Provide the amount of people recommended to assemble the item. |
| `ground_to_item_distance` | array | Provide the distance from ground to item (clearance), measured from the lowest point (excluding feet/legs) to the surface it rests on. |
| `tools_recommended_for_assembly` | array | Provide the type of tools recommended to assemble the components of the item. |
| `number_of_leaves` | array | Provide the number of leaves included with this item. Leaves are additional tabletop pieces used to expand the size of the table. |
| `table_extension_mechanism` | array | Provide the method used to increase the table's surface area when needed, such as expanding or adding sections to accommodate more space. |
| `collapsed_length_minimum` | array | Provide the minimum length measurement of the item without any extensions. |
| `natural_variation_type` | array | Provide the types of imperfections and unique characteristics found in the natural material of the table, contributing to its individuality. |
| `unextended_seating_capacity` | array | Provide the number of seats the item has when not extended, for items that can expand to accommodate more seating. |
| `umbrella_hole_diameter` | array | Provide the diameter of the item's umbrella hole. An umbrella hole is designed to hold an umbrella for shade or decoration. |
| `includes_all_assembly_tools` | array | Provide whether or not all the tools required for assembling the item are included. |
| `base_to_top_distance` | array | Provide the distance from the top of the base to the underside of the top surface of the item. |
| `bench_quantity` | array | Provide the number of benches included with the item. Benches are long seats on which multiple people may sit on at the same time. |
| `set_name` | array | Provide the manufacturer's official name for the product set. If no official name exists, summarize the type and number of its components. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `safety_warning` | array | List safety information customers should know. |
| `country_of_origin` | array | The country in which the product was published. |
| `warranty_description` | array | Describe the warranty. |
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
| `item_weight` | array | A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point. Please use decimal points, commas are not accepted. |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `fcc_radio_frequency_emission_compliance` | array | Provide details on compliance to FCC regulations for products that may emit radio frequencies. |
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

### edge_style

Provide the style of the edge of the item

**Type:** array

**Examples:**

- `Plain`

### item_type_keyword

What is the item that you are selling?

**Type:** array

**Examples:**

- `Dining tables`

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

The full name of the publisher who issued the product

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

### special_feature

An additional text field where you can indicate any additional relevant product information.

**Type:** array

**Examples:**

- `Floating`

### style

The style of the item

**Type:** array

**Examples:**

- `Mission; Art Deco; Jack Purcell`

### age_range_description

Provide the age group the item is suitable for, describing who can safely use or interact with it.

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

### item_diameter

Provide the width across the item's circular top, the distance from one side to the other through the center.

**Type:** array

**Examples:**

- `5 inches`

### part_number

For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number.

**Type:** array

**Examples:**

- `LE`

### warranty_type

Enter the type of warranty for this item

**Type:** array

**Examples:**

- `Manufacturer`

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

### is_resizable

If the item is resizable select yes, if it is not select no

**Type:** array

**Examples:**

- `Yes, No`

### ring

The attribute indicates Ring of the product

**Type:** array

**Examples:**

- `One Size`

### care_instructions

Provide instructions related to how to care for the item

**Type:** array

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

### paper_size

Specify the size of the paper

**Type:** array

**Examples:**

- `6 x 5 Millimeters, 8 1/2 x 11 Inches`

### line_size

Provide the product's line or point size

**Type:** array

**Examples:**

- `0.5 Millimeters, 1.0 Millimeters`

### hardware_platform

Provide the product's hardware platform

**Type:** array

**Examples:**

- `Xbox, PlayStation`

### platform_for_display

Provide the platform associated with the product.

**Type:** array

**Examples:**

- `Android, Mac, PC`

### language

Select the appropriate language from the list of valid values

**Type:** array

**Examples:**

- `English`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `type`

### is_customizable

Is customizable?

**Type:** array

**Examples:**

- `Yes`

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

### number_of_doors

Provide the number of doors the product has

**Type:** array

**Examples:**

- `1`

### is_foldable

Provide whether the structural feature of the product can be folded or not.

**Type:** array

**Examples:**

- `Yes`

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

### assembly_instructions

Provide the step-by-step directions needed for a user to assemble the product.

**Type:** array

**Examples:**

- `Position columns into holes of base and push in until snap buttons lock in place`

### feet_type

The type of feet on the item

**Type:** array

**Examples:**

- `Self-Levelling`

### access_method

Provide the access method

**Type:** array

**Examples:**

- `example text goes here`

### furniture_finish

the finish of furniture

**Type:** array

**Examples:**

- `Oak`

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

### base_type

Provide the type of base the product has or uses

**Type:** array

**Examples:**

- `Pedestal`

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

Provide the name of the sports team associated with the furniture item, indicating the team-themed design or branding.

**Type:** array

**Examples:**

- `Seattle Seahawks`

### athlete

Name of athlete participating in the event

**Type:** array

**Examples:**

- `Michael Jordan`

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Examples:**

- `Record Player`

### is_fragile

Is the item fragile?

**Type:** array

**Examples:**

- `TRUE`

### scent

Provide a description of the scent of the item

**Type:** array

### is_stain_resistant

Is the item made of a stain resistant material or has it been treated to be stain resistant

**Type:** array

### base

Enter the specifications for the base

**Type:** array

**Examples:**

- `Stainless Steel`

### has_tilting

Provide whether the item can change its angle or orientation, allowing adjustment of viewing or positioning.

**Type:** array

**Examples:**

- `Yes,No`

### length_range

Length range for blinds

**Type:** array

**Examples:**

- `24-60" long`

### maximum_lifting_height

Provide the maximum lifting height

**Type:** array

**Examples:**

- `1.4 Inches, 8 Feet`

### room_type

Provide the type of room the table is designed for, influencing its size, features, and aesthetics.

**Type:** array

**Examples:**

- `Bedroom`

### shelf

The attribute indicates Shelf of the product

**Type:** array

**Examples:**

- `Meters`

### top

The attribute indicates Top of the product

**Type:** array

**Examples:**

- `Ash Wood`

### width_range

Width range for blinds

**Type:** array

**Examples:**

- `24-60" wide`

### extended_length

Enter the length of the item when extended. Do not include modifier.

**Type:** array

**Examples:**

- `Example goes here`

### maximum_weight_recommendation

Provide the highest weight the item can safely support, the maximum load it can bear without issues.

**Type:** array

**Examples:**

- `20.0 Pounds, 350.0 Kilograms`

### number_of_height_positions

Specify the number of height positions

**Type:** array

**Examples:**

- `3`

### minimum_required_door_width

Provide the minimum width of a doorway needed for the piece of furniture to fit through. This information is typically used as a measurement for delivery.

**Type:** array

**Examples:**

- `36.0 Inches`

### furniture_leg

Describes the furniture item's legs

**Type:** array

**Examples:**

- `Straight, Fluted, Tapered`

### indoor_outdoor_usage

Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor.

**Type:** array

**Examples:**

- `Indoor`

### table_design

Provide the design type of the table. The table design represents a standard form of the table based around the specific user needs for example the structure of the surface.

**Type:** array

**Examples:**

- `Console Table, Dining Table, End Table`

### item_length_width_height

Provide the length, width and height of the item in ready to use condition.

**Type:** array

**Examples:**

- `100 Inches`

### furniture_base_movement

Provide the way the item's base allows it to move, enabling stability and mobility, like gliding or swiveling.

**Type:** array

**Examples:**

- `Glide, Rock, Swivel`

### decorative_plating

Provide the decorative metal coating on the item, used to enhance appearance, prevent corrosion, or improve durability.

**Type:** array

**Examples:**

- `Rose Gold, Rhodium`

### item_depth_width_height

Provide the dimensions of the item when ready for use, like a fully unrolled rug or blanket, excluding packaging.

**Type:** array

**Examples:**

- `40 Inches`

### item_width

Provide the width of the item in ready to use condition.

**Type:** array

**Examples:**

- `92.0 Centimeters`

### tabletop_thickness

Provide the dimensional thickness of the product's tabletop. A tabletop is the raised flat surface on top of a furniture table.

**Type:** array

**Examples:**

- `1.5 Inches`

### recommended_number_of_people_for_assembly

Provide the amount of people recommended to assemble the item.

**Type:** array

**Examples:**

- `2`

### ground_to_item_distance

Provide the distance from ground to item (clearance), measured from the lowest point (excluding feet/legs) to the surface it rests on.

**Type:** array

**Examples:**

- `12.6 Inches`

### tools_recommended_for_assembly

Provide the type of tools recommended to assemble the components of the item.

**Type:** array

**Examples:**

- `Hammer`

### number_of_leaves

Provide the number of leaves included with this item. Leaves are additional tabletop pieces used to expand the size of the table.

**Type:** array

**Examples:**

- `2`

### table_extension_mechanism

Provide the method used to increase the table's surface area when needed, such as expanding or adding sections to accommodate more space.

**Type:** array

**Examples:**

- `Butterfly Leaf`

### collapsed_length_minimum

Provide the minimum length measurement of the item without any extensions.

**Type:** array

**Examples:**

- `20 Inches`

### natural_variation_type

Provide the types of imperfections and unique characteristics found in the natural material of the table, contributing to its individuality.

**Type:** array

**Examples:**

- `Burl Patterns`

### unextended_seating_capacity

Provide the number of seats the item has when not extended, for items that can expand to accommodate more seating.

**Type:** array

**Examples:**

- `6`

### umbrella_hole_diameter

Provide the diameter of the item's umbrella hole. An umbrella hole is designed to hold an umbrella for shade or decoration.

**Type:** array

**Examples:**

- `3 Inches`

### includes_all_assembly_tools

Provide whether or not all the tools required for assembling the item are included.

**Type:** array

**Examples:**

- `Yes`

### base_to_top_distance

Provide the distance from the top of the base to the underside of the top surface of the item.

**Type:** array

**Examples:**

- `4.33 Inches`

### bench_quantity

Provide the number of benches included with the item. Benches are long seats on which multiple people may sit on at the same time.

**Type:** array

**Examples:**

- `2`

### set_name

Provide the manufacturer's official name for the product set. If no official name exists, summarize the type and number of its components.

**Type:** array

**Examples:**

- `Strata Ultimate Golf Club Set (16 Piece)`

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

A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point. Please use decimal points, commas are not accepted.

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

