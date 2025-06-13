# DESK Schema Documentation

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
- `drawer_weight_capacity` - Required when selectors `marketplace_id`, `type` are specified
- `drawer_interior_dimensions` - Required when selectors `marketplace_id`, `type` are specified
- `cabinet_interior_dimensions` - Required when selectors `marketplace_id`, `type` are specified
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
- `target_gender.value` - Required when `target_gender` is provided
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
- `warranty_type.value` - Required when `warranty_type` is provided
- `warranty_type.language_tag` - Required when `warranty_type` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `care_instructions.value` - Required when `care_instructions` is provided
- `care_instructions.language_tag` - Required when `care_instructions` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `platform_for_display.value` - Required when `platform_for_display` is provided
- `platform_for_display.language_tag` - Required when `platform_for_display` is provided
- `language.type` - Required when `language` is provided
- `language.value` - Required when `language` is provided
- `lock_type.value` - Required when `lock_type` is provided
- `lock_type.language_tag` - Required when `lock_type` is provided
- `is_customizable.value` - Required when `is_customizable` is provided
- `storage_volume.value` - Required when `storage_volume` is provided
- `storage_volume.unit` - Required when `storage_volume` is provided
- `is_assembly_required.value` - Required when `is_assembly_required` is provided
- `number_of_shelves.value` - Required when `number_of_shelves` is provided
- `number_of_shelves.language_tag` - Required when `number_of_shelves` is provided
- `drawer_type.value` - Required when `drawer_type` is provided
- `drawer_type.language_tag` - Required when `drawer_type` is provided
- `number_of_drawers.value` - Required when `number_of_drawers` is provided
- `assembly_instructions.value` - Required when `assembly_instructions` is provided
- `assembly_instructions.language_tag` - Required when `assembly_instructions` is provided
- `lifting_mechanism.value` - Required when `lifting_mechanism` is provided
- `lifting_mechanism.language_tag` - Required when `lifting_mechanism` is provided
- `furniture_finish.value` - Required when `furniture_finish` is provided
- `furniture_finish.language_tag` - Required when `furniture_finish` is provided
- `product_grade.value` - Required when `product_grade` is provided
- `product_grade.language_tag` - Required when `product_grade` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `mounting_type.value` - Required when `mounting_type` is provided
- `mounting_type.language_tag` - Required when `mounting_type` is provided
- `maximum_tilt_angle.value` - Required when `maximum_tilt_angle` is provided
- `maximum_tilt_angle.unit` - Required when `maximum_tilt_angle` is provided
- `finish_type.value` - Required when `finish_type` is provided
- `finish_type.language_tag` - Required when `finish_type` is provided
- `base_type.value` - Required when `base_type` is provided
- `base_type.language_tag` - Required when `base_type` is provided
- `item_form.value` - Required when `item_form` is provided
- `item_form.language_tag` - Required when `item_form` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `included_components.value` - Required when `included_components` is provided
- `included_components.language_tag` - Required when `included_components` is provided
- `recommended_uses_for_product.value` - Required when `recommended_uses_for_product` is provided
- `recommended_uses_for_product.language_tag` - Required when `recommended_uses_for_product` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `is_electric.value` - Required when `is_electric` is provided
- `is_ul_listed.value` - Required when `is_ul_listed` is provided
- `length_range.value` - Required when `length_range` is provided
- `length_range.language_tag` - Required when `length_range` is provided
- `room_type.value` - Required when `room_type` is provided
- `room_type.language_tag` - Required when `room_type` is provided
- `width_range.value` - Required when `width_range` is provided
- `width_range.language_tag` - Required when `width_range` is provided
- `maximum_compatible_number_of_seats.value` - Required when `maximum_compatible_number_of_seats` is provided
- `maximum_weight_recommendation.value` - Required when `maximum_weight_recommendation` is provided
- `maximum_weight_recommendation.unit` - Required when `maximum_weight_recommendation` is provided
- `number_of_height_positions.value` - Required when `number_of_height_positions` is provided
- `desk_design.value` - Required when `desk_design` is provided
- `item_depth_width_height.depth` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.height` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.width` - Required when `item_depth_width_height` is provided
- `tabletop_thickness.value` - Required when `tabletop_thickness` is provided
- `tabletop_thickness.unit` - Required when `tabletop_thickness` is provided
- `recommended_number_of_people_for_assembly.value` - Required when `recommended_number_of_people_for_assembly` is provided
- `tools_recommended_for_assembly.value` - Required when `tools_recommended_for_assembly` is provided
- `number_of_leaves.value` - Required when `number_of_leaves` is provided
- `drawer_weight_capacity.type` - Required when `drawer_weight_capacity` is provided
- `drawer_weight_capacity.unit_decimal` - Required when `drawer_weight_capacity` is provided
- `has_finished_back.value` - Required when `has_finished_back` is provided
- `number_of_cabinets.value` - Required when `number_of_cabinets` is provided
- `distressed_finish_type.value` - Required when `distressed_finish_type` is provided
- `distressed_finish_type.language_tag` - Required when `distressed_finish_type` is provided
- `natural_variation_type.value` - Required when `natural_variation_type` is provided
- `natural_variation_type.language_tag` - Required when `natural_variation_type` is provided
- `number_of_enclosed_shelves.value` - Required when `number_of_enclosed_shelves` is provided
- `number_of_open_shelves.value` - Required when `number_of_open_shelves` is provided
- `working_surface_length_width.length` - Required when `working_surface_length_width` is provided
- `working_surface_length_width.width` - Required when `working_surface_length_width` is provided
- `drawer_pedestal_count.value` - Required when `drawer_pedestal_count` is provided
- `includes_all_assembly_tools.value` - Required when `includes_all_assembly_tools` is provided
- `drawer_interior_dimensions.depth` - Required when `drawer_interior_dimensions` is provided
- `drawer_interior_dimensions.height` - Required when `drawer_interior_dimensions` is provided
- `drawer_interior_dimensions.type` - Required when `drawer_interior_dimensions` is provided
- `drawer_interior_dimensions.width` - Required when `drawer_interior_dimensions` is provided
- `cabinet_interior_dimensions.depth` - Required when `cabinet_interior_dimensions` is provided
- `cabinet_interior_dimensions.height` - Required when `cabinet_interior_dimensions` is provided
- `cabinet_interior_dimensions.type` - Required when `cabinet_interior_dimensions` is provided
- `cabinet_interior_dimensions.width` - Required when `cabinet_interior_dimensions` is provided
- `working_surface_diagonal_length.value` - Required when `working_surface_diagonal_length` is provided
- `working_surface_diagonal_length.unit` - Required when `working_surface_diagonal_length` is provided
- `storage_options.value` - Required when `storage_options` is provided
- `storage_options.language_tag` - Required when `storage_options` is provided
- `knee_space_dimensions.depth` - Required when `knee_space_dimensions` is provided
- `knee_space_dimensions.height` - Required when `knee_space_dimensions` is provided
- `knee_space_dimensions.width` - Required when `knee_space_dimensions` is provided
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
- `mfg_warranty_description_type.value` - Required when `mfg_warranty_description_type` is provided
- `mfg_warranty_description_type.language_tag` - Required when `mfg_warranty_description_type` is provided
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
- `maximum_height.value` - Required when `maximum_height` is provided
- `maximum_height.unit` - Required when `maximum_height` is provided
- `item_display_weight.value` - Required when `item_display_weight` is provided
- `item_display_weight.unit` - Required when `item_display_weight` is provided
- `minimum_height.value` - Required when `minimum_height` is provided
- `minimum_height.unit` - Required when `minimum_height` is provided
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
| `item_type_keyword` | array | Provide the specific type of desk, indicating its primary purpose or design features that distinguish it from other desk varieties. |
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
| `target_gender` | array | Provide the intended gender for whom the item is designed, indicating its style, size, or other gender-specific features. |
| `age_range_description` | array | Provide the age group the item is suitable for, describing who can comfortably use it based on size and design. |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `warranty_type` | array | Enter the type of warranty for this item |
| `item_shape` | array | The shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `care_instructions` | array | Provide instructions related to how to care for the item |
| `frame` | array | The attribute indicates the Frame of the product |
| `edition` | array | Provide the version or edition of the item |
| `platform_for_display` | array | Provide the platform associated with the product. |
| `language` | array | Select the appropriate language from the list of valid values |
| `lock_type` | array | Lock |
| `is_customizable` | array | Is customizable? |
| `storage_volume` | array | Provide the volume capacity the item has available to store contents. |
| `is_assembly_required` | array | Indicate whether or not the item requires assembly by the customer |
| `number_of_shelves` | array | Number of Shelves |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `drawer_type` | array | Describes the drawer(s) on the product. |
| `number_of_drawers` | array | Provide the number of drawers that the item has |
| `assembly_instructions` | array | Provide the step-by-step directions needed for a user to assemble the product. |
| `lifting_mechanism` | array | Provide the method used to raise or lower the desk, indicating how the height can be adjusted for user comfort and ergonomics. |
| `furniture_finish` | array | the finish of furniture |
| `product_grade` | array | Provide the intended use or quality level of the item, indicating its durability and purpose, like for heavy-duty or casual use. |
| `customer_package_type` | array | Provide the products package type |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `mounting_type` | array | Provide the type of mount the desk has or is intended for, indicating how it can be attached or secured in place. |
| `maximum_tilt_angle` | array | Indicates maximum tilt angle. |
| `finish_type` | array | Indicate the external appearance of the product once applied |
| `base_type` | array | Provide the style or structure of the desk's supporting foundation, which affects its stability, appearance, and functionality. |
| `item_form` | array | Provide a value that represents the form of the item |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `included_components` | array | Which components are included? |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `scent` | array | Provide a description of the scent of the item |
| `base` | array | Enter the specifications for the base |
| `is_electric` | array | Item is powered by electricity |
| `is_ul_listed` | array | Provide whether the item meets safety standards set by Underwriters Laboratories, ensuring safe usage. |
| `length_range` | array | Length range for blinds |
| `room_type` | array | Provide the type of room the item is intended for, such as a study, office, or bedroom. |
| `shelf` | array | The attribute indicates Shelf of the product |
| `top` | array | The attribute indicates Top of the product |
| `width_range` | array | Width range for blinds |
| `maximum_compatible_number_of_seats` | array | Specify the maximum compatible number of seats |
| `maximum_weight_recommendation` | array | Provide the highest weight the item can safely hold, the maximum load it can support without issues. |
| `number_of_height_positions` | array | Provide the quantity of available height settings for the desk, indicating the adjustability of the work surface. |
| `furniture_leg` | array | Describes the furniture item's legs |
| `desk_design` | array | Provide the design of the desk. The desk design represents the standard form and function of the desk to create work and storage space to meet the user's needs. |
| `item_depth_width_height` | array | Provide the dimensions of the item when fully set up and ready to use, including depth, width, and height. |
| `tabletop_thickness` | array | Provide the dimensional thickness of the product's tabletop. A tabletop is the raised flat surface on top of a furniture table. |
| `recommended_number_of_people_for_assembly` | array | Provide the amount of people recommended to assemble the item. |
| `tools_recommended_for_assembly` | array | Provide the type of tools recommended to assemble the components of the item. |
| `number_of_leaves` | array | Provide the number of leaves included with this item. Leaves are additional tabletop pieces used to expand the size of the table. |
| `drawer` | array | Provide the specifications of an item's drawer, a varying-sized compartment that opens to reveal contents and closes when not in use. |
| `drawer_weight_capacity` | array | Provide the maximum weight capacity that a single drawer within a dresser, a desk, or a storage drawer unit can support without being damaged. |
| `has_finished_back` | array | Provide whether the back of the item is polished and finished like the front, for a consistent look from all sides. |
| `number_of_cabinets` | array | Provide the number of cabinets that are included with the product. |
| `distressed_finish_type` | array | Provide the surface treatment that gives the desk a worn or aged appearance, such as intentional weathering or natural wear. |
| `natural_variation_type` | array | Provide the types of natural imperfections and unique characteristics in the desk's material, such as wood grains or color variations. |
| `number_of_enclosed_shelves` | array | Provide the number of enclosed shelves the item has. The number of enclosed shelves is the quantity of shelves behind doors or panels. |
| `number_of_open_shelves` | array | Provide the number of open shelves the item has. The number of open shelves is the quantity of shelves not enclosed behind doors. |
| `working_surface_length_width` | array | Provide the measurement of the length and width of the working surface of the item in assembled, unextended condition. |
| `drawer_pedestal_count` | array | Provide the number of small cabinets with stacked drawers that support the desk's work surface. |
| `includes_all_assembly_tools` | array | Provide whether or not all the tools required for assembling the item are included. |
| `hutch` | array | Provide details on the hutch included with the item. A hutch is a set of shelves or cabinets placed on top of a lower unit. |
| `keyboard_tray` | array | The attribute indicates the Keyboard Tray of the item. |
| `cabinet` | array | Cabinet describes the specifications of the cabinet included with the item. |
| `drawer_interior_dimensions` | array | Provide the measurement of the product's single drawer interior dimensions in depth, width and height in an assembled state. |
| `cabinet_interior_dimensions` | array | Provide the interior dimensions of each cabinet included with the item in depth, width, and height in an assembled state. |
| `desk_return_dimensions` | array | Provide the measurement of depth, width and height of the item's desk return in ready to use condition. |
| `working_surface_diagonal_length` | array | Provide the working surface diagonal length, which refers to the distance from one corner of a working surface to the opposite corner. |
| `storage_options` | array | Provide the different ways the item can store goods, like drawers or shelves, for keeping things organized and accessible. |
| `knee_space_dimensions` | array | Provide the knee space dimensions of the item which defines leg clearance and comfortable leg movement when seated. |
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
| `item_weight` | array | A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point. Please use decimal points, commas are not accepted. |
| `mfg_warranty_description_type` | array | Provide the details on the warranty coverage provided by the manufacturer for the item, explaining what is covered and for how long. |
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
| `maximum_height` | array | Provide the maximum height of the product |
| `item_display_weight` | array | Provide the item weight if the product is a solid |
| `minimum_height` | array | Enter the minimum height. |
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

Provide the specific type of desk, indicating its primary purpose or design features that distinguish it from other desk varieties.

**Type:** array

**Examples:**

- `Home office desks`

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

- `max number of images 36,  Operating Time 6 hours`

### style

The style of the item

**Type:** array

**Examples:**

- `Mission; Art Deco; Jack Purcell`

### target_gender

Provide the intended gender for whom the item is designed, indicating its style, size, or other gender-specific features.

**Type:** array

**Examples:**

- `Female`

### age_range_description

Provide the age group the item is suitable for, describing who can comfortably use it based on size and design.

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

### lock_type

Lock

**Type:** array

**Examples:**

- `No`

### is_customizable

Is customizable?

**Type:** array

**Examples:**

- `Yes`

### storage_volume

Provide the volume capacity the item has available to store contents.

**Type:** array

**Examples:**

- `20.0 Liters, 5.3 Gallons`

### is_assembly_required

Indicate whether or not the item requires assembly by the customer

**Type:** array

**Examples:**

- `Yes`

### number_of_shelves

Number of Shelves

**Type:** array

**Examples:**

- `One Full`

### item_display_dimensions

Provide the dimensions of the product, without packaging and fully assembled

**Type:** array

**Examples:**

- `5.7 Inches x 3.5 Inches x 1.8 Inches`

### drawer_type

Describes the drawer(s) on the product.

**Type:** array

**Examples:**

- `Storage, Warming`

### number_of_drawers

Provide the number of drawers that the item has

**Type:** array

**Examples:**

- `7`

### assembly_instructions

Provide the step-by-step directions needed for a user to assemble the product.

**Type:** array

**Examples:**

- `Position columns into holes of base and push in until snap buttons lock in place`

### lifting_mechanism

Provide the method used to raise or lower the desk, indicating how the height can be adjusted for user comfort and ergonomics.

**Type:** array

**Examples:**

- `Manual, Pneumatic, Electrical`

### furniture_finish

the finish of furniture

**Type:** array

**Examples:**

- `Oak`

### product_grade

Provide the intended use or quality level of the item, indicating its durability and purpose, like for heavy-duty or casual use.

**Type:** array

**Examples:**

- `Replacement Parts`

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

Provide the type of mount the desk has or is intended for, indicating how it can be attached or secured in place.

**Type:** array

**Examples:**

- `Clevis`

### maximum_tilt_angle

Indicates maximum tilt angle.

**Type:** array

**Examples:**

- `60.0 °`

### finish_type

Indicate the external appearance of the product once applied

**Type:** array

### base_type

Provide the style or structure of the desk's supporting foundation, which affects its stability, appearance, and functionality.

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

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Examples:**

- `Cycling`

### scent

Provide a description of the scent of the item

**Type:** array

### base

Enter the specifications for the base

**Type:** array

**Examples:**

- `Stainless Steel`

### is_electric

Item is powered by electricity

**Type:** array

**Examples:**

- `Yes`

### is_ul_listed

Provide whether the item meets safety standards set by Underwriters Laboratories, ensuring safe usage.

**Type:** array

**Examples:**

- `Yes`

### length_range

Length range for blinds

**Type:** array

**Examples:**

- `24-60" long`

### room_type

Provide the type of room the item is intended for, such as a study, office, or bedroom.

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

### maximum_compatible_number_of_seats

Specify the maximum compatible number of seats

**Type:** array

**Examples:**

- `10`

### maximum_weight_recommendation

Provide the highest weight the item can safely hold, the maximum load it can support without issues.

**Type:** array

**Examples:**

- `20.0 Pounds, 350.0 Kilograms`

### number_of_height_positions

Provide the quantity of available height settings for the desk, indicating the adjustability of the work surface.

**Type:** array

**Examples:**

- `3`

### furniture_leg

Describes the furniture item's legs

**Type:** array

**Examples:**

- `Straight, Fluted, Tapered`

### desk_design

Provide the design of the desk. The desk design represents the standard form and function of the desk to create work and storage space to meet the user's needs.

**Type:** array

**Examples:**

- `Executive Desk, Armoire Desk, Computer Desk`

### item_depth_width_height

Provide the dimensions of the item when fully set up and ready to use, including depth, width, and height.

**Type:** array

**Examples:**

- `40 Inches`

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

### drawer

Provide the specifications of an item's drawer, a varying-sized compartment that opens to reveal contents and closes when not in use.

**Type:** array

**Examples:**

- `Ball Bearing Glide, Metal`

### drawer_weight_capacity

Provide the maximum weight capacity that a single drawer within a dresser, a desk, or a storage drawer unit can support without being damaged.

**Type:** array

**Examples:**

- `Large, 4 Kilograms`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `type`

### has_finished_back

Provide whether the back of the item is polished and finished like the front, for a consistent look from all sides.

**Type:** array

**Examples:**

- `TRUE`

### number_of_cabinets

Provide the number of cabinets that are included with the product.

**Type:** array

**Examples:**

- `4`

### distressed_finish_type

Provide the surface treatment that gives the desk a worn or aged appearance, such as intentional weathering or natural wear.

**Type:** array

**Examples:**

- `Chipped`

### natural_variation_type

Provide the types of natural imperfections and unique characteristics in the desk's material, such as wood grains or color variations.

**Type:** array

**Examples:**

- `Burl Patterns`

### number_of_enclosed_shelves

Provide the number of enclosed shelves the item has. The number of enclosed shelves is the quantity of shelves behind doors or panels.

**Type:** array

**Examples:**

- `4`

### number_of_open_shelves

Provide the number of open shelves the item has. The number of open shelves is the quantity of shelves not enclosed behind doors.

**Type:** array

**Examples:**

- `4`

### working_surface_length_width

Provide the measurement of the length and width of the working surface of the item in assembled, unextended condition.

**Type:** array

**Examples:**

- `Length: 42 Inches, Width:36 Inches`

### drawer_pedestal_count

Provide the number of small cabinets with stacked drawers that support the desk's work surface.

**Type:** array

**Examples:**

- `4`

### includes_all_assembly_tools

Provide whether or not all the tools required for assembling the item are included.

**Type:** array

**Examples:**

- `Yes`

### hutch

Provide details on the hutch included with the item. A hutch is a set of shelves or cabinets placed on top of a lower unit.

**Type:** array

**Examples:**

- `Wood, Depth: 6.375 Inches, Width: 45 Inches, Height: 5.75 Inches`

### keyboard_tray

The attribute indicates the Keyboard Tray of the item.

**Type:** array

**Examples:**

- `Length: 17.9 Inches
Width: 7.7 Inches`

### cabinet

Cabinet describes the specifications of the cabinet included with the item.

**Type:** array

**Examples:**

- `Cabinet Configuration: Built-In`

### drawer_interior_dimensions

Provide the measurement of the product's single drawer interior dimensions in depth, width and height in an assembled state.

**Type:** array

**Examples:**

- `Large, Depth: 5.75 Inches, Width: 38.625 Inches, Height: 6.375 Inches`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `type`

### cabinet_interior_dimensions

Provide the interior dimensions of each cabinet included with the item in depth, width, and height in an assembled state.

**Type:** array

**Examples:**

- `Cabinet 1, Depth: 16.1 Inches, Width: 12.4, Height: 12 Inches`

**Conditionally Required**

**Conditionally Required based on selectors:** `marketplace_id`, `type`

### desk_return_dimensions

Provide the measurement of depth, width and height of the item's desk return in ready to use condition.

**Type:** array

**Examples:**

- `Depth: 15.5 Inches, Width: 47.25 Inches, Height: 27.5 Inches`

### working_surface_diagonal_length

Provide the working surface diagonal length, which refers to the distance from one corner of a working surface to the opposite corner.

**Type:** array

**Examples:**

- `30 Inches`

### storage_options

Provide the different ways the item can store goods, like drawers or shelves, for keeping things organized and accessible.

**Type:** array

**Examples:**

- `Drawer`

### knee_space_dimensions

Provide the knee space dimensions of the item which defines leg clearance and comfortable leg movement when seated.

**Type:** array

**Examples:**

- `18 Inches`

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

A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point. Please use decimal points, commas are not accepted.

**Type:** array

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

### mfg_warranty_description_type

Provide the details on the warranty coverage provided by the manufacturer for the item, explaining what is covered and for how long.

**Type:** array

**Examples:**

- `Yearly`

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

### maximum_height

Provide the maximum height of the product

**Type:** array

**Examples:**

- `8.0 Feet`

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

### minimum_height

Enter the minimum height.

**Type:** array

**Examples:**

- `3.1 Inches, 91.0 Centimeters`

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

