# SOFA Schema Documentation

**Schema Version:** https://schemas.amazon.com/selling-partners/definitions/product-types/meta-schema/v1

## Required Fields

- `brand`
- `bullet_point`
- `country_of_origin`
- `fabric_type`
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
- `subject_character.value` - Required when `subject_character` is provided
- `subject_character.language_tag` - Required when `subject_character` is provided
- `color.language_tag` - Required when `color` is provided
- `size.value` - Required when `size` is provided
- `size.language_tag` - Required when `size` is provided
- `number_of_pieces.value` - Required when `number_of_pieces` is provided
- `part_number.value` - Required when `part_number` is provided
- `collection.value` - Required when `collection` is provided
- `collection.language_tag` - Required when `collection` is provided
- `warranty_type.value` - Required when `warranty_type` is provided
- `warranty_type.language_tag` - Required when `warranty_type` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `care_instructions.value` - Required when `care_instructions` is provided
- `care_instructions.language_tag` - Required when `care_instructions` is provided
- `manufacturer_grade.value` - Required when `manufacturer_grade` is provided
- `manufacturer_grade.language_tag` - Required when `manufacturer_grade` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `is_customizable.value` - Required when `is_customizable` is provided
- `material_feature.value` - Required when `material_feature` is provided
- `material_feature.language_tag` - Required when `material_feature` is provided
- `is_assembly_required.value` - Required when `is_assembly_required` is provided
- `item_firmness_description.value` - Required when `item_firmness_description` is provided
- `item_firmness_description.language_tag` - Required when `item_firmness_description` is provided
- `fill_material.value` - Required when `fill_material` is provided
- `fill_material.language_tag` - Required when `fill_material` is provided
- `assembly_instructions.value` - Required when `assembly_instructions` is provided
- `assembly_instructions.language_tag` - Required when `assembly_instructions` is provided
- `seating_capacity.value` - Required when `seating_capacity` is provided
- `specification_met.value` - Required when `specification_met` is provided
- `specification_met.language_tag` - Required when `specification_met` is provided
- `suspension_type.value` - Required when `suspension_type` is provided
- `suspension_type.language_tag` - Required when `suspension_type` is provided
- `orientation.value` - Required when `orientation` is provided
- `orientation.language_tag` - Required when `orientation` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `item_density.value` - Required when `item_density` is provided
- `item_density.unit` - Required when `item_density` is provided
- `item_form.value` - Required when `item_form` is provided
- `item_form.language_tag` - Required when `item_form` is provided
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
- `is_fragile.value` - Required when `is_fragile` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `hand_orientation.value` - Required when `hand_orientation` is provided
- `hand_orientation.language_tag` - Required when `hand_orientation` is provided
- `cushion_style.value` - Required when `cushion_style` is provided
- `cushion_style.language_tag` - Required when `cushion_style` is provided
- `embellishment_feature.value` - Required when `embellishment_feature` is provided
- `embellishment_feature.language_tag` - Required when `embellishment_feature` is provided
- `fire_rating.value` - Required when `fire_rating` is provided
- `fire_rating.language_tag` - Required when `fire_rating` is provided
- `length_range.value` - Required when `length_range` is provided
- `length_range.language_tag` - Required when `length_range` is provided
- `room_type.value` - Required when `room_type` is provided
- `room_type.language_tag` - Required when `room_type` is provided
- `width_range.value` - Required when `width_range` is provided
- `width_range.language_tag` - Required when `width_range` is provided
- `number_of_height_positions.value` - Required when `number_of_height_positions` is provided
- `minimum_required_door_width.value` - Required when `minimum_required_door_width` is provided
- `minimum_required_door_width.unit` - Required when `minimum_required_door_width` is provided
- `seat_recline.operation_mode` - Required when `seat_recline` is provided
- `sofa_type.value` - Required when `sofa_type` is provided
- `indoor_outdoor_usage.value` - Required when `indoor_outdoor_usage` is provided
- `item_depth_width_height.depth` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.height` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.width` - Required when `item_depth_width_height` is provided
- `seat_back_fill_material.value` - Required when `seat_back_fill_material` is provided
- `number_of_cup_holders.value` - Required when `number_of_cup_holders` is provided
- `reclined_length.value` - Required when `reclined_length` is provided
- `reclined_length.unit` - Required when `reclined_length` is provided
- `recommended_number_of_people_for_assembly.value` - Required when `recommended_number_of_people_for_assembly` is provided
- `furniture_wall_clearance.value` - Required when `furniture_wall_clearance` is provided
- `furniture_wall_clearance.unit` - Required when `furniture_wall_clearance` is provided
- `component_connector_assembly.value` - Required when `component_connector_assembly` is provided
- `tools_recommended_for_assembly.value` - Required when `tools_recommended_for_assembly` is provided
- `sleeping_area_dimensions.height` - Required when `sleeping_area_dimensions` is provided
- `sleeping_area_dimensions.length` - Required when `sleeping_area_dimensions` is provided
- `sleeping_area_dimensions.width` - Required when `sleeping_area_dimensions` is provided
- `seat_cushion_configuration.value` - Required when `seat_cushion_configuration` is provided
- `includes_all_assembly_tools.value` - Required when `includes_all_assembly_tools` is provided
- `reclining_seat_count.value` - Required when `reclining_seat_count` is provided
- `reclining_position_count.value` - Required when `reclining_position_count` is provided
- `reclining_position_count.language_tag` - Required when `reclining_position_count` is provided
- `cushion_construction.value` - Required when `cushion_construction` is provided
- `cushion_construction.language_tag` - Required when `cushion_construction` is provided
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
- `item_display_weight.value` - Required when `item_display_weight` is provided
- `item_display_weight.unit` - Required when `item_display_weight` is provided
- `master_pack_layers_per_pallet_quantity.value` - Required when `master_pack_layers_per_pallet_quantity` is provided
- `master_packs_per_layer_quantity.value` - Required when `master_packs_per_layer_quantity` is provided

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `item_name` | array | Provide a title for the item including brand name, material, sofa type, product type and color if available |
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
| `product_description` | array | The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum. |
| `bullet_point` | array | Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description. |
| `generic_keyword` | array | Provide specific search terms to help customers find your product. |
| `special_feature` | array | An additional text field where you can indicate any additional relevant product information. |
| `style` | array | The style of the item |
| `age_range_description` | array | Provide the age range for which the sofa is intended or appropriate, helping customers choose suitable seating for different age groups. |
| `material` | array | What material is the product made out of? |
| `fabric_type` | array | List all fabrics separated by ','. Indicate with % composition. Always add "Viscose" or "Rayon" instead of "Bamboo", and "Azlon" for Soy |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `subject_character` | array | Provide the primary character the item represents |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `number_of_pieces` | array | Number of pieces |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `collection` | array | Enter the name of collection that an item belongs to. |
| `warranty_type` | array | Enter the type of warranty for this item |
| `item_shape` | array | The shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `care_instructions` | array | Provide instructions related to how to care for the item |
| `arm` | array | Enter the specifications for the arm |
| `frame` | array | The attribute indicates the Frame of the product |
| `manufacturer_grade` | array | Enter the manufacturer grade |
| `configuration` | array | Indicate the configuration of the item |
| `is_customizable` | array | Is customizable? |
| `material_feature` | array | Provide the key material properties of the item, such as fabric type, texture, and durability characteristics. |
| `is_assembly_required` | array | Indicate whether or not the item requires assembly by the customer |
| `item_firmness_description` | array | Provide the cushion firmness level for the item, how soft or firm the seating feels, affecting comfort and support. |
| `fill_material` | array | Provide the material used to fill the interior of the item. |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `assembly_instructions` | array | Provide the step-by-step directions needed for a user to assemble the product. |
| `seating_capacity` | array | Provide the maximum number of people the item can seat. |
| `specification_met` | array | Provide the standards or guidelines the item meets, ensuring quality and safety for intended use. |
| `suspension_type` | array | Provide the suspenion typoe of the product |
| `orientation` | array | Provide the direction the item is facing or positioned, its layout or arrangement. |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `item_density` | array | Enter the item density. Do not include a modifier. |
| `item_form` | array | Provide a value that represents the form of the item |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `included_components` | array | Which components are included? |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Provide the name of the sports team associated with the sofa, indicating the team-themed design or branding on the furniture. |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `is_fragile` | array | Is the item fragile? |
| `scent` | array | Provide a description of the scent of the item |
| `hand_orientation` | array | Provide the hand orientation that the item is built for; left, right or both |
| `back` | array | The attribute indicates Back of the product |
| `certificate` | array | The attribute indicates Certificate of the product |
| `cushion_style` | array | Provide the design and shape of the item's cushions, the soft padded sections for sitting comfort. |
| `embellishment_feature` | array | Provide the decorative elements or designs on the item, enhancing its appearance or style. |
| `fire_rating` | array | Provide the item's ability to resist fire, measured in time, ensuring safety standards are met. |
| `length_range` | array | Length range for blinds |
| `room_type` | array | Provide the intended room for the sofa, indicating the space where it is designed to be used and fit best. |
| `seat` | array | Provide the dimensions of the seat |
| `thread` | array | The attribute indicates the Thread of the product |
| `weight_capacity` | array | The attribute indicates Weight Capacity of the product |
| `width_range` | array | Width range for blinds |
| `number_of_height_positions` | array | Specify the number of height positions |
| `seat_cushion` | array | This attribute specifies details on seat cushions that come with a piece of furniture. |
| `back_cushion` | array | This attribute specifies details on back cushions that come with a piece of furniture. |
| `minimum_required_door_width` | array | Provide the minimum width of a doorway needed for the piece of furniture to fit through. This information is typically used as a measurement for delivery. |
| `furniture_leg` | array | Describes the furniture item's legs |
| `seat_recline` | array | Provide details on the reclining functionality of the furniture including whether it is manual or powered and how the reclining is triggered. |
| `mattress` | array | The attribute indicates Mattress of the product |
| `upholstery` | array | The attribute indicates Upholstery of the product |
| `sofa_type` | array | Provide the specific design and primary function of the sofa, indicating its style and purpose within the seating furniture category. |
| `indoor_outdoor_usage` | array | Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor. |
| `item_depth_width_height` | array | Provide the length, width, and height of the item when set up for use, like a rug fully rolled out. |
| `seat_back_fill_material` | array | Provide the material or materials used to fill the inner back seating area of the item (e.g. sofa). The seat back is the usually vertical portion of an item that supports the back of the person when they are seated. |
| `number_of_cup_holders` | array | Provide the number of built-in holders for cups and beverages on the item, designed to keep drinks secure and accessible. |
| `reclined_length` | array | Provide the total length of the item from the top of the headrest to the bottom of the footrest when the item is fully reclined. |
| `recommended_number_of_people_for_assembly` | array | Provide the amount of people recommended to assemble the item. |
| `furniture_wall_clearance` | array | Provide the clearance required between the item and a back wall or other obstruction in order for the item to fully recline. |
| `component_connector_assembly` | array | Provide information about the assembly of the item's component connectors such as brackets and clips. |
| `tools_recommended_for_assembly` | array | Provide the type of tools recommended to assemble the components of the item. |
| `included_throw_pillow` | array | Provide the details of the throw pillows inlcuded with the item. |
| `sleeping_area_dimensions` | array | Provide the length, width and height of the item's  sleeping area when item is converted into a bed. |
| `seat_cushion_configuration` | array | Provide the arrangement of cushions on the item's seating area, whether a single cushion or multiple separate cushions. |
| `includes_all_assembly_tools` | array | Provide whether or not all the tools required for assembling the item are included. |
| `reclining_seat_count` | array | Provide the number of reclining seats the item has. Reclining seats have a mechanism to adjust the position of the backrest and footrest. |
| `reclining_position_count` | array | Provide the number of reclining positions the item offers, based on its adjustable back and footrest mechanism. |
| `cushion_construction` | array | Provide the design and materials used to construct the item's cushions, affecting comfort and durability. |
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
| `mfg_warranty_description_type` | array | Provide the details on the manufacturer's warranty coverage for the item, explaining what is covered and for how long. |
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
| `master_pack_layers_per_pallet_quantity` | array | Provide the number of layers of master packs held on a pallet packed for storage (known as Hi). |
| `master_packs_per_layer_quantity` | array | Provide the number of master packs of the product in each layer on a pallet (known as Ti). |

## Property Details

### item_name

Provide a title for the item including brand name, material, sofa type, product type and color if available

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

- `Patio sofas`

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

### age_range_description

Provide the age range for which the sofa is intended or appropriate, helping customers choose suitable seating for different age groups.

**Type:** array

**Examples:**

- `Baby`

### material

What material is the product made out of?

**Type:** array

**Examples:**

- `nylon, wood, steel`

### fabric_type

List all fabrics separated by ','. Indicate with % composition. Always add "Viscose" or "Rayon" instead of "Bamboo", and "Azlon" for Soy

**Type:** array

**Examples:**

- `90% cotton/10% rayon`

### number_of_items

Provide the total number of identical items in the selling unit to the customer

**Type:** array

### item_package_quantity

Quantity of the item for sale in one package

**Type:** array

**Examples:**

- `3`

### subject_character

Provide the primary character the item represents

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

### number_of_pieces

Number of pieces

**Type:** array

**Examples:**

- `1250`

### part_number

For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number.

**Type:** array

**Examples:**

- `LE`

### collection

Enter the name of collection that an item belongs to.

**Type:** array

**Examples:**

- `Rivington`

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

### arm

Enter the specifications for the arm

**Type:** array

**Examples:**

- `Key`

### frame

The attribute indicates the Frame of the product

**Type:** array

**Examples:**

- `Eucalyptus Wood`

### manufacturer_grade

Enter the manufacturer grade

**Type:** array

**Examples:**

- `Type C`

### configuration

Indicate the configuration of the item

**Type:** array

**Examples:**

- `AWD Configuration`

### is_customizable

Is customizable?

**Type:** array

**Examples:**

- `Yes`

### material_feature

Provide the key material properties of the item, such as fabric type, texture, and durability characteristics.

**Type:** array

**Examples:**

- `Compostable, biodegradable, Is food safe, Fragrance free, Plant based, etc.`

### is_assembly_required

Indicate whether or not the item requires assembly by the customer

**Type:** array

**Examples:**

- `Yes`

### item_firmness_description

Provide the cushion firmness level for the item, how soft or firm the seating feels, affecting comfort and support.

**Type:** array

**Examples:**

- `Firm`

### fill_material

Provide the material used to fill the interior of the item.

**Type:** array

**Examples:**

- `Cotton`

### item_display_dimensions

Provide the dimensions of the product, without packaging and fully assembled

**Type:** array

**Examples:**

- `5.7 Inches x 3.5 Inches x 1.8 Inches`

### assembly_instructions

Provide the step-by-step directions needed for a user to assemble the product.

**Type:** array

**Examples:**

- `Position columns into holes of base and push in until snap buttons lock in place`

### seating_capacity

Provide the maximum number of people the item can seat.

**Type:** array

**Examples:**

- `4`

### specification_met

Provide the standards or guidelines the item meets, ensuring quality and safety for intended use.

**Type:** array

**Examples:**

- `AMS, ASTM, MIL`

### suspension_type

Provide the suspenion typoe of the product

**Type:** array

**Examples:**

- `Full`

### orientation

Provide the direction the item is facing or positioned, its layout or arrangement.

**Type:** array

**Examples:**

- `Forward Facing`

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Examples:**

- `Floral, Geometric, Polka Dot`

### item_density

Enter the item density. Do not include a modifier.

**Type:** array

**Examples:**

- `27 pounds per cubic foot`

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

### league_name

Name of league associated with this event

**Type:** array

**Examples:**

- `NBA`

### team_name

Provide the name of the sports team associated with the sofa, indicating the team-themed design or branding on the furniture.

**Type:** array

**Examples:**

- `Seattle Seahawks`

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Examples:**

- `Cycling`

### is_fragile

Is the item fragile?

**Type:** array

**Examples:**

- `TRUE`

### scent

Provide a description of the scent of the item

**Type:** array

### hand_orientation

Provide the hand orientation that the item is built for; left, right or both

**Type:** array

**Examples:**

- `Left Hand`

### back

The attribute indicates Back of the product

**Type:** array

**Examples:**

- `Criss-Cross Back`

### certificate

The attribute indicates Certificate of the product

**Type:** array

**Examples:**

- `PGTL`

### cushion_style

Provide the design and shape of the item's cushions, the soft padded sections for sitting comfort.

**Type:** array

**Examples:**

- `Adjustable, check seal`

### embellishment_feature

Provide the decorative elements or designs on the item, enhancing its appearance or style.

**Type:** array

**Examples:**

- `Buckle`

### fire_rating

Provide the item's ability to resist fire, measured in time, ensuring safety standards are met.

**Type:** array

**Examples:**

- `45 minutes, REI 30`

### length_range

Length range for blinds

**Type:** array

**Examples:**

- `24-60" long`

### room_type

Provide the intended room for the sofa, indicating the space where it is designed to be used and fit best.

**Type:** array

**Examples:**

- `Bedroom`

### seat

Provide the dimensions of the seat

**Type:** array

**Examples:**

- `Angstrom`

### thread

The attribute indicates the Thread of the product

**Type:** array

**Examples:**

- `UNC`

### weight_capacity

The attribute indicates Weight Capacity of the product

**Type:** array

**Examples:**

- `Milligrams`

### width_range

Width range for blinds

**Type:** array

**Examples:**

- `24-60" wide`

### number_of_height_positions

Specify the number of height positions

**Type:** array

**Examples:**

- `3`

### seat_cushion

This attribute specifies details on seat cushions that come with a piece of furniture.

**Type:** array

**Examples:**

- `2`

### back_cushion

This attribute specifies details on back cushions that come with a piece of furniture.

**Type:** array

**Examples:**

- `2`

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

### seat_recline

Provide details on the reclining functionality of the furniture including whether it is manual or powered and how the reclining is triggered.

**Type:** array

**Examples:**

- `Manual,
Push Botton`

### mattress

The attribute indicates Mattress of the product

**Type:** array

**Examples:**

- `King, Queen, Twin`

### upholstery

The attribute indicates Upholstery of the product

**Type:** array

**Examples:**

- `Upholstery Fabric Type: Cotton Blend,
Upholstery Material Composition.Material: Cotton,
Upholstery Material Composition.Percentage: 50`

### sofa_type

Provide the specific design and primary function of the sofa, indicating its style and purpose within the seating furniture category.

**Type:** array

**Examples:**

- `Setee`

### indoor_outdoor_usage

Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor.

**Type:** array

**Examples:**

- `Indoor`

### item_depth_width_height

Provide the length, width, and height of the item when set up for use, like a rug fully rolled out.

**Type:** array

**Examples:**

- `40 Inches`

### seat_back_fill_material

Provide the material or materials used to fill the inner back seating area of the item (e.g. sofa). The seat back is the usually vertical portion of an item that supports the back of the person when they are seated.

**Type:** array

**Examples:**

- `Cotton`

### number_of_cup_holders

Provide the number of built-in holders for cups and beverages on the item, designed to keep drinks secure and accessible.

**Type:** array

**Examples:**

- `4`

### reclined_length

Provide the total length of the item from the top of the headrest to the bottom of the footrest when the item is fully reclined.

**Type:** array

**Examples:**

- `67 Inches`

### recommended_number_of_people_for_assembly

Provide the amount of people recommended to assemble the item.

**Type:** array

**Examples:**

- `2`

### furniture_wall_clearance

Provide the clearance required between the item and a back wall or other obstruction in order for the item to fully recline.

**Type:** array

**Examples:**

- `3.5`

### component_connector_assembly

Provide information about the assembly of the item's component connectors such as brackets and clips.

**Type:** array

**Examples:**

- `Built-In`

### tools_recommended_for_assembly

Provide the type of tools recommended to assemble the components of the item.

**Type:** array

**Examples:**

- `Hammer`

### included_throw_pillow

Provide the details of the throw pillows inlcuded with the item.

**Type:** array

**Examples:**

- `Buckwheat, Linen, 1`

### sleeping_area_dimensions

Provide the length, width and height of the item's  sleeping area when item is converted into a bed.

**Type:** array

**Examples:**

- `200 Centimeters`

### seat_cushion_configuration

Provide the arrangement of cushions on the item's seating area, whether a single cushion or multiple separate cushions.

**Type:** array

**Examples:**

- `Single Cushion Seat`

### includes_all_assembly_tools

Provide whether or not all the tools required for assembling the item are included.

**Type:** array

**Examples:**

- `Yes`

### reclining_seat_count

Provide the number of reclining seats the item has. Reclining seats have a mechanism to adjust the position of the backrest and footrest.

**Type:** array

**Examples:**

- `4`

### reclining_position_count

Provide the number of reclining positions the item offers, based on its adjustable back and footrest mechanism.

**Type:** array

**Examples:**

- `2 Position`

### cushion_construction

Provide the design and materials used to construct the item's cushions, affecting comfort and durability.

**Type:** array

**Examples:**

- `Fiber Wrapped Foam`

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

Provide the details on the manufacturer's warranty coverage for the item, explaining what is covered and for how long.

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

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

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

