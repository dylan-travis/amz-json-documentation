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

## Nested Required Fields

| Field Path | Requirement |
|-----------|-------------|
| `age_range_description[item].language_tag` | Required in age_range_description[item] object |
| `age_range_description[item].value` | Required in age_range_description[item] object |
| `arm[item].height[item].language_tag` | Required in arm[item].height[item] object |
| `arm[item].height[item].language_tag` | Required in arm[item].height[item] object |
| `arm[item].height[item].value` | Required in arm[item].height[item] object |
| `arm[item].height[item].value` | Required in arm[item].height[item] object |
| `arm[item].style[item].language_tag` | Required in arm[item].style[item] object |
| `arm[item].style[item].language_tag` | Required in arm[item].style[item] object |
| `arm[item].style[item].value` | Required in arm[item].style[item] object |
| `arm[item].style[item].value` | Required in arm[item].style[item] object |
| `arm[item].width[item].unit` | Required in arm[item].width[item] object |
| `arm[item].width[item].unit` | Required in arm[item].width[item] object |
| `arm[item].width[item].value` | Required in arm[item].width[item] object |
| `arm[item].width[item].value` | Required in arm[item].width[item] object |
| `assembly_instructions[item].language_tag` | Required in assembly_instructions[item] object |
| `assembly_instructions[item].value` | Required in assembly_instructions[item] object |
| `back[item].style[item].language_tag` | Required in back[item].style[item] object |
| `back[item].style[item].language_tag` | Required in back[item].style[item] object |
| `back[item].style[item].value` | Required in back[item].style[item] object |
| `back[item].style[item].value` | Required in back[item].style[item] object |
| `back_cushion[item].removability[item].value` | Required in back_cushion[item].removability[item] object |
| `back_cushion[item].removability[item].value` | Required in back_cushion[item].removability[item] object |
| `back_cushion[item].thickness[item].unit` | Required in back_cushion[item].thickness[item] object |
| `back_cushion[item].thickness[item].unit` | Required in back_cushion[item].thickness[item] object |
| `back_cushion[item].thickness[item].value` | Required in back_cushion[item].thickness[item] object |
| `back_cushion[item].thickness[item].value` | Required in back_cushion[item].thickness[item] object |
| `batteries_included[item].value` | Required in batteries_included[item] object |
| `batteries_required[item].value` | Required in batteries_required[item] object |
| `battery[item].cell_composition[item].value` | Required in battery[item].cell_composition[item] object |
| `battery[item].cell_composition[item].value` | Required in battery[item].cell_composition[item] object |
| `battery[item].cell_composition_other_than_listed[item].language_tag` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].cell_composition_other_than_listed[item].language_tag` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].cell_composition_other_than_listed[item].value` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].cell_composition_other_than_listed[item].value` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].weight[item].unit` | Required in battery[item].weight[item] object |
| `battery[item].weight[item].unit` | Required in battery[item].weight[item] object |
| `battery[item].weight[item].value` | Required in battery[item].weight[item] object |
| `battery[item].weight[item].value` | Required in battery[item].weight[item] object |
| `brand[item].language_tag` | Required in brand[item] object |
| `brand[item].value` | Required in brand[item] object |
| `bullet_point[item].language_tag` | Required in bullet_point[item] object |
| `bullet_point[item].value` | Required in bullet_point[item] object |
| `california_proposition_65[item].compliance_type` | Required in california_proposition_65[item] object |
| `care_instructions[item].language_tag` | Required in care_instructions[item] object |
| `care_instructions[item].value` | Required in care_instructions[item] object |
| `certificate[item].type[item].language_tag` | Required in certificate[item].type[item] object |
| `certificate[item].type[item].language_tag` | Required in certificate[item].type[item] object |
| `certificate[item].type[item].value` | Required in certificate[item].type[item] object |
| `certificate[item].type[item].value` | Required in certificate[item].type[item] object |
| `child_parent_sku_relationship[item].child_relationship_type` | Required in child_parent_sku_relationship[item] object |
| `collection[item].language_tag` | Required in collection[item] object |
| `collection[item].value` | Required in collection[item] object |
| `color[item].language_tag` | Required in color[item] object |
| `compliance_media[item].content_language` | Required in compliance_media[item] object |
| `compliance_media[item].content_type` | Required in compliance_media[item] object |
| `compliance_media[item].source_location` | Required in compliance_media[item] object |
| `component_connector_assembly[item].value` | Required in component_connector_assembly[item] object |
| `condition_note[item].language_tag` | Required in condition_note[item] object |
| `condition_note[item].value` | Required in condition_note[item] object |
| `condition_type[item].value` | Required in condition_type[item] object |
| `configuration[item].language_tag` | Required in configuration[item] object |
| `configuration[item].value` | Required in configuration[item] object |
| `contains_pfas[item].value` | Required in contains_pfas[item] object |
| `country_of_origin[item].value` | Required in country_of_origin[item] object |
| `cushion_construction[item].language_tag` | Required in cushion_construction[item] object |
| `cushion_construction[item].value` | Required in cushion_construction[item] object |
| `cushion_style[item].language_tag` | Required in cushion_style[item] object |
| `cushion_style[item].value` | Required in cushion_style[item] object |
| `dsa_responsible_party_address[item].value` | Required in dsa_responsible_party_address[item] object |
| `embellishment_feature[item].language_tag` | Required in embellishment_feature[item] object |
| `embellishment_feature[item].value` | Required in embellishment_feature[item] object |
| `externally_assigned_product_identifier[item].type` | Required in externally_assigned_product_identifier[item] object |
| `externally_assigned_product_identifier[item].value` | Required in externally_assigned_product_identifier[item] object |
| `fabric_type[item].language_tag` | Required in fabric_type[item] object |
| `fabric_type[item].value` | Required in fabric_type[item] object |
| `fcc_radio_frequency_emission_compliance[item].registration_status` | Required in fcc_radio_frequency_emission_compliance[item] object |
| `fill_material[item].language_tag` | Required in fill_material[item] object |
| `fill_material[item].value` | Required in fill_material[item] object |
| `fire_rating[item].language_tag` | Required in fire_rating[item] object |
| `fire_rating[item].value` | Required in fire_rating[item] object |
| `frame[item].color[item].language_tag` | Required in frame[item].color[item] object |
| `frame[item].color[item].language_tag` | Required in frame[item].color[item] object |
| `frame[item].color[item].value` | Required in frame[item].color[item] object |
| `frame[item].color[item].value` | Required in frame[item].color[item] object |
| `frame[item].joint_type[item].language_tag` | Required in frame[item].joint_type[item] object |
| `frame[item].joint_type[item].language_tag` | Required in frame[item].joint_type[item] object |
| `frame[item].joint_type[item].value` | Required in frame[item].joint_type[item] object |
| `frame[item].joint_type[item].value` | Required in frame[item].joint_type[item] object |
| `frame[item].material[item].language_tag` | Required in frame[item].material[item] object |
| `frame[item].material[item].language_tag` | Required in frame[item].material[item] object |
| `frame[item].material[item].value` | Required in frame[item].material[item] object |
| `frame[item].material[item].value` | Required in frame[item].material[item] object |
| `fulfillment_availability[item].fulfillment_channel_code` | Required in fulfillment_availability[item] object |
| `furniture_leg[item].color[item].language_tag` | Required in furniture_leg[item].color[item] object |
| `furniture_leg[item].color[item].language_tag` | Required in furniture_leg[item].color[item] object |
| `furniture_leg[item].color[item].value` | Required in furniture_leg[item].color[item] object |
| `furniture_leg[item].color[item].value` | Required in furniture_leg[item].color[item] object |
| `furniture_leg[item].length[item].unit` | Required in furniture_leg[item].length[item] object |
| `furniture_leg[item].length[item].unit` | Required in furniture_leg[item].length[item] object |
| `furniture_leg[item].length[item].value` | Required in furniture_leg[item].length[item] object |
| `furniture_leg[item].length[item].value` | Required in furniture_leg[item].length[item] object |
| `furniture_leg[item].material[item].language_tag` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].material[item].language_tag` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].material[item].value` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].material[item].value` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].style[item].language_tag` | Required in furniture_leg[item].style[item] object |
| `furniture_leg[item].style[item].language_tag` | Required in furniture_leg[item].style[item] object |
| `furniture_leg[item].style[item].value` | Required in furniture_leg[item].style[item] object |
| `furniture_leg[item].style[item].value` | Required in furniture_leg[item].style[item] object |
| `furniture_wall_clearance[item].unit` | Required in furniture_wall_clearance[item] object |
| `furniture_wall_clearance[item].value` | Required in furniture_wall_clearance[item] object |
| `generic_keyword[item].language_tag` | Required in generic_keyword[item] object |
| `generic_keyword[item].value` | Required in generic_keyword[item] object |
| `ghs[item].classification[item].class` | Required in ghs[item].classification[item] object |
| `ghs[item].classification[item].class` | Required in ghs[item].classification[item] object |
| `ghs_chemical_h_code[item].value` | Required in ghs_chemical_h_code[item] object |
| `gpsr_safety_attestation[item].value` | Required in gpsr_safety_attestation[item] object |
| `hand_orientation[item].language_tag` | Required in hand_orientation[item] object |
| `hand_orientation[item].value` | Required in hand_orientation[item] object |
| `handmade_classification[item].value` | Required in handmade_classification[item] object |
| `hazmat[item].aspect` | Required in hazmat[item] object |
| `hazmat[item].value` | Required in hazmat[item] object |
| `included_components[item].language_tag` | Required in included_components[item] object |
| `included_components[item].value` | Required in included_components[item] object |
| `included_throw_pillow[item].cover_material[item].language_tag` | Required in included_throw_pillow[item].cover_material[item] object |
| `included_throw_pillow[item].cover_material[item].language_tag` | Required in included_throw_pillow[item].cover_material[item] object |
| `included_throw_pillow[item].cover_material[item].value` | Required in included_throw_pillow[item].cover_material[item] object |
| `included_throw_pillow[item].cover_material[item].value` | Required in included_throw_pillow[item].cover_material[item] object |
| `included_throw_pillow[item].fill_material[item].language_tag` | Required in included_throw_pillow[item].fill_material[item] object |
| `included_throw_pillow[item].fill_material[item].language_tag` | Required in included_throw_pillow[item].fill_material[item] object |
| `included_throw_pillow[item].fill_material[item].value` | Required in included_throw_pillow[item].fill_material[item] object |
| `included_throw_pillow[item].fill_material[item].value` | Required in included_throw_pillow[item].fill_material[item] object |
| `included_throw_pillow[item].quantity[item].value` | Required in included_throw_pillow[item].quantity[item] object |
| `included_throw_pillow[item].quantity[item].value` | Required in included_throw_pillow[item].quantity[item] object |
| `includes_all_assembly_tools[item].value` | Required in includes_all_assembly_tools[item] object |
| `indoor_outdoor_usage[item].value` | Required in indoor_outdoor_usage[item] object |
| `is_assembly_required[item].value` | Required in is_assembly_required[item] object |
| `is_customizable[item].value` | Required in is_customizable[item] object |
| `is_fragile[item].value` | Required in is_fragile[item] object |
| `item_density[item].unit` | Required in item_density[item] object |
| `item_density[item].value` | Required in item_density[item] object |
| `item_depth_width_height[item].depth` | Required in item_depth_width_height[item] object |
| `item_depth_width_height[item].depth.unit` | Required in item_depth_width_height[item].depth object |
| `item_depth_width_height[item].depth.unit` | Required in item_depth_width_height[item].depth object |
| `item_depth_width_height[item].depth.value` | Required in item_depth_width_height[item].depth object |
| `item_depth_width_height[item].depth.value` | Required in item_depth_width_height[item].depth object |
| `item_depth_width_height[item].height` | Required in item_depth_width_height[item] object |
| `item_depth_width_height[item].height.unit` | Required in item_depth_width_height[item].height object |
| `item_depth_width_height[item].height.unit` | Required in item_depth_width_height[item].height object |
| `item_depth_width_height[item].height.value` | Required in item_depth_width_height[item].height object |
| `item_depth_width_height[item].height.value` | Required in item_depth_width_height[item].height object |
| `item_depth_width_height[item].width` | Required in item_depth_width_height[item] object |
| `item_depth_width_height[item].width.unit` | Required in item_depth_width_height[item].width object |
| `item_depth_width_height[item].width.unit` | Required in item_depth_width_height[item].width object |
| `item_depth_width_height[item].width.value` | Required in item_depth_width_height[item].width object |
| `item_depth_width_height[item].width.value` | Required in item_depth_width_height[item].width object |
| `item_display_dimensions[item].height.unit` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].height.unit` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].height.value` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].height.value` | Required in item_display_dimensions[item].height object |
| `item_display_weight[item].unit` | Required in item_display_weight[item] object |
| `item_display_weight[item].value` | Required in item_display_weight[item] object |
| `item_firmness_description[item].language_tag` | Required in item_firmness_description[item] object |
| `item_firmness_description[item].value` | Required in item_firmness_description[item] object |
| `item_form[item].language_tag` | Required in item_form[item] object |
| `item_form[item].value` | Required in item_form[item] object |
| `item_name[item].language_tag` | Required in item_name[item] object |
| `item_name[item].value` | Required in item_name[item] object |
| `item_package_dimensions[item].height` | Required in item_package_dimensions[item] object |
| `item_package_dimensions[item].height.unit` | Required in item_package_dimensions[item].height object |
| `item_package_dimensions[item].height.unit` | Required in item_package_dimensions[item].height object |
| `item_package_dimensions[item].height.value` | Required in item_package_dimensions[item].height object |
| `item_package_dimensions[item].height.value` | Required in item_package_dimensions[item].height object |
| `item_package_dimensions[item].length` | Required in item_package_dimensions[item] object |
| `item_package_dimensions[item].length.unit` | Required in item_package_dimensions[item].length object |
| `item_package_dimensions[item].length.unit` | Required in item_package_dimensions[item].length object |
| `item_package_dimensions[item].length.value` | Required in item_package_dimensions[item].length object |
| `item_package_dimensions[item].length.value` | Required in item_package_dimensions[item].length object |
| `item_package_dimensions[item].width` | Required in item_package_dimensions[item] object |
| `item_package_dimensions[item].width.unit` | Required in item_package_dimensions[item].width object |
| `item_package_dimensions[item].width.unit` | Required in item_package_dimensions[item].width object |
| `item_package_dimensions[item].width.value` | Required in item_package_dimensions[item].width object |
| `item_package_dimensions[item].width.value` | Required in item_package_dimensions[item].width object |
| `item_package_quantity[item].value` | Required in item_package_quantity[item] object |
| `item_package_weight[item].unit` | Required in item_package_weight[item] object |
| `item_package_weight[item].value` | Required in item_package_weight[item] object |
| `item_shape[item].language_tag` | Required in item_shape[item] object |
| `item_shape[item].value` | Required in item_shape[item] object |
| `item_type_keyword[item].value` | Required in item_type_keyword[item] object |
| `item_weight[item].unit` | Required in item_weight[item] object |
| `item_weight[item].value` | Required in item_weight[item] object |
| `league_name[item].language_tag` | Required in league_name[item] object |
| `league_name[item].value` | Required in league_name[item] object |
| `length_range[item].language_tag` | Required in length_range[item] object |
| `length_range[item].value` | Required in length_range[item] object |
| `list_price[item].currency` | Required in list_price[item] object |
| `list_price[item].value` | Required in list_price[item] object |
| `lithium_battery[item].energy_content[item].unit` | Required in lithium_battery[item].energy_content[item] object |
| `lithium_battery[item].energy_content[item].unit` | Required in lithium_battery[item].energy_content[item] object |
| `lithium_battery[item].energy_content[item].value` | Required in lithium_battery[item].energy_content[item] object |
| `lithium_battery[item].energy_content[item].value` | Required in lithium_battery[item].energy_content[item] object |
| `lithium_battery[item].packaging[item].value` | Required in lithium_battery[item].packaging[item] object |
| `lithium_battery[item].packaging[item].value` | Required in lithium_battery[item].packaging[item] object |
| `lithium_battery[item].weight[item].unit` | Required in lithium_battery[item].weight[item] object |
| `lithium_battery[item].weight[item].unit` | Required in lithium_battery[item].weight[item] object |
| `lithium_battery[item].weight[item].value` | Required in lithium_battery[item].weight[item] object |
| `lithium_battery[item].weight[item].value` | Required in lithium_battery[item].weight[item] object |
| `main_offer_image_locator[item].media_location` | Required in main_offer_image_locator[item] object |
| `main_product_image_locator[item].media_location` | Required in main_product_image_locator[item] object |
| `manufacturer[item].language_tag` | Required in manufacturer[item] object |
| `manufacturer[item].value` | Required in manufacturer[item] object |
| `manufacturer_grade[item].language_tag` | Required in manufacturer_grade[item] object |
| `manufacturer_grade[item].value` | Required in manufacturer_grade[item] object |
| `map_policy[item].value` | Required in map_policy[item] object |
| `master_pack_layers_per_pallet_quantity[item].value` | Required in master_pack_layers_per_pallet_quantity[item] object |
| `master_packs_per_layer_quantity[item].value` | Required in master_packs_per_layer_quantity[item] object |
| `material[item].language_tag` | Required in material[item] object |
| `material[item].value` | Required in material[item] object |
| `material_feature[item].language_tag` | Required in material_feature[item] object |
| `material_feature[item].value` | Required in material_feature[item] object |
| `mattress[item].length_width[item].length` | Required in mattress[item].length_width[item] object |
| `mattress[item].length_width[item].length` | Required in mattress[item].length_width[item] object |
| `mattress[item].length_width[item].length.unit` | Required in mattress[item].length_width[item].length object |
| `mattress[item].length_width[item].length.unit` | Required in mattress[item].length_width[item].length object |
| `mattress[item].length_width[item].length.unit` | Required in mattress[item].length_width[item].length object |
| `mattress[item].length_width[item].length.value` | Required in mattress[item].length_width[item].length object |
| `mattress[item].length_width[item].length.value` | Required in mattress[item].length_width[item].length object |
| `mattress[item].length_width[item].length.value` | Required in mattress[item].length_width[item].length object |
| `mattress[item].length_width[item].width` | Required in mattress[item].length_width[item] object |
| `mattress[item].length_width[item].width` | Required in mattress[item].length_width[item] object |
| `mattress[item].length_width[item].width.unit` | Required in mattress[item].length_width[item].width object |
| `mattress[item].length_width[item].width.unit` | Required in mattress[item].length_width[item].width object |
| `mattress[item].length_width[item].width.unit` | Required in mattress[item].length_width[item].width object |
| `mattress[item].length_width[item].width.value` | Required in mattress[item].length_width[item].width object |
| `mattress[item].length_width[item].width.value` | Required in mattress[item].length_width[item].width object |
| `mattress[item].length_width[item].width.value` | Required in mattress[item].length_width[item].width object |
| `mattress[item].size_name[item].value` | Required in mattress[item].size_name[item] object |
| `mattress[item].size_name[item].value` | Required in mattress[item].size_name[item] object |
| `mattress[item].thickness[item].unit` | Required in mattress[item].thickness[item] object |
| `mattress[item].thickness[item].unit` | Required in mattress[item].thickness[item] object |
| `mattress[item].thickness[item].value` | Required in mattress[item].thickness[item] object |
| `mattress[item].thickness[item].value` | Required in mattress[item].thickness[item] object |
| `max_order_quantity[item].value` | Required in max_order_quantity[item] object |
| `merchant_release_date[item].value` | Required in merchant_release_date[item] object |
| `merchant_shipping_group[item].value` | Required in merchant_shipping_group[item] object |
| `merchant_suggested_asin[item].value` | Required in merchant_suggested_asin[item] object |
| `mfg_warranty_description_type[item].language_tag` | Required in mfg_warranty_description_type[item] object |
| `mfg_warranty_description_type[item].value` | Required in mfg_warranty_description_type[item] object |
| `minimum_required_door_width[item].unit` | Required in minimum_required_door_width[item] object |
| `minimum_required_door_width[item].value` | Required in minimum_required_door_width[item] object |
| `model_name[item].language_tag` | Required in model_name[item] object |
| `model_name[item].value` | Required in model_name[item] object |
| `model_number[item].value` | Required in model_number[item] object |
| `num_batteries[item].quantity` | Required in num_batteries[item] object |
| `num_batteries[item].type` | Required in num_batteries[item] object |
| `number_of_cup_holders[item].value` | Required in number_of_cup_holders[item] object |
| `number_of_height_positions[item].value` | Required in number_of_height_positions[item] object |
| `number_of_items[item].value` | Required in number_of_items[item] object |
| `number_of_lithium_ion_cells[item].value` | Required in number_of_lithium_ion_cells[item] object |
| `number_of_lithium_metal_cells[item].value` | Required in number_of_lithium_metal_cells[item] object |
| `number_of_pieces[item].value` | Required in number_of_pieces[item] object |
| `orientation[item].language_tag` | Required in orientation[item] object |
| `orientation[item].value` | Required in orientation[item] object |
| `other_offer_image_locator_1[item].media_location` | Required in other_offer_image_locator_1[item] object |
| `other_offer_image_locator_2[item].media_location` | Required in other_offer_image_locator_2[item] object |
| `other_offer_image_locator_3[item].media_location` | Required in other_offer_image_locator_3[item] object |
| `other_offer_image_locator_4[item].media_location` | Required in other_offer_image_locator_4[item] object |
| `other_offer_image_locator_5[item].media_location` | Required in other_offer_image_locator_5[item] object |
| `other_product_image_locator_1[item].media_location` | Required in other_product_image_locator_1[item] object |
| `other_product_image_locator_2[item].media_location` | Required in other_product_image_locator_2[item] object |
| `other_product_image_locator_3[item].media_location` | Required in other_product_image_locator_3[item] object |
| `other_product_image_locator_4[item].media_location` | Required in other_product_image_locator_4[item] object |
| `other_product_image_locator_5[item].media_location` | Required in other_product_image_locator_5[item] object |
| `other_product_image_locator_6[item].media_location` | Required in other_product_image_locator_6[item] object |
| `other_product_image_locator_7[item].media_location` | Required in other_product_image_locator_7[item] object |
| `other_product_image_locator_8[item].media_location` | Required in other_product_image_locator_8[item] object |
| `package_contains_sku[item].quantity` | Required in package_contains_sku[item] object |
| `package_contains_sku[item].sku` | Required in package_contains_sku[item] object |
| `package_level[item].value` | Required in package_level[item] object |
| `parentage_level[item].value` | Required in parentage_level[item] object |
| `part_number[item].value` | Required in part_number[item] object |
| `pattern[item].language_tag` | Required in pattern[item] object |
| `pattern[item].value` | Required in pattern[item] object |
| `product_description[item].language_tag` | Required in product_description[item] object |
| `product_description[item].value` | Required in product_description[item] object |
| `product_site_launch_date[item].value` | Required in product_site_launch_date[item] object |
| `product_tax_code[item].value` | Required in product_tax_code[item] object |
| `purchasable_offer[item].automated_pricing_merchandising_rule_plan[item].merchandising_rule.rule_id` | Required in purchasable_offer[item].automated_pricing_merchandising_rule_plan[item].merchandising_rule object |
| `purchasable_offer[item].automated_pricing_merchandising_rule_plan[item].merchandising_rule.rule_id` | Required in purchasable_offer[item].automated_pricing_merchandising_rule_plan[item].merchandising_rule object |
| `purchasable_offer[item].automated_pricing_merchandising_rule_plan[item].merchandising_rule.rule_id` | Required in purchasable_offer[item].automated_pricing_merchandising_rule_plan[item].merchandising_rule object |
| `purchasable_offer[item].discounted_price[item].schedule` | Required in purchasable_offer[item].discounted_price[item] object |
| `purchasable_offer[item].discounted_price[item].schedule` | Required in purchasable_offer[item].discounted_price[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].end_at` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].end_at` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].end_at` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].start_at` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].start_at` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].start_at` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].value_with_tax` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].value_with_tax` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].discounted_price[item].schedule[item].value_with_tax` | Required in purchasable_offer[item].discounted_price[item].schedule[item] object |
| `purchasable_offer[item].our_price[item].schedule` | Required in purchasable_offer[item].our_price[item] object |
| `purchasable_offer[item].our_price[item].schedule` | Required in purchasable_offer[item].our_price[item] object |
| `purchasable_offer[item].our_price[item].schedule[item].value_with_tax` | Required in purchasable_offer[item].our_price[item].schedule[item] object |
| `purchasable_offer[item].our_price[item].schedule[item].value_with_tax` | Required in purchasable_offer[item].our_price[item].schedule[item] object |
| `purchasable_offer[item].our_price[item].schedule[item].value_with_tax` | Required in purchasable_offer[item].our_price[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule` | Required in purchasable_offer[item].quantity_discount_plan[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule` | Required in purchasable_offer[item].quantity_discount_plan[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].discount_type` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].discount_type` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].discount_type` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].lower_bound` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].lower_bound` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].lower_bound` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].lower_bound` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].lower_bound` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].value` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].value` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].value` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].value` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item].value` | Required in purchasable_offer[item].quantity_discount_plan[item].schedule[item].levels[item] object |
| `reclined_length[item].unit` | Required in reclined_length[item] object |
| `reclined_length[item].value` | Required in reclined_length[item] object |
| `reclining_position_count[item].language_tag` | Required in reclining_position_count[item] object |
| `reclining_position_count[item].value` | Required in reclining_position_count[item] object |
| `reclining_seat_count[item].value` | Required in reclining_seat_count[item] object |
| `recommended_number_of_people_for_assembly[item].value` | Required in recommended_number_of_people_for_assembly[item] object |
| `recommended_uses_for_product[item].language_tag` | Required in recommended_uses_for_product[item] object |
| `recommended_uses_for_product[item].value` | Required in recommended_uses_for_product[item] object |
| `regulatory_compliance_certification[item].regulation_type` | Required in regulatory_compliance_certification[item] object |
| `regulatory_compliance_certification[item].value` | Required in regulatory_compliance_certification[item] object |
| `room_type[item].language_tag` | Required in room_type[item] object |
| `room_type[item].value` | Required in room_type[item] object |
| `safety_data_sheet_url[item].language_tag` | Required in safety_data_sheet_url[item] object |
| `safety_data_sheet_url[item].value` | Required in safety_data_sheet_url[item] object |
| `safety_warning[item].language_tag` | Required in safety_warning[item] object |
| `safety_warning[item].value` | Required in safety_warning[item] object |
| `scent[item].language_tag` | Required in scent[item] object |
| `scent[item].value` | Required in scent[item] object |
| `seat[item].back_interior_height[item].unit` | Required in seat[item].back_interior_height[item] object |
| `seat[item].back_interior_height[item].unit` | Required in seat[item].back_interior_height[item] object |
| `seat[item].back_interior_height[item].value` | Required in seat[item].back_interior_height[item] object |
| `seat[item].back_interior_height[item].value` | Required in seat[item].back_interior_height[item] object |
| `seat[item].depth[item].unit` | Required in seat[item].depth[item] object |
| `seat[item].depth[item].unit` | Required in seat[item].depth[item] object |
| `seat[item].depth[item].value` | Required in seat[item].depth[item] object |
| `seat[item].depth[item].value` | Required in seat[item].depth[item] object |
| `seat[item].fill_material[item].value` | Required in seat[item].fill_material[item] object |
| `seat[item].fill_material[item].value` | Required in seat[item].fill_material[item] object |
| `seat[item].height[item].unit` | Required in seat[item].height[item] object |
| `seat[item].height[item].unit` | Required in seat[item].height[item] object |
| `seat[item].height[item].value` | Required in seat[item].height[item] object |
| `seat[item].height[item].value` | Required in seat[item].height[item] object |
| `seat[item].interior_width[item].unit` | Required in seat[item].interior_width[item] object |
| `seat[item].interior_width[item].unit` | Required in seat[item].interior_width[item] object |
| `seat[item].interior_width[item].value` | Required in seat[item].interior_width[item] object |
| `seat[item].interior_width[item].value` | Required in seat[item].interior_width[item] object |
| `seat_back_fill_material[item].value` | Required in seat_back_fill_material[item] object |
| `seat_cushion[item].has_removable_cover[item].value` | Required in seat_cushion[item].has_removable_cover[item] object |
| `seat_cushion[item].has_removable_cover[item].value` | Required in seat_cushion[item].has_removable_cover[item] object |
| `seat_cushion[item].quantity[item].value` | Required in seat_cushion[item].quantity[item] object |
| `seat_cushion[item].quantity[item].value` | Required in seat_cushion[item].quantity[item] object |
| `seat_cushion[item].removability[item].value` | Required in seat_cushion[item].removability[item] object |
| `seat_cushion[item].removability[item].value` | Required in seat_cushion[item].removability[item] object |
| `seat_cushion_configuration[item].value` | Required in seat_cushion_configuration[item] object |
| `seat_recline[item].operation_mode` | Required in seat_recline[item] object |
| `seating_capacity[item].value` | Required in seating_capacity[item] object |
| `ships_globally[item].value` | Required in ships_globally[item] object |
| `size[item].language_tag` | Required in size[item] object |
| `size[item].value` | Required in size[item] object |
| `skip_offer[item].value` | Required in skip_offer[item] object |
| `sleeping_area_dimensions[item].height` | Required in sleeping_area_dimensions[item] object |
| `sleeping_area_dimensions[item].height.unit` | Required in sleeping_area_dimensions[item].height object |
| `sleeping_area_dimensions[item].height.unit` | Required in sleeping_area_dimensions[item].height object |
| `sleeping_area_dimensions[item].height.value` | Required in sleeping_area_dimensions[item].height object |
| `sleeping_area_dimensions[item].height.value` | Required in sleeping_area_dimensions[item].height object |
| `sleeping_area_dimensions[item].length` | Required in sleeping_area_dimensions[item] object |
| `sleeping_area_dimensions[item].length.unit` | Required in sleeping_area_dimensions[item].length object |
| `sleeping_area_dimensions[item].length.unit` | Required in sleeping_area_dimensions[item].length object |
| `sleeping_area_dimensions[item].length.value` | Required in sleeping_area_dimensions[item].length object |
| `sleeping_area_dimensions[item].length.value` | Required in sleeping_area_dimensions[item].length object |
| `sleeping_area_dimensions[item].width` | Required in sleeping_area_dimensions[item] object |
| `sleeping_area_dimensions[item].width.unit` | Required in sleeping_area_dimensions[item].width object |
| `sleeping_area_dimensions[item].width.unit` | Required in sleeping_area_dimensions[item].width object |
| `sleeping_area_dimensions[item].width.value` | Required in sleeping_area_dimensions[item].width object |
| `sleeping_area_dimensions[item].width.value` | Required in sleeping_area_dimensions[item].width object |
| `sofa_type[item].value` | Required in sofa_type[item] object |
| `special_feature[item].language_tag` | Required in special_feature[item] object |
| `special_feature[item].value` | Required in special_feature[item] object |
| `specification_met[item].language_tag` | Required in specification_met[item] object |
| `specification_met[item].value` | Required in specification_met[item] object |
| `style[item].language_tag` | Required in style[item] object |
| `style[item].value` | Required in style[item] object |
| `subject_character[item].language_tag` | Required in subject_character[item] object |
| `subject_character[item].value` | Required in subject_character[item] object |
| `supplier_declared_dg_hz_regulation[item].value` | Required in supplier_declared_dg_hz_regulation[item] object |
| `supplier_declared_has_product_identifier_exemption[item].value` | Required in supplier_declared_has_product_identifier_exemption[item] object |
| `suspension_type[item].language_tag` | Required in suspension_type[item] object |
| `suspension_type[item].value` | Required in suspension_type[item] object |
| `swatch_product_image_locator[item].media_location` | Required in swatch_product_image_locator[item] object |
| `team_name[item].language_tag` | Required in team_name[item] object |
| `team_name[item].value` | Required in team_name[item] object |
| `theme[item].language_tag` | Required in theme[item] object |
| `theme[item].value` | Required in theme[item] object |
| `thread[item].count[item].value` | Required in thread[item].count[item] object |
| `thread[item].count[item].value` | Required in thread[item].count[item] object |
| `tools_recommended_for_assembly[item].value` | Required in tools_recommended_for_assembly[item] object |
| `unit_count[item].type.language_tag` | Required in unit_count[item].type object |
| `unit_count[item].type.language_tag` | Required in unit_count[item].type object |
| `unit_count[item].type.value` | Required in unit_count[item].type object |
| `unit_count[item].type.value` | Required in unit_count[item].type object |
| `unit_count[item].value` | Required in unit_count[item] object |
| `upholstery[item].cleaning_code[item].language_tag` | Required in upholstery[item].cleaning_code[item] object |
| `upholstery[item].cleaning_code[item].language_tag` | Required in upholstery[item].cleaning_code[item] object |
| `upholstery[item].cleaning_code[item].value` | Required in upholstery[item].cleaning_code[item] object |
| `upholstery[item].cleaning_code[item].value` | Required in upholstery[item].cleaning_code[item] object |
| `upholstery[item].color[item].language_tag` | Required in upholstery[item].color[item] object |
| `upholstery[item].color[item].language_tag` | Required in upholstery[item].color[item] object |
| `upholstery[item].color[item].value` | Required in upholstery[item].color[item] object |
| `upholstery[item].color[item].value` | Required in upholstery[item].color[item] object |
| `upholstery[item].double_rub_count[item].value` | Required in upholstery[item].double_rub_count[item] object |
| `upholstery[item].double_rub_count[item].value` | Required in upholstery[item].double_rub_count[item] object |
| `upholstery[item].fabric_type[item].language_tag` | Required in upholstery[item].fabric_type[item] object |
| `upholstery[item].fabric_type[item].language_tag` | Required in upholstery[item].fabric_type[item] object |
| `upholstery[item].fabric_type[item].value` | Required in upholstery[item].fabric_type[item] object |
| `upholstery[item].fabric_type[item].value` | Required in upholstery[item].fabric_type[item] object |
| `upholstery[item].material_composition[item].material_percentage` | Required in upholstery[item].material_composition[item] object |
| `upholstery[item].material_composition[item].material_percentage` | Required in upholstery[item].material_composition[item] object |
| `upholstery[item].material_composition[item].material_type` | Required in upholstery[item].material_composition[item] object |
| `upholstery[item].material_composition[item].material_type` | Required in upholstery[item].material_composition[item] object |
| `upholstery[item].rub_count[item].value` | Required in upholstery[item].rub_count[item] object |
| `upholstery[item].rub_count[item].value` | Required in upholstery[item].rub_count[item] object |
| `variation_theme[item].name` | Required in variation_theme[item] object |
| `warranty_type[item].language_tag` | Required in warranty_type[item] object |
| `warranty_type[item].value` | Required in warranty_type[item] object |
| `weight_capacity[item].maximum[item].unit` | Required in weight_capacity[item].maximum[item] object |
| `weight_capacity[item].maximum[item].unit` | Required in weight_capacity[item].maximum[item] object |
| `weight_capacity[item].maximum[item].value` | Required in weight_capacity[item].maximum[item] object |
| `weight_capacity[item].maximum[item].value` | Required in weight_capacity[item].maximum[item] object |
| `width_range[item].language_tag` | Required in width_range[item] object |
| `width_range[item].value` | Required in width_range[item] object |

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

**Title:** Title

**Required:** Yes

**Examples:**

- `Adidas Blue Sneakers`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a title for the item including brand name, material, sofa type, product type and color if available |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### brand

Max. 50 characters

**Type:** array

**Title:** Brand Name

**Required:** Yes

**Examples:**

- `Sonny Brook Hams`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the brand name of the product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### externally_assigned_product_identifier

Provide the external ID (barcode) type and corresponding value that is being used to identify the product

**Type:** array

**Title:** External Product ID

**Required:** Conditionally

**Examples:**

- `714532191586`

**Selectors:** `marketplace_id`, `type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `type` | string | Yes | Select the type of external ID (barcode) that is being used to identify this product |
| `value` | string | Yes | Provide the corresponding external product id value based on the type that was selected |
| `marketplace_id` | object | No |  |

### merchant_suggested_asin

Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID.

**Type:** array

**Title:** Merchant Suggested ASIN

**Required:** Conditionally

**Examples:**

- `B007KQBXN0`

**Selectors:** `marketplace_id`, `value`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide an ASIN for your product if one exists. If a value is not provided, the system will attempt a match based on the External Product ID. |
| `marketplace_id` | object | No |  |

### supplier_declared_has_product_identifier_exemption

Please specify if the product is exempt from supplier declared external product identifiers.

**Type:** array

**Title:** Is exempt from a supplier declared external identifier

**Required:** No

**Examples:**

- `Y, N`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Please specify if the product is exempt from supplier declared external product identifiers. |
| `marketplace_id` | object | No |  |

### item_type_keyword

What is the item that you are selling?

**Type:** array

**Title:** Item Type Keyword

**Required:** Yes

**Examples:**

- `Patio sofas`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Item type keywords are used to place new ASINs in the appropriate place(s) within the graph. Select the most specific accurate term for optimal placement. |
| `marketplace_id` | object | No |  |

### package_level

Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy.

**Type:** array

**Title:** Package Level

**Required:** No

**Examples:**

- `Unit, Case`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the package level of the item. Choose “Unit” when package hierarchy is not provided or applicable. Provide one “Unit” item for every package hierarchy. |
| `marketplace_id` | object | No |  |

### package_contains_sku

Provide the SKU and quantity of the child items contained in the next package level.

**Type:** array

**Title:** Package Contains SKU

**Required:** Conditionally

**Examples:**

- `SKU: ABC123, Quanitity: 1`

**Selectors:** `marketplace_id`, `sku`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `quantity` | integer | Yes | Provide the quantity of each unit, case, or pallet identified in Package Level. |
| `sku` | string | Yes | Provide the SKU identifier of each unit, case or pallet identified in Package Level. |

### model_number

Product code assigned by the manufacturer; can be numbers, letters, or both

**Type:** array

**Title:** Model Number

**Required:** No

**Examples:**

- `C-50`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the manufacturer 's model number for the item |
| `marketplace_id` | object | No |  |

### model_name

Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size

**Type:** array

**Title:** Model Name

**Required:** No

**Examples:**

- `MacBook Pro`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the model name of the product as defined by the manufacturer or brand excluding item type, color, brand or size |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### manufacturer

The full name of the publisher who issued the product

**Type:** array

**Title:** Manufacturer

**Required:** No

**Examples:**

- `Sony, Kitchen Aid, Microsoft`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the company that manufactures the product. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### skip_offer

Please indicate whether the offer should be skipped and a buyable offer should not be created. A value of "Yes", means no offer will be created.

**Type:** array

**Title:** Skip Offer

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Please indicate whether the offer should be skipped and a buyable offer should not be created. A value of "Yes", means no offer will be created. |
| `marketplace_id` | object | No |  |

### fulfillment_availability

For those merchants using Amazon fulfillment services, please provide associated logistical information.

**Type:** array

**Title:** Fulfillment Availability

**Required:** Conditionally

**Selectors:** `fulfillment_channel_code`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `fulfillment_channel_code` | string | Yes | For those merchants using Amazon fulfillment services, this designates which fulfillment network will be used. Specifying a value other than DEFAULT will cancel the Merchant-fulfilled offering. |
| `quantity` | integer | No | Enter the quantity of the item you are making available for sale. This is your current inventory commitment (as a whole number) |
| `lead_time_to_ship_max_days` | integer | No | Provide the time, in days, between when you receive an order for an item and when you can ship the item |
| `restock_date` | string | No | Date that product will be restocked |
| `is_inventory_available` | boolean | No | Always available inventory is an alternative to quantity that allows inventory to never deplete. Enabling or disabling will toggle this feature on or off. Note that a quantity cannot be specified when provided. |

### map_policy

Select one.

**Type:** array

**Title:** Minimum Advertised Price Display

**Required:** No

**Examples:**

- `Policy 9`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Select one. |
| `marketplace_id` | object | No |  |

### purchasable_offer

The attribute indicates the Purchasable Offer of the product

**Type:** array

**Title:** Purchasable Offer

**Required:** Conditionally

**Examples:**

- `EUR`

**Selectors:** `marketplace_id`, `currency`, `audience`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `map_price` | array | No | The attribute indicates the Purchasable Offer Map Price of the product |
| `currency` | string | No | Select the corresponding currency |
| `marketplace_id` | object | No |  |
| `our_price` | array | No | The attribute indicates the Purchasable Offer Our Price of the product |
| `automated_pricing_merchandising_rule_plan` | array | No |  |
| `minimum_seller_allowed_price` | array | No | The attribute indicates the Purchasable Offer Minimum Seller Allowed Price of the product |
| `maximum_seller_allowed_price` | array | No | The attribute indicates the Purchasable Offer Maximum Seller Allowed Price of the product |
| `discounted_price` | array | No | The attribute indicates the Purchasable Offer Discounted Price of the product |
| `start_at` | object | No | The attribute indicates the Purchasable Offer Start At of the product |
| `end_at` | object | No | The attribute indicates the Purchasable Offer End At of the product |
| `audience` | string | No | Provide the intended buyer segment or program that this purchasable offer is applicable to. |
| `quantity_discount_plan` | array | No | Provide and define the quantity discount plan for your business price. |

#### purchasable_offer[].start_at

The attribute indicates the Purchasable Offer Start At of the product

**Type:** object

**Title:** Purchasable Offer Start At

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | No | Your price start date |

#### purchasable_offer[].end_at

The attribute indicates the Purchasable Offer End At of the product

**Type:** object

**Title:** Purchasable Offer End At

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | No | Your price end date |

### condition_type

Provide the actual condition type of the product

**Type:** array

**Title:** Item Condition

**Required:** No

**Examples:**

- `New`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the actual condition type of the product |
| `marketplace_id` | object | No |  |

### condition_note

Provide descriptive text explaining the actual condition of the item

**Type:** array

**Title:** Offer Condition Note

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide descriptive text explaining the actual condition of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### list_price

Provide the list price for the product. List Price is the suggested retail price of a product as provided by a manufacturer, supplier, or seller. This is not the offering or cost price.

**Type:** array

**Title:** List Price

**Required:** Conditionally

**Examples:**

- `64 USD, 69 GBP, 98 EUR`

**Selectors:** `marketplace_id`, `currency`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the list price for the product not including tax. List Price is the suggested retail price of a product as provided by a manufacturer, supplier, or seller. This is not the offering or cost price. If you are unable to provide a value, enter 0. |
| `currency` | string | Yes | Select the corresponding currency |
| `marketplace_id` | object | No |  |

### product_tax_code

Enter the product tax code supplied to you by Amazon.com

**Type:** array

**Title:** Product Tax Code

**Required:** No

**Examples:**

- `A_GEN_NOTAX`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Enter the product tax code supplied to you by Amazon.com |
| `marketplace_id` | object | No |  |

### merchant_release_date

Provide the merchant release date using YYYY-MM-DD format

**Type:** array

**Title:** Offering Release Date

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `value` | string | Yes | Provide the merchant release date using YYYY-MM-DD format |

### merchant_shipping_group

The ship configuration group for an offer. The ship configuration group is created and managed by the seller through the ship setting UI.

**Type:** array

**Title:** Merchant Shipping Group

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | The ship configuration group for an offer. The ship configuration group is created and managed by the seller through the ship setting UI. |
| `marketplace_id` | object | No |  |

### max_order_quantity

Max order quantity.

**Type:** array

**Title:** Max Order Quantity

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Max order quantity. |
| `marketplace_id` | object | No |  |

### gift_options

Provide gift card options

**Type:** array

**Title:** Gift Options

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `can_be_messaged` | boolean | No | If you can print a gift message with the item indicate that here. If left blank, defaults to 'No' |
| `can_be_wrapped` | boolean | No | If you can gift wrap an item indicate that here.  If left blank, defaults to 'No' |
| `marketplace_id` | object | No |  |

### main_offer_image_locator

Provide the location of the image

**Type:** array

**Title:** Main Offer Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL where the main offer-specific image of the product is located |

### other_offer_image_locator_1

Provide the location of the image

**Type:** array

**Title:** Other Offer Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_offer_image_locator_2

Provide the location of the image

**Type:** array

**Title:** Other Offer Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_offer_image_locator_3

Provide the location of the image

**Type:** array

**Title:** Other Offer Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_offer_image_locator_4

Provide the location of the image

**Type:** array

**Title:** Other Offer Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_offer_image_locator_5

Provide the location and source of the image

**Type:** array

**Title:** Other Offer Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### supplemental_condition_information

Provide the additional condition information on the non-new product.

**Type:** array

**Title:** Supplemental Condition Information

**Required:** No

**Examples:**

- `iPhone 14, Open Box Never Used, OEM, Original, Greater than 90%, With Tags, Pristine, Fully Functional`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `accessories` | string | No | Provide the type of accessory included in the non-new product. |
| `battery_life_percentage` | string | No | Provide the battery health information of the non-new product if it includes batteries. |
| `cosmetic` | string | No | Provide the overall cosmetic condition of the non-new product. |
| `features` | array | No | Provide the refurbishment type of the non-new product. |
| `functional_condition` | string | No | Provide the functional condition of the non-new product. |
| `marketplace_id` | object | No |  |
| `packaging` | string | No | Provide the packaging type of the non-new product |
| `source_type` | string | No | Provide the information on how the non-new product was sourced. |

### handmade_classification

Select the value that best describes how the product was produced

**Type:** array

**Title:** Handmade Classification

**Required:** No

**Examples:**

- `Hand-Altered`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Select the value that best describes how the product was produced |
| `marketplace_id` | object | No |  |

### product_description

The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum.

**Type:** array

**Title:** Product Description

**Required:** Yes

**Examples:**

- `This ham has been smoked for 12 hours...`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a text description of the product. This information will appear in paragraph form on the detail page of your product. Include unique product features, product line details, and product specifications. Do not use all caps. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### bullet_point

Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description.

**Type:** array

**Title:** Key Product Features

**Required:** Yes

**Examples:**

- `Delicious honey-apricot glaze`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Brief descriptive text, called out via a bullet point, regarding a specific aspect of the product. These display directly under or next to your product photo, it is useful to put interesting information in these fields. Do NOT use all caps or abbreviations. Please do NOT use for fabric content, care instructions or country as these are populated in different fields. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### generic_keyword

Provide specific search terms to help customers find your product.

**Type:** array

**Title:** Search Terms

**Required:** No

**Examples:**

- `Dark Chocolate, Apples, Cookies`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide any terms that may be relevant to customer searches. No repetition, no competitor brand names or ASINs. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### special_feature

An additional text field where you can indicate any additional relevant product information.

**Type:** array

**Title:** Additional Features

**Required:** No

**Examples:**

- `max number of images 36,  Operating Time 6 hours`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide any special features an item has that distinguish it from other, comparable products |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### style

The style of the item

**Type:** array

**Title:** Style Name

**Required:** No

**Examples:**

- `Mission; Art Deco; Jack Purcell`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### age_range_description

Provide the age range for which the sofa is intended or appropriate, helping customers choose suitable seating for different age groups.

**Type:** array

**Title:** Age Range Description

**Required:** No

**Examples:**

- `Baby`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the age range for which the sofa is intended or appropriate, helping customers choose suitable seating for different age groups. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### material

What material is the product made out of?

**Type:** array

**Title:** Material Type

**Required:** No

**Examples:**

- `nylon, wood, steel`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the primary materials used for manufacturing the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### fabric_type

List all fabrics separated by ','. Indicate with % composition. Always add "Viscose" or "Rayon" instead of "Bamboo", and "Azlon" for Soy

**Type:** array

**Title:** Fabric Type

**Required:** Yes

**Examples:**

- `90% cotton/10% rayon`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | List all fabrics separated by ','. Indicate with % composition. Always add "Viscose" or "Rayon" instead of "Bamboo", and "Azlon" for Soy |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### number_of_items

Provide the total number of identical items in the selling unit to the customer

**Type:** array

**Title:** Number of Items

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the total number of identical items in the selling unit to the customer |
| `marketplace_id` | object | No |  |

### item_package_quantity

Quantity of the item for sale in one package

**Type:** array

**Title:** Package Quantity

**Required:** No

**Examples:**

- `3`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of packages sold as part of a single item. An ASIN selling 5 boxes of paperclips with 100 paperclips per box would have item package quantity = '5' |
| `marketplace_id` | object | No |  |

### subject_character

Provide the primary character the item represents

**Type:** array

**Title:** Subject Character

**Required:** No

**Examples:**

- `Batman`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the primary character the item represents |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### color

Provide the color of the product

**Type:** array

**Title:** Color

**Required:** No

**Examples:**

- `Cranberry`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | No | Provide the color of the product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### size

The numeric or text version of the item's size.

**Type:** array

**Title:** Size

**Required:** No

**Examples:**

- `2T, 6X, 12, Small, X-Large, 18 months, 14 Tall, 28Wx32L`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the size of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### number_of_pieces

Number of pieces

**Type:** array

**Title:** Number of Pieces

**Required:** No

**Examples:**

- `1250`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of pieces within the unit being sold to the customer |
| `marketplace_id` | object | No |  |

### part_number

For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number.

**Type:** array

**Title:** Manufacturer Part Number

**Required:** No

**Examples:**

- `LE`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the part number. For many products, this will be identical to the model number however some manufacturers distinguish part number from model number |
| `marketplace_id` | object | No |  |

### collection

Enter the name of collection that an item belongs to.

**Type:** array

**Title:** Collection Name

**Required:** No

**Examples:**

- `Rivington`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Enter the name of collection that an item belongs to. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### warranty_type

Enter the type of warranty for this item

**Type:** array

**Title:** Warranty Type

**Required:** No

**Examples:**

- `Manufacturer`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Enter the type of warranty or select "No warranty" if there isn't one |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### item_shape

The shape of the item

**Type:** array

**Title:** Shape

**Required:** No

**Examples:**

- `Round; Oval; Square`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the shape of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### theme

Provide the primary high-level subject, concept, topic, motif, or idea of an item.

**Type:** array

**Title:** Theme

**Required:** No

**Examples:**

- `Sports`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### care_instructions

Provide instructions related to how to care for the item

**Type:** array

**Title:** Product Care Instructions

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide instructions related to how to care for the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### arm

Enter the specifications for the arm

**Type:** array

**Title:** Arm

**Required:** No

**Examples:**

- `Key`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `height` | array | No | Enter the arm height. |
| `marketplace_id` | object | No |  |
| `style` | array | No | Provide the design of the item's armrests, like rolled or square, or if it has no arms. |
| `width` | array | No | Provide the width of the arm/armrest of the item from the left edge to the right edge. |

### frame

The attribute indicates the Frame of the product

**Type:** array

**Title:** Frame

**Required:** No

**Examples:**

- `Eucalyptus Wood`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `color` | array | No | Provide the dominant color of the product's frame. |
| `joint_type` | array | No | Provide the technique used to connect the frame pieces, how the parts are joined together. |
| `marketplace_id` | object | No |  |
| `material` | array | No | Materal Frame is made of |

### manufacturer_grade

Enter the manufacturer grade

**Type:** array

**Title:** Manufacturer Grade

**Required:** No

**Examples:**

- `Type C`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the manufacturer grade value |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### configuration

Indicate the configuration of the item

**Type:** array

**Title:** Configuration

**Required:** No

**Examples:**

- `AWD Configuration`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Indicate the configuration of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### is_customizable

Is customizable?

**Type:** array

**Title:** Is Customizable?

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Specify if this product is customizable. |
| `marketplace_id` | object | No |  |

### material_feature

Provide the key material properties of the item, such as fabric type, texture, and durability characteristics.

**Type:** array

**Title:** Material Features

**Required:** No

**Examples:**

- `Compostable, biodegradable, Is food safe, Fragrance free, Plant based, etc.`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the characteristics of the materials used in the sofa's construction, highlighting unique or notable aspects of its composition. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### is_assembly_required

Indicate whether or not the item requires assembly by the customer

**Type:** array

**Title:** Required Assembly

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Indicate whether or not the item requires assembly by the customer |
| `marketplace_id` | object | No |  |

### item_firmness_description

Provide the cushion firmness level for the item, how soft or firm the seating feels, affecting comfort and support.

**Type:** array

**Title:** Item Firmness Description

**Required:** No

**Examples:**

- `Firm`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a description of the item's firmness |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### fill_material

Provide the material used to fill the interior of the item.

**Type:** array

**Title:** Fill Material

**Required:** No

**Examples:**

- `Cotton`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the material used to fill the interior of the item. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### item_display_dimensions

Provide the dimensions of the product, without packaging and fully assembled

**Type:** array

**Title:** Item Display Dimensions

**Required:** No

**Examples:**

- `5.7 Inches x 3.5 Inches x 1.8 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `height` | object | No | Provide the height of the product without packaging and fully assembled |
| `marketplace_id` | object | No |  |

#### item_display_dimensions[].height

Provide the height of the product without packaging and fully assembled

**Type:** object

**Title:** Item Display Height

**Required:** No

**Examples:**

- `1.8`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the numeric component of the height of the product without packaging and fully assembled |
| `unit` | string | Yes | Select the corresponding unit |

### assembly_instructions

Provide the step-by-step directions needed for a user to assemble the product.

**Type:** array

**Title:** Assembly Instructions

**Required:** No

**Examples:**

- `Position columns into holes of base and push in until snap buttons lock in place`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the step-by-step directions needed for a user to assemble the product. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### seating_capacity

Provide the maximum number of people the item can seat.

**Type:** array

**Title:** Seating Capacity

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the maximum number of people the item can seat. |
| `marketplace_id` | object | No |  |

### specification_met

Provide the standards or guidelines the item meets, ensuring quality and safety for intended use.

**Type:** array

**Title:** Specification Met

**Required:** No

**Examples:**

- `AMS, ASTM, MIL`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the industry standards or specifications the sofa has met, indicating compliance with recognized quality or safety benchmarks. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### suspension_type

Provide the suspenion typoe of the product

**Type:** array

**Title:** Suspension Type

**Required:** No

**Examples:**

- `Full`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the suspenion type of the product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### orientation

Provide the direction the item is facing or positioned, its layout or arrangement.

**Type:** array

**Title:** Orientation

**Required:** No

**Examples:**

- `Forward Facing`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the orientation of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### pattern

Provide the most prominent repeated decorative design of the item

**Type:** array

**Title:** Pattern

**Required:** No

**Examples:**

- `Floral, Geometric, Polka Dot`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the most prominent repeated decorative design of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### item_density

Enter the item density. Do not include a modifier.

**Type:** array

**Title:** Item Density

**Required:** No

**Examples:**

- `27 pounds per cubic foot`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Enter the item density. Do not include a modifier. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the sofa's compactness or density. |
| `marketplace_id` | object | No |  |

### item_form

Provide a value that represents the form of the item

**Type:** array

**Title:** Item Form

**Required:** No

**Examples:**

- `Sticks`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a value that represents the form of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### unit_count

Specify the number of units and the unit type of the product

**Type:** array

**Title:** Unit Count

**Required:** No

**Examples:**

- `72.0 Ounces`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | For products that are consumed by volume, weight, linear dimension, etc., provide the net quantity that would be shipped to a customer who orders one ASIN (e.g. 12 pack of 6 floz. bottles of water = 72, vs. a single 2 liter bottle = 2). For products consumed as individual units, provide the total number of units (pack of 12 pens = 12). For packed assortments of non-identical items, enter 1 |
| `type` | object | No | For items consumed by volume, weight, linear dimension etc., provide the unit of measure listed on the products. For products consumed as individual units, enter: count |
| `marketplace_id` | object | No |  |

#### unit_count[].type

For items consumed by volume, weight, linear dimension etc., provide the unit of measure listed on the products. For products consumed as individual units, enter: count

**Type:** object

**Title:** Unit Count Type

**Required:** No

**Examples:**

- `Ounces`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | For items consumed by volume, weight, linear dimension etc., provide the unit of measure listed on the products. For products consumed as individual units, enter: count |
| `language_tag` | object | Yes |  |

### product_site_launch_date

Date you wish this detail page to launch.

**Type:** array

**Title:** Launch Date

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `value` | string | Yes | Provide the date the product launches and should first be shown on the Amazon website (YYYY-MM-DD format). PSLD does not impact buyability or pre-order logic, it is used to indicate when a product will be visible and searchable on the Amazon website |

### included_components

Which components are included?

**Type:** array

**Title:** Included Components

**Required:** No

**Examples:**

- `Camera Body, Battery Pack`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the items that are included with this product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### league_name

Name of league associated with this event

**Type:** array

**Title:** League Name

**Required:** No

**Examples:**

- `NBA`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the league name associated with this product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### team_name

Provide the name of the sports team associated with the sofa, indicating the team-themed design or branding on the furniture.

**Type:** array

**Title:** Team Name

**Required:** No

**Examples:**

- `Seattle Seahawks`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the name of the sports team associated with the sofa, indicating the team-themed design or branding on the furniture. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Title:** Recommended Uses For Product

**Required:** No

**Examples:**

- `Cycling`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the recommended uses for the product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### is_fragile

Is the item fragile?

**Type:** array

**Title:** Is Fragile

**Required:** No

**Examples:**

- `TRUE`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Is the product glass or fragile? |
| `marketplace_id` | object | No |  |

### scent

Provide a description of the scent of the item

**Type:** array

**Title:** Scent Name

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a description of the scent of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### hand_orientation

Provide the hand orientation that the item is built for; left, right or both

**Type:** array

**Title:** Hand Orientation

**Required:** No

**Examples:**

- `Left Hand`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the hand orientation that the item is built for; left, right or both |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### back

The attribute indicates Back of the product

**Type:** array

**Title:** Back

**Required:** No

**Examples:**

- `Criss-Cross Back`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `style` | array | No | Provide a description of the the style of the item's back |

### certificate

The attribute indicates Certificate of the product

**Type:** array

**Title:** Certificate

**Required:** No

**Examples:**

- `PGTL`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `type` | array | No | Provide the certification or standard the item meets, indicating quality, safety, or environmental compliance. |

### cushion_style

Provide the design and shape of the item's cushions, the soft padded sections for sitting comfort.

**Type:** array

**Title:** Cushion Style

**Required:** No

**Examples:**

- `Adjustable, check seal`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the design or configuration of the sofa's cushions, indicating their shape, arrangement, or special features. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### embellishment_feature

Provide the decorative elements or designs on the item, enhancing its appearance or style.

**Type:** array

**Title:** Embellishment Feature

**Required:** No

**Examples:**

- `Buckle`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the decorative element attached to the sofa, enhancing its appearance or style. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### fire_rating

Provide the item's ability to resist fire, measured in time, ensuring safety standards are met.

**Type:** array

**Title:** Fire Rating

**Required:** No

**Examples:**

- `45 minutes, REI 30`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Amount of time the product is rated to protect against fire |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### length_range

Length range for blinds

**Type:** array

**Title:** Length Range

**Required:** No

**Examples:**

- `24-60" long`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Length range for blinds |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### room_type

Provide the intended room for the sofa, indicating the space where it is designed to be used and fit best.

**Type:** array

**Title:** Room Type

**Required:** No

**Examples:**

- `Bedroom`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the intended room for the sofa, indicating the space where it is designed to be used and fit best. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### seat

Provide the dimensions of the seat

**Type:** array

**Title:** Seat

**Required:** No

**Examples:**

- `Angstrom`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `back_interior_height` | array | No | Provide the height from the seat to the top of the back |
| `depth` | array | No | Provide the depth of the item's seat |
| `fill_material` | array | No | Provide the material or materials used to fill the seating surface of the item (e.g.  sofa). The seating surface can be the seating cushions or the seating surface when there are no seat cushions. |
| `height` | array | No | Provide the height of the product's seat |
| `interior_width` | array | No | Seat interior width designates the width measurement between the armrests or boundaries of a seat when unexpanded and placed in the manner in which it is expected to be used. It represents the available horizontal space within the seating area. |
| `marketplace_id` | object | No |  |

### thread

The attribute indicates the Thread of the product

**Type:** array

**Title:** Thread

**Required:** No

**Examples:**

- `UNC`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `count` | array | No | Provide the number of threads woven into the fabric, indicating quality and durability of the item's upholstery. |
| `marketplace_id` | object | No |  |

### weight_capacity

The attribute indicates Weight Capacity of the product

**Type:** array

**Title:** Weight Capacity

**Required:** No

**Examples:**

- `Milligrams`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `maximum` | array | No | Provide the maximum weight capacity for the item |

### width_range

Width range for blinds

**Type:** array

**Title:** Width Range

**Required:** No

**Examples:**

- `24-60" wide`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Width range for blinds |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### number_of_height_positions

Specify the number of height positions

**Type:** array

**Title:** Number of Height Positions

**Required:** No

**Examples:**

- `3`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Specify the number of height positions |
| `marketplace_id` | object | No |  |

### seat_cushion

This attribute specifies details on seat cushions that come with a piece of furniture.

**Type:** array

**Title:** Seat Cushion

**Required:** No

**Examples:**

- `2`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `has_removable_cover` | array | No | Indicate whether the seat cushion covers are removable. |
| `marketplace_id` | object | No |  |
| `quantity` | array | No | Provide the number of seat cushions that come with the item. |
| `removability` | array | No | Provide whether or not the seat cushion is removable or is built into the item. |

### back_cushion

This attribute specifies details on back cushions that come with a piece of furniture.

**Type:** array

**Title:** Back Cushion

**Required:** No

**Examples:**

- `2`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `removability` | array | No | Provide information on whether or not the back cushion of the seating area is removable. Back cushions support the back of the person when they are seated. |
| `thickness` | array | No | Provide the thickness of the back cushion. Thickness is measured from the back to the front of the cushion when placed vertically. |

### minimum_required_door_width

Provide the minimum width of a doorway needed for the piece of furniture to fit through. This information is typically used as a measurement for delivery.

**Type:** array

**Title:** Minimum Required Door Width

**Required:** No

**Examples:**

- `36.0 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the minimum width of a doorway needed for the piece of furniture to fit through. This information is typically used as a measurement for delivery. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the minimum doorway width needed for the sofa to pass through. |
| `marketplace_id` | object | No |  |

### furniture_leg

Describes the furniture item's legs

**Type:** array

**Title:** Furniture Leg

**Required:** No

**Examples:**

- `Straight, Fluted, Tapered`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `color` | array | No | Provide the dominant color of the item's legs. |
| `length` | array | No | The length of the furniture leg from top to bottom. |
| `marketplace_id` | object | No |  |
| `material` | array | No | Provide the material of the furniture item's legs. The leg material refers to the primary visible material of the legs and does not include the materials of leg parts such as tips. |
| `style` | array | No | Provide the style of the furniture item's legs. |

### seat_recline

Provide details on the reclining functionality of the furniture including whether it is manual or powered and how the reclining is triggered.

**Type:** array

**Title:** Seat Recline

**Required:** No

**Examples:**

- `Manual,
Push Botton`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `control_mechanism` | string | No | Provide the mechanism used to enable or drive the reclining or inclining motion. |
| `marketplace_id` | object | No |  |
| `operation_mode` | string | Yes | Provide whether the reclining functionality is manual or powered. |

### mattress

The attribute indicates Mattress of the product

**Type:** array

**Title:** Mattress

**Required:** No

**Examples:**

- `King, Queen, Twin`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `length_width` | array | No | Provide the length and width measurement of the item's mattress in ready-to-use condition. |
| `marketplace_id` | object | No |  |
| `size_name` | array | No | Provide the standard size name for the mattress that comes with the item. |
| `thickness` | array | No | Provide the thickness of the item's mattress. Thickness is measured from the top to the bottom of the mattress when it is placed flat. |

### upholstery

The attribute indicates Upholstery of the product

**Type:** array

**Title:** Upholstery

**Required:** No

**Examples:**

- `Upholstery Fabric Type: Cotton Blend,
Upholstery Material Composition.Material: Cotton,
Upholstery Material Composition.Percentage: 50`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `cleaning_code` | array | No | Provide the cleaning code of the upholstery material. The cleaning code specifies the appropriate cleaning method for a particular upholstery material. |
| `color` | array | No | Provide the dominant color of the upholstery of the item.  Upholstery is the fabric or material that covers majority of the furniture item. |
| `double_rub_count` | array | No | Provide the total number of rubs based on the Wyzenbeek testing method the fabric can sustain prior to being considered worn. |
| `fabric_type` | array | No | Provide the type of fabric used to upholster the majority of the furniture product. |
| `marketplace_id` | object | No |  |
| `material_composition` | array | No | Provide the material or materials that make up the upholstery fabric along with a content percent. |
| `rub_count` | array | No | Provide the total number of rubs based on the Martindale testing method the fabric can sustain before being considered worn. |

### sofa_type

Provide the specific design and primary function of the sofa, indicating its style and purpose within the seating furniture category.

**Type:** array

**Title:** Sofa Type

**Required:** No

**Examples:**

- `Setee`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the specific design and primary function of the sofa, indicating its style and purpose within the seating furniture category. |
| `marketplace_id` | object | No |  |

### indoor_outdoor_usage

Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor.

**Type:** array

**Title:** Indoor Outdoor Usage

**Required:** No

**Examples:**

- `Indoor`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide whether the product is made for indoor or outdoor use. If both, provide values for both indoor and outdoor. |
| `marketplace_id` | object | No |  |

### item_depth_width_height

Provide the length, width, and height of the item when set up for use, like a rug fully rolled out.

**Type:** array

**Title:** Item Dimensions D x W x H

**Required:** No

**Examples:**

- `40 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `depth` | object | Yes | Provide the measurement of the item from front to back in assembled state. For reclining sofas, depth is measured in an unreclined position. |
| `height` | object | Yes | Provide the measurement of the item from the floor to the top in an assembled state. For reclining sofas, height is measured in an unreclined position. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the measurement from side to side of the front of the item in an assembled state. This measurement is taken from armrest to armrest (for sofas with armrests)  in a non-reclined position |

#### item_depth_width_height[].depth

Provide the measurement of the item from front to back in assembled state. For reclining sofas, depth is measured in an unreclined position.

**Type:** object

**Title:** Item Depth Front To Back

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of the item from front to back in assembled state. For reclining sofas, depth is measured in an unreclined position. |
| `unit` | string | Yes | Select the unit of measure for Item depth. |

#### item_depth_width_height[].height

Provide the measurement of the item from the floor to the top in an assembled state. For reclining sofas, height is measured in an unreclined position.

**Type:** object

**Title:** Item Height Floor To Top

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of the item from the floor to the top in an assembled state. For reclining sofas, height is measured in an unreclined position. |
| `unit` | string | Yes | Select the unit of measure for item Height |

#### item_depth_width_height[].width

Provide the measurement from side to side of the front of the item in an assembled state. This measurement is taken from armrest to armrest (for sofas with armrests)  in a non-reclined position

**Type:** object

**Title:** Item Width Side To Side

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement from side to side of the front of the item in an assembled state. This measurement is taken from armrest to armrest (for sofas with armrests)  in a non-reclined position |
| `unit` | string | Yes | Select the unit of measure for item width. |

### seat_back_fill_material

Provide the material or materials used to fill the inner back seating area of the item (e.g. sofa). The seat back is the usually vertical portion of an item that supports the back of the person when they are seated.

**Type:** array

**Title:** Seat Back Fill Material

**Required:** No

**Examples:**

- `Cotton`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the material or materials used to fill the inner back seating area of the item (e.g. sofa). The seat back is the usually vertical portion of an item that supports the back of the person when they are seated. |
| `marketplace_id` | object | No |  |

### number_of_cup_holders

Provide the number of built-in holders for cups and beverages on the item, designed to keep drinks secure and accessible.

**Type:** array

**Title:** Number of Cup Holders

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of cup holders integrated into the item. Cup holders are specifically designed to accommodate a drinking cup or other beverage container. |
| `marketplace_id` | object | No |  |

### reclined_length

Provide the total length of the item from the top of the headrest to the bottom of the footrest when the item is fully reclined.

**Type:** array

**Title:** Reclined Length

**Required:** No

**Examples:**

- `67 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the total length of the item from the top of the headrest to the bottom of the footrest when the item is fully reclined. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the sofa's fully reclined length from headrest to footrest. |
| `marketplace_id` | object | No |  |

### recommended_number_of_people_for_assembly

Provide the amount of people recommended to assemble the item.

**Type:** array

**Title:** Recommended Number of People for Assembly

**Required:** No

**Examples:**

- `2`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the amount of people recommended to assemble the item. |
| `marketplace_id` | object | No |  |

### furniture_wall_clearance

Provide the clearance required between the item and a back wall or other obstruction in order for the item to fully recline.

**Type:** array

**Title:** Furniture Wall Clearance

**Required:** No

**Examples:**

- `3.5`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the clearance required between the item and a back wall or other obstruction in order for the item to fully recline. |
| `unit` | string | Yes | Provide the unit of measure used to indicate the minimum distance required between the item and a wall or rear obstruction. |
| `marketplace_id` | object | No |  |

### component_connector_assembly

Provide information about the assembly of the item's component connectors such as brackets and clips.

**Type:** array

**Title:** Component Connector Assembly

**Required:** No

**Examples:**

- `Built-In`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide information about the assembly of the item's component connectors such as brackets and clips. |
| `marketplace_id` | object | No |  |

### tools_recommended_for_assembly

Provide the type of tools recommended to assemble the components of the item.

**Type:** array

**Title:** Tools Recommended For Assembly

**Required:** No

**Examples:**

- `Hammer`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the type of tools recommended to assemble the components of the item. |
| `marketplace_id` | object | No |  |

### included_throw_pillow

Provide the details of the throw pillows inlcuded with the item.

**Type:** array

**Title:** Included Throw Pillow

**Required:** No

**Examples:**

- `Buckwheat, Linen, 1`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `cover_material` | array | No | Provide the type of material that the item's throw pillow cover is made of. |
| `fill_material` | array | No | Provide the type of material that the item's throw pillow is filled with. |
| `marketplace_id` | object | No |  |
| `quantity` | array | No | Provide the number of throw pillows included with the item. |

### sleeping_area_dimensions

Provide the length, width and height of the item's  sleeping area when item is converted into a bed.

**Type:** array

**Title:** Sleeping Area Dimensions

**Required:** No

**Examples:**

- `200 Centimeters`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `height` | object | Yes | Provide the height of the sleeping area of the item from floor to seating/sleeping surface when converted into a bed. |
| `length` | object | Yes | Provide the length of the sleeping area of the item when it is converted into a bed. The length is measured along the longer horizontal edge. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the width of the sleeping area of the item when it is converted into a bed. The width is measured along the shorter horizontal edge. |

#### sleeping_area_dimensions[].height

Provide the height of the sleeping area of the item from floor to seating/sleeping surface when converted into a bed.

**Type:** object

**Title:** Sleeping Area Height

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the height of the sleeping area of the item from floor to seating/sleeping surface when converted into a bed. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the height of the sleeping area of the item. |

#### sleeping_area_dimensions[].length

Provide the length of the sleeping area of the item when it is converted into a bed. The length is measured along the longer horizontal edge.

**Type:** object

**Title:** Sleeping Area Length

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the length of the sleeping area of the item when it is converted into a bed. The length is measured along the longer horizontal edge. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the length of the sleeping area of the item. |

#### sleeping_area_dimensions[].width

Provide the width of the sleeping area of the item when it is converted into a bed. The width is measured along the shorter horizontal edge.

**Type:** object

**Title:** Sleeping Area Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the width of the sleeping area of the item when it is converted into a bed. The width is measured along the shorter horizontal edge. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the width of the sleeping area of the item. |

### seat_cushion_configuration

Provide the arrangement of cushions on the item's seating area, whether a single cushion or multiple separate cushions.

**Type:** array

**Title:** Seat Cushion Configuration

**Required:** No

**Examples:**

- `Single Cushion Seat`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the arrangement of cushions on the sofa's seating area, indicating whether it has a single or multiple seat cushions. |
| `marketplace_id` | object | No |  |

### includes_all_assembly_tools

Provide whether or not all the tools required for assembling the item are included.

**Type:** array

**Title:** Includes All Assembly Tools

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether or not all the tools required for assembling the item are included. |
| `marketplace_id` | object | No |  |

### reclining_seat_count

Provide the number of reclining seats the item has. Reclining seats have a mechanism to adjust the position of the backrest and footrest.

**Type:** array

**Title:** Reclining Seat Count

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of reclining seats the item has. Reclining seats have a mechanism to adjust the position of the backrest and footrest. |
| `marketplace_id` | object | No |  |

### reclining_position_count

Provide the number of reclining positions the item offers, based on its adjustable back and footrest mechanism.

**Type:** array

**Title:** Reclining Position Count

**Required:** No

**Examples:**

- `2 Position`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the number of adjustable reclining positions the sofa offers, indicating the range of comfort settings available. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### cushion_construction

Provide the design and materials used to construct the item's cushions, affecting comfort and durability.

**Type:** array

**Title:** Cushion Construction

**Required:** No

**Examples:**

- `Fiber Wrapped Foam`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the design and fabrication method of the sofa cushions, including filling material, density, and stitching patterns. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### parentage_level

Specify whether a SKU is a parent or child

**Type:** array

**Title:** Parentage Level

**Required:** No

**Examples:**

- `Parent`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify whether a SKU is a parent or child |
| `marketplace_id` | object | No |  |

### child_parent_sku_relationship

The attribute indicates the Child Parent Sku Relationship of the product

**Type:** array

**Title:** Child Parent Sku Relationship

**Required:** No

**Examples:**

- `Accessory`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `child_relationship_type` | string | Yes | The relationship that the child has to the parent |
| `marketplace_id` | object | No |  |
| `parent_sku` | string | No | The SKU of the parent item |

### variation_theme

Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping.

**Type:** array

**Title:** Variation Theme

**Required:** No

**Examples:**

- `Size/Color`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `name` | string | Yes | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |

### safety_warning

List safety information customers should know.

**Type:** array

**Title:** Safety Warning

**Required:** No

**Examples:**

- `Consult with a doctor before using this product.`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide any safety warnings printed on the item's packaging |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### country_of_origin

The country in which the product was published.

**Type:** array

**Title:** Country of Publication

**Required:** Yes

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Select the product's country of origin |
| `marketplace_id` | object | No |  |

### batteries_required

Indicate if batteries are required.

**Type:** array

**Title:** Are Batteries Required

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Select "yes" if batteries are required to power the item (or if the item is a battery) or "no" if they are not. Please note that an internal rechargeable battery is also considered a battery |
| `marketplace_id` | object | No |  |

### batteries_included

Indicate if batteries are included with the product.

**Type:** array

**Title:** Batteries are Included

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Select "yes" if batteries are contained in the product (e.g. batteries inside a pair of Bluetooth headphones) and/or included with the product (e.g. batteries packed separately with a camera), otherwise select "no" |
| `marketplace_id` | object | No |  |

### battery

Provide battery information

**Type:** array

**Title:** Battery

**Required:** No

**Examples:**

- `Alkaline`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `cell_composition` | array | No | What type or composition is the battery? |
| `cell_composition_other_than_listed` | array | No | Provide the components of the item's battery cell that are not already listed under battery cell composition. |
| `marketplace_id` | object | No |  |
| `weight` | array | No | Provide the total net weight of the batteries included. This is the weight of the standalone batteries not including packaging or the device it may be used in |

### num_batteries

Provide the quantity and type of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided

**Type:** array

**Title:** Number of Batteries

**Required:** Conditionally

**Examples:**

- `1 AA, 2 AAA`

**Selectors:** `marketplace_id`, `type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `quantity` | integer | Yes | Specify the number of batteries needed to power the item.  If batteries are included with the item be sure to account for spare batteries provided |
| `type` | string | Yes | Provide battery type needed to power the item, including spares if included. Some options may be moved under other attribute eg. IEC code |

### number_of_lithium_metal_cells

Total number of Lithium cells (of type "Metal") in the product, where the cell isn't contained in an encased battery.

**Type:** array

**Title:** Number of Lithium Metal Cells

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Specify the total number of Lithium Metal cells in the product where the cell isn't contained in an encased battery (e.g. coin cells) |
| `marketplace_id` | object | No |  |

### number_of_lithium_ion_cells

Total number of Lithium cells (of type "Ion") in the product, where the cell isn't contained in an encased battery.

**Type:** array

**Title:** Number of Lithium-ion Cells

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Specify the total number of Lithium-ion cells in the product where the cell isn't contained in an encased battery. For example, an AA battery is considered a cell |
| `marketplace_id` | object | No |  |

### lithium_battery

The attribute indicates the Lithium Battery of the product

**Type:** array

**Title:** Lithium Battery

**Required:** No

**Examples:**

- `Milligrams`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `energy_content` | array | No | Watt hours of each battery (or cell) in unit |
| `marketplace_id` | object | No |  |
| `packaging` | array | No | Choices are "batteries_only" (If battery is a standalone) "batteries_contained_in_equipment" (if battery is assembled in the item) or "batteries_packed_with_equipment" (If battery is included in the item packaging but not assembled in the item) |
| `weight` | array | No | Provide the weight of lithium contained in the cell or battery |

### supplier_declared_dg_hz_regulation

Provide the regulations that apply to the item if it is classified as a dangerous good, hazardous material, substance, or waste.

**Type:** array

**Title:** Dangerous Goods Regulations

**Required:** Yes

**Examples:**

- `GHS, Storage, Transportation`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the regulations that apply to the item if it is classified as a dangerous good, hazardous material, substance, or waste. |
| `marketplace_id` | object | No |  |

### ghs

Provide the Global Harmonized System (GHS) information

**Type:** array

**Title:** GHS

**Required:** No

**Examples:**

- `NGK`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `classification` | array | No | Provide the Global Harmonized System (GHS) CLP classification for the product |
| `marketplace_id` | object | No |  |

### hazmat

Provide hazmat information that is relevant to the product based on the aspect selected

**Type:** array

**Title:** Hazmat

**Required:** Conditionally

**Examples:**

- `UN1993`

**Selectors:** `marketplace_id`, `aspect`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `aspect` | string | Yes | Select the aspect or regulatory body used for the hazardous product information |
| `value` | string | Yes | Provide hazmat information that is relevant to the product based on the aspect selected |
| `marketplace_id` | object | No |  |

### safety_data_sheet_url

Provide the SDS/MSDS URL. Required for Hazardous material SDS/MSDS provides information such as physical data (flashpoint, pH, etc.), health concerns, storage, and transportation information for potentially dangerous substances.

**Type:** array

**Title:** Safety Data Sheet (SDS or MSDS) URL

**Required:** No

**Examples:**

- `www.safetysheetsRus.com/hazardous_substance/msds.pdf`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the web address for the Safety Data Sheet, containing essential safety information for potentially hazardous materials. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### item_weight

A number with up to 10 digits to the left of the decimal point and 2 digits to the right of the decimal point. Please use decimal points, commas are not accepted.

**Type:** array

**Title:** Item Weight

**Required:** No

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the item weight numeric value (not including the packaging) |
| `unit` | string | Yes | Provide unit for item weight |
| `marketplace_id` | object | No |  |

### mfg_warranty_description_type

Provide the details on the manufacturer's warranty coverage for the item, explaining what is covered and for how long.

**Type:** array

**Title:** Mfg Warranty Type (i.e. Parts, Labor)

**Required:** No

**Examples:**

- `Yearly`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the mfg warranty description type |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### california_proposition_65

Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required

**Type:** array

**Title:** California Proposition 65

**Required:** No

**Examples:**

- `Furniture; Lead`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `compliance_type` | string | Yes | Select the warning type applicable to your product, if any. You certify that the warning provided satisfies legal requirements and that you’ll remove a warning previously provided only if it is no longer legally required. |
| `chemical_names` | array | No | If you selected the Food, Furniture, or Chemical warning you must indicate a chemical(s). You certify that the chemical(s) satisfies legal requirements and that you’ll remove a chemical previously provided only if it is no longer legally required. |
| `marketplace_id` | object | No |  |

### fcc_radio_frequency_emission_compliance

Provide details on compliance to FCC regulations for products that may emit radio frequencies.

**Type:** array

**Title:** FCC Radio Frequency Emission Compliance

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `registration_status` | string | Yes | Indicate whether this product is capable of emitting radio frequency energy, and if so, what type of FCC RF equipment authorization this product has. |
| `identification_number` | string | No | If the device has an FCC ID, provide it. |
| `point_of_contact_name` | string | No | If the device has a Supplier's Declaration of Conformity, provide the name of the point of contact for the Responsible Party, as defined by the FCC. |
| `point_of_contact_address` | string | No | If the device has a Supplier's Declaration of Conformity, provide a US mailing address for the Responsible Party, as defined by the FCC. |
| `point_of_contact_email` | string | No | If the device has an SDoC, provide an e-mail address (in this field) or a US phone number (in the next field) for the Responsible Party, as defined by the FCC. If you provide a phone number in the next field, you may enter "N/A" in this field. |
| `point_of_contact_phone_number` | string | No | If the device has an SDoC, provide a US phone number (in this field) or an e-mail address (in the prior field) for the Responsible Party, as defined by the FCC. If you provide an e-mail address in the prior field, you may enter "N/A" in this field. |
| `marketplace_id` | object | No |  |

### regulatory_compliance_certification

Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers.

**Type:** array

**Title:** Regulatory Compliance Certification

**Required:** Conditionally

**Examples:**

- `FDA 510(k) Number,
F2345G234`

**Selectors:** `marketplace_id`, `regulation_type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `regulation_type` | string | Yes | Select applicable regulation type |
| `value` | string | Yes | Provide the regulatory identification associated with the regulation type. |
| `marketplace_id` | object | No |  |

### dsa_responsible_party_address

Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations.

**Type:** array

**Title:** Responsible Person's Email or Electronic Address

**Required:** No

**Examples:**

- `rsp-email@example.com`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations. |
| `marketplace_id` | object | No |  |

### compliance_media

Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager.

**Type:** array

**Title:** Compliance Media

**Required:** Conditionally

**Examples:**

- `Installation Manual`

**Selectors:** `marketplace_id`, `content_type`, `content_language`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `content_type` | string | Yes | Please enter the content type of the compliance document. |
| `content_language` | string | Yes | Provide the language used for the content of the compliance media. |
| `source_location` | string | Yes | Provide the source location of the compliance media. |
| `marketplace_id` | object | No |  |

### gpsr_safety_attestation

Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it.

**Type:** array

**Title:** GPSR Safety Attestation

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it. |
| `marketplace_id` | object | No |  |

### gpsr_manufacturer_reference

Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL.

**Type:** array

**Title:** GPSR Manufacturer Reference

**Required:** No

**Examples:**

- `abc@example.com`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `gpsr_manufacturer_email_address` | string | No | Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL. |
| `marketplace_id` | object | No |  |

### contains_pfas

Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals.

**Type:** array

**Title:** Contains PFAS

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals. |
| `marketplace_id` | object | No |  |

### ships_globally

Provide whether the item can be shipped globally by Amazon 

**Type:** array

**Title:** Ships Globally

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether the item can be shipped globally by Amazon  |
| `marketplace_id` | object | No |  |

### ghs_chemical_h_code

Provide the GHS chemical hazard codes for the chemical substance/mixture in order to display warnings to customers.

**Type:** array

**Title:** GHS Chemical H Code

**Required:** Conditionally

**Examples:**

- `H200`

**Selectors:** `marketplace_id`, `value`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the GHS chemical hazard codes for the chemical substance/mixture in order to display warnings to customers. |
| `marketplace_id` | object | No |  |

### main_product_image_locator

The attribute indicates the Main Product Image Locator of the product

**Type:** array

**Title:** Main Product Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL where the main offer-specific image of the product is located. |

### other_product_image_locator_1

The attribute indicates the Other Product Image Locator 1 of the product

**Type:** array

**Title:** Other Product Image Locator 1

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_2

The attribute indicates the Other Product Image Locator 2 of the product

**Type:** array

**Title:** Other Product Image Locator 2

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_3

The attribute indicates the Other Product Image Locator 3 of the product

**Type:** array

**Title:** Other Product Image Locator 3

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_4

The attribute indicates the Other Product Image Locator 4 of the product

**Type:** array

**Title:** Other Product Image Locator 4

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_5

The attribute indicates the Other Product Image Locator 5 of the product

**Type:** array

**Title:** Other Product Image Locator 5

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_6

The attribute indicates the Other Product Image Locator 6 of the product

**Type:** array

**Title:** Other Product Image Locator 6

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_7

The attribute indicates the Other Product Image Locator 7 of the product

**Type:** array

**Title:** Other Product Image Locator 7

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### other_product_image_locator_8

The attribute indicates the Other Product Image Locator 8 of the product

**Type:** array

**Title:** Other Product Image Locator 8

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL for additional images of your product. These images will be shown on the detail page when the customer clicks through to see other views associated with the product. |

### swatch_product_image_locator

The attribute indicates the Swatch Product Image Locator of the product

**Type:** array

**Title:** Swatch Product Image Locator

**Required:** No

**Examples:**

- `Feed`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `media_location` | string | Yes | The URL where an image of a color swatch from the product is located |

### item_package_dimensions

Provide the item's package dimensions

**Type:** array

**Title:** Item Package Dimensions

**Required:** No

**Examples:**

- `10 x 2 x 2.7 inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `length` | object | Yes | Provide the package length |
| `width` | object | Yes | Provide the package width |
| `height` | object | Yes | Provide the package height |
| `marketplace_id` | object | No |  |

#### item_package_dimensions[].length

Provide the package length

**Type:** object

**Title:** Package Length

**Required:** No

**Examples:**

- `10`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the package length as a numeric value. |
| `unit` | string | Yes | Select the unit of measure for Package Length. If a value is provided for Package Length, you must also enter the corresponding unit. |

#### item_package_dimensions[].width

Provide the package width

**Type:** object

**Title:** Package Width

**Required:** No

**Examples:**

- `2`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the package width as a numeric value. |
| `unit` | string | Yes | Select the unit of measure for Package Width. If a value is provided for Package Width, you must also enter the corresponding unit. |

#### item_package_dimensions[].height

Provide the package height

**Type:** object

**Title:** Package Height

**Required:** No

**Examples:**

- `2.7`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the package height as a numeric value. |
| `unit` | string | Yes | Select the unit of measure for Package Height. If a value is provided for Package Height, you must also enter the corresponding unit. |

### item_package_weight

The weight in original package

**Type:** array

**Title:** Package Weight

**Required:** No

**Examples:**

- `14.89`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | This attribute represents the weight of the item plus the packaging. If your item is shipped to the customer in multiple packages, enter the dimensions of the heaviest package |
| `unit` | string | Yes | Select the unit of measure for Package Weight. If a value is provided for Package Weight, you must also enter the corresponding unit. |
| `marketplace_id` | object | No |  |

### item_display_weight

Provide the item weight if the product is a solid

**Type:** array

**Title:** Item Display Weight

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the item weight (numeric) if the product is a solid |
| `unit` | string | Yes | Select the corresponding unit |
| `marketplace_id` | object | No |  |

### master_pack_layers_per_pallet_quantity

Provide the number of layers of master packs held on a pallet packed for storage (known as Hi).

**Type:** array

**Title:** Master Pack Layers per Pallet Quantity

**Required:** No

**Examples:**

- `5`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of layers of master packs held on a pallet packed for storage (known as Hi). |
| `marketplace_id` | object | No |  |

### master_packs_per_layer_quantity

Provide the number of master packs of the product in each layer on a pallet (known as Ti).

**Type:** array

**Title:** Master Packs Per Layer Quantity

**Required:** No

**Examples:**

- `9`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of master packs of the product in each layer on a pallet (known as Ti). |
| `marketplace_id` | object | No |  |

