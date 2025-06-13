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

## Nested Required Fields

| Field Path | Requirement |
|-----------|-------------|
| `age_range_description[item].language_tag` | Required in age_range_description[item] object |
| `age_range_description[item].value` | Required in age_range_description[item] object |
| `assembly_instructions[item].language_tag` | Required in assembly_instructions[item] object |
| `assembly_instructions[item].value` | Required in assembly_instructions[item] object |
| `base[item].color[item].language_tag` | Required in base[item].color[item] object |
| `base[item].color[item].language_tag` | Required in base[item].color[item] object |
| `base[item].color[item].value` | Required in base[item].color[item] object |
| `base[item].color[item].value` | Required in base[item].color[item] object |
| `base[item].material[item].language_tag` | Required in base[item].material[item] object |
| `base[item].material[item].language_tag` | Required in base[item].material[item] object |
| `base[item].material[item].value` | Required in base[item].material[item] object |
| `base[item].material[item].value` | Required in base[item].material[item] object |
| `base_type[item].language_tag` | Required in base_type[item] object |
| `base_type[item].value` | Required in base_type[item] object |
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
| `cabinet[item].configuration[item].value` | Required in cabinet[item].configuration[item] object |
| `cabinet[item].configuration[item].value` | Required in cabinet[item].configuration[item] object |
| `cabinet_interior_dimensions[item].depth` | Required in cabinet_interior_dimensions[item] object |
| `cabinet_interior_dimensions[item].depth.unit` | Required in cabinet_interior_dimensions[item].depth object |
| `cabinet_interior_dimensions[item].depth.unit` | Required in cabinet_interior_dimensions[item].depth object |
| `cabinet_interior_dimensions[item].depth.value` | Required in cabinet_interior_dimensions[item].depth object |
| `cabinet_interior_dimensions[item].depth.value` | Required in cabinet_interior_dimensions[item].depth object |
| `cabinet_interior_dimensions[item].height` | Required in cabinet_interior_dimensions[item] object |
| `cabinet_interior_dimensions[item].height.unit` | Required in cabinet_interior_dimensions[item].height object |
| `cabinet_interior_dimensions[item].height.unit` | Required in cabinet_interior_dimensions[item].height object |
| `cabinet_interior_dimensions[item].height.value` | Required in cabinet_interior_dimensions[item].height object |
| `cabinet_interior_dimensions[item].height.value` | Required in cabinet_interior_dimensions[item].height object |
| `cabinet_interior_dimensions[item].type` | Required in cabinet_interior_dimensions[item] object |
| `cabinet_interior_dimensions[item].width` | Required in cabinet_interior_dimensions[item] object |
| `cabinet_interior_dimensions[item].width.unit` | Required in cabinet_interior_dimensions[item].width object |
| `cabinet_interior_dimensions[item].width.unit` | Required in cabinet_interior_dimensions[item].width object |
| `cabinet_interior_dimensions[item].width.value` | Required in cabinet_interior_dimensions[item].width object |
| `cabinet_interior_dimensions[item].width.value` | Required in cabinet_interior_dimensions[item].width object |
| `california_proposition_65[item].compliance_type` | Required in california_proposition_65[item] object |
| `care_instructions[item].language_tag` | Required in care_instructions[item] object |
| `care_instructions[item].value` | Required in care_instructions[item] object |
| `child_parent_sku_relationship[item].child_relationship_type` | Required in child_parent_sku_relationship[item] object |
| `color[item].language_tag` | Required in color[item] object |
| `compliance_media[item].content_language` | Required in compliance_media[item] object |
| `compliance_media[item].content_type` | Required in compliance_media[item] object |
| `compliance_media[item].source_location` | Required in compliance_media[item] object |
| `condition_note[item].language_tag` | Required in condition_note[item] object |
| `condition_note[item].value` | Required in condition_note[item] object |
| `condition_type[item].value` | Required in condition_type[item] object |
| `contains_pfas[item].value` | Required in contains_pfas[item] object |
| `country_of_origin[item].value` | Required in country_of_origin[item] object |
| `customer_package_type[item].language_tag` | Required in customer_package_type[item] object |
| `customer_package_type[item].value` | Required in customer_package_type[item] object |
| `desk_design[item].value` | Required in desk_design[item] object |
| `desk_return_dimensions[item].depth.unit` | Required in desk_return_dimensions[item].depth object |
| `desk_return_dimensions[item].depth.unit` | Required in desk_return_dimensions[item].depth object |
| `desk_return_dimensions[item].depth.value` | Required in desk_return_dimensions[item].depth object |
| `desk_return_dimensions[item].depth.value` | Required in desk_return_dimensions[item].depth object |
| `desk_return_dimensions[item].height.unit` | Required in desk_return_dimensions[item].height object |
| `desk_return_dimensions[item].height.unit` | Required in desk_return_dimensions[item].height object |
| `desk_return_dimensions[item].height.value` | Required in desk_return_dimensions[item].height object |
| `desk_return_dimensions[item].height.value` | Required in desk_return_dimensions[item].height object |
| `desk_return_dimensions[item].width.unit` | Required in desk_return_dimensions[item].width object |
| `desk_return_dimensions[item].width.unit` | Required in desk_return_dimensions[item].width object |
| `desk_return_dimensions[item].width.value` | Required in desk_return_dimensions[item].width object |
| `desk_return_dimensions[item].width.value` | Required in desk_return_dimensions[item].width object |
| `distressed_finish_type[item].language_tag` | Required in distressed_finish_type[item] object |
| `distressed_finish_type[item].value` | Required in distressed_finish_type[item] object |
| `drawer[item].glide_material[item].language_tag` | Required in drawer[item].glide_material[item] object |
| `drawer[item].glide_material[item].language_tag` | Required in drawer[item].glide_material[item] object |
| `drawer[item].glide_material[item].value` | Required in drawer[item].glide_material[item] object |
| `drawer[item].glide_material[item].value` | Required in drawer[item].glide_material[item] object |
| `drawer[item].glide_mechanism[item].language_tag` | Required in drawer[item].glide_mechanism[item] object |
| `drawer[item].glide_mechanism[item].language_tag` | Required in drawer[item].glide_mechanism[item] object |
| `drawer[item].glide_mechanism[item].value` | Required in drawer[item].glide_mechanism[item] object |
| `drawer[item].glide_mechanism[item].value` | Required in drawer[item].glide_mechanism[item] object |
| `drawer_interior_dimensions[item].depth` | Required in drawer_interior_dimensions[item] object |
| `drawer_interior_dimensions[item].depth.unit` | Required in drawer_interior_dimensions[item].depth object |
| `drawer_interior_dimensions[item].depth.unit` | Required in drawer_interior_dimensions[item].depth object |
| `drawer_interior_dimensions[item].depth.value` | Required in drawer_interior_dimensions[item].depth object |
| `drawer_interior_dimensions[item].depth.value` | Required in drawer_interior_dimensions[item].depth object |
| `drawer_interior_dimensions[item].height` | Required in drawer_interior_dimensions[item] object |
| `drawer_interior_dimensions[item].height.unit` | Required in drawer_interior_dimensions[item].height object |
| `drawer_interior_dimensions[item].height.unit` | Required in drawer_interior_dimensions[item].height object |
| `drawer_interior_dimensions[item].height.value` | Required in drawer_interior_dimensions[item].height object |
| `drawer_interior_dimensions[item].height.value` | Required in drawer_interior_dimensions[item].height object |
| `drawer_interior_dimensions[item].type` | Required in drawer_interior_dimensions[item] object |
| `drawer_interior_dimensions[item].width` | Required in drawer_interior_dimensions[item] object |
| `drawer_interior_dimensions[item].width.unit` | Required in drawer_interior_dimensions[item].width object |
| `drawer_interior_dimensions[item].width.unit` | Required in drawer_interior_dimensions[item].width object |
| `drawer_interior_dimensions[item].width.value` | Required in drawer_interior_dimensions[item].width object |
| `drawer_interior_dimensions[item].width.value` | Required in drawer_interior_dimensions[item].width object |
| `drawer_pedestal_count[item].value` | Required in drawer_pedestal_count[item] object |
| `drawer_type[item].language_tag` | Required in drawer_type[item] object |
| `drawer_type[item].value` | Required in drawer_type[item] object |
| `drawer_weight_capacity[item].type` | Required in drawer_weight_capacity[item] object |
| `drawer_weight_capacity[item].unit_decimal` | Required in drawer_weight_capacity[item] object |
| `drawer_weight_capacity[item].unit_decimal.unit` | Required in drawer_weight_capacity[item].unit_decimal object |
| `drawer_weight_capacity[item].unit_decimal.unit` | Required in drawer_weight_capacity[item].unit_decimal object |
| `drawer_weight_capacity[item].unit_decimal.value` | Required in drawer_weight_capacity[item].unit_decimal object |
| `drawer_weight_capacity[item].unit_decimal.value` | Required in drawer_weight_capacity[item].unit_decimal object |
| `dsa_responsible_party_address[item].value` | Required in dsa_responsible_party_address[item] object |
| `edition[item].language_tag` | Required in edition[item] object |
| `edition[item].value` | Required in edition[item] object |
| `externally_assigned_product_identifier[item].type` | Required in externally_assigned_product_identifier[item] object |
| `externally_assigned_product_identifier[item].value` | Required in externally_assigned_product_identifier[item] object |
| `fcc_radio_frequency_emission_compliance[item].registration_status` | Required in fcc_radio_frequency_emission_compliance[item] object |
| `finish_type[item].language_tag` | Required in finish_type[item] object |
| `finish_type[item].value` | Required in finish_type[item] object |
| `frame[item].joint_type[item].language_tag` | Required in frame[item].joint_type[item] object |
| `frame[item].joint_type[item].language_tag` | Required in frame[item].joint_type[item] object |
| `frame[item].joint_type[item].value` | Required in frame[item].joint_type[item] object |
| `frame[item].joint_type[item].value` | Required in frame[item].joint_type[item] object |
| `frame[item].material[item].language_tag` | Required in frame[item].material[item] object |
| `frame[item].material[item].language_tag` | Required in frame[item].material[item] object |
| `frame[item].material[item].value` | Required in frame[item].material[item] object |
| `frame[item].material[item].value` | Required in frame[item].material[item] object |
| `fulfillment_availability[item].fulfillment_channel_code` | Required in fulfillment_availability[item] object |
| `furniture_finish[item].language_tag` | Required in furniture_finish[item] object |
| `furniture_finish[item].value` | Required in furniture_finish[item] object |
| `furniture_leg[item].material[item].language_tag` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].material[item].language_tag` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].material[item].value` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].material[item].value` | Required in furniture_leg[item].material[item] object |
| `furniture_leg[item].style[item].language_tag` | Required in furniture_leg[item].style[item] object |
| `furniture_leg[item].style[item].language_tag` | Required in furniture_leg[item].style[item] object |
| `furniture_leg[item].style[item].value` | Required in furniture_leg[item].style[item] object |
| `furniture_leg[item].style[item].value` | Required in furniture_leg[item].style[item] object |
| `generic_keyword[item].language_tag` | Required in generic_keyword[item] object |
| `generic_keyword[item].value` | Required in generic_keyword[item] object |
| `ghs[item].classification[item].class` | Required in ghs[item].classification[item] object |
| `ghs[item].classification[item].class` | Required in ghs[item].classification[item] object |
| `ghs_chemical_h_code[item].value` | Required in ghs_chemical_h_code[item] object |
| `gpsr_safety_attestation[item].value` | Required in gpsr_safety_attestation[item] object |
| `handmade_classification[item].value` | Required in handmade_classification[item] object |
| `has_finished_back[item].value` | Required in has_finished_back[item] object |
| `hazmat[item].aspect` | Required in hazmat[item] object |
| `hazmat[item].value` | Required in hazmat[item] object |
| `hutch[item].depth_width_height[item].depth.unit` | Required in hutch[item].depth_width_height[item].depth object |
| `hutch[item].depth_width_height[item].depth.unit` | Required in hutch[item].depth_width_height[item].depth object |
| `hutch[item].depth_width_height[item].depth.unit` | Required in hutch[item].depth_width_height[item].depth object |
| `hutch[item].depth_width_height[item].depth.value` | Required in hutch[item].depth_width_height[item].depth object |
| `hutch[item].depth_width_height[item].depth.value` | Required in hutch[item].depth_width_height[item].depth object |
| `hutch[item].depth_width_height[item].depth.value` | Required in hutch[item].depth_width_height[item].depth object |
| `hutch[item].depth_width_height[item].height.unit` | Required in hutch[item].depth_width_height[item].height object |
| `hutch[item].depth_width_height[item].height.unit` | Required in hutch[item].depth_width_height[item].height object |
| `hutch[item].depth_width_height[item].height.unit` | Required in hutch[item].depth_width_height[item].height object |
| `hutch[item].depth_width_height[item].height.value` | Required in hutch[item].depth_width_height[item].height object |
| `hutch[item].depth_width_height[item].height.value` | Required in hutch[item].depth_width_height[item].height object |
| `hutch[item].depth_width_height[item].height.value` | Required in hutch[item].depth_width_height[item].height object |
| `hutch[item].depth_width_height[item].width.unit` | Required in hutch[item].depth_width_height[item].width object |
| `hutch[item].depth_width_height[item].width.unit` | Required in hutch[item].depth_width_height[item].width object |
| `hutch[item].depth_width_height[item].width.unit` | Required in hutch[item].depth_width_height[item].width object |
| `hutch[item].depth_width_height[item].width.value` | Required in hutch[item].depth_width_height[item].width object |
| `hutch[item].depth_width_height[item].width.value` | Required in hutch[item].depth_width_height[item].width object |
| `hutch[item].depth_width_height[item].width.value` | Required in hutch[item].depth_width_height[item].width object |
| `hutch[item].material[item].language_tag` | Required in hutch[item].material[item] object |
| `hutch[item].material[item].language_tag` | Required in hutch[item].material[item] object |
| `hutch[item].material[item].value` | Required in hutch[item].material[item] object |
| `hutch[item].material[item].value` | Required in hutch[item].material[item] object |
| `included_components[item].language_tag` | Required in included_components[item] object |
| `included_components[item].value` | Required in included_components[item] object |
| `includes_all_assembly_tools[item].value` | Required in includes_all_assembly_tools[item] object |
| `is_assembly_required[item].value` | Required in is_assembly_required[item] object |
| `is_customizable[item].value` | Required in is_customizable[item] object |
| `is_electric[item].value` | Required in is_electric[item] object |
| `is_ul_listed[item].value` | Required in is_ul_listed[item] object |
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
| `item_display_dimensions[item].depth.unit` | Required in item_display_dimensions[item].depth object |
| `item_display_dimensions[item].depth.unit` | Required in item_display_dimensions[item].depth object |
| `item_display_dimensions[item].depth.value` | Required in item_display_dimensions[item].depth object |
| `item_display_dimensions[item].depth.value` | Required in item_display_dimensions[item].depth object |
| `item_display_dimensions[item].diameter.unit` | Required in item_display_dimensions[item].diameter object |
| `item_display_dimensions[item].diameter.unit` | Required in item_display_dimensions[item].diameter object |
| `item_display_dimensions[item].diameter.value` | Required in item_display_dimensions[item].diameter object |
| `item_display_dimensions[item].diameter.value` | Required in item_display_dimensions[item].diameter object |
| `item_display_dimensions[item].height.unit` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].height.unit` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].height.value` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].height.value` | Required in item_display_dimensions[item].height object |
| `item_display_dimensions[item].length.unit` | Required in item_display_dimensions[item].length object |
| `item_display_dimensions[item].length.unit` | Required in item_display_dimensions[item].length object |
| `item_display_dimensions[item].length.value` | Required in item_display_dimensions[item].length object |
| `item_display_dimensions[item].length.value` | Required in item_display_dimensions[item].length object |
| `item_display_dimensions[item].width.unit` | Required in item_display_dimensions[item].width object |
| `item_display_dimensions[item].width.unit` | Required in item_display_dimensions[item].width object |
| `item_display_dimensions[item].width.value` | Required in item_display_dimensions[item].width object |
| `item_display_dimensions[item].width.value` | Required in item_display_dimensions[item].width object |
| `item_display_weight[item].unit` | Required in item_display_weight[item] object |
| `item_display_weight[item].value` | Required in item_display_weight[item] object |
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
| `keyboard_tray[item].length_width[item].length` | Required in keyboard_tray[item].length_width[item] object |
| `keyboard_tray[item].length_width[item].length` | Required in keyboard_tray[item].length_width[item] object |
| `keyboard_tray[item].length_width[item].length.unit` | Required in keyboard_tray[item].length_width[item].length object |
| `keyboard_tray[item].length_width[item].length.unit` | Required in keyboard_tray[item].length_width[item].length object |
| `keyboard_tray[item].length_width[item].length.unit` | Required in keyboard_tray[item].length_width[item].length object |
| `keyboard_tray[item].length_width[item].length.value` | Required in keyboard_tray[item].length_width[item].length object |
| `keyboard_tray[item].length_width[item].length.value` | Required in keyboard_tray[item].length_width[item].length object |
| `keyboard_tray[item].length_width[item].length.value` | Required in keyboard_tray[item].length_width[item].length object |
| `keyboard_tray[item].length_width[item].width` | Required in keyboard_tray[item].length_width[item] object |
| `keyboard_tray[item].length_width[item].width` | Required in keyboard_tray[item].length_width[item] object |
| `keyboard_tray[item].length_width[item].width.unit` | Required in keyboard_tray[item].length_width[item].width object |
| `keyboard_tray[item].length_width[item].width.unit` | Required in keyboard_tray[item].length_width[item].width object |
| `keyboard_tray[item].length_width[item].width.unit` | Required in keyboard_tray[item].length_width[item].width object |
| `keyboard_tray[item].length_width[item].width.value` | Required in keyboard_tray[item].length_width[item].width object |
| `keyboard_tray[item].length_width[item].width.value` | Required in keyboard_tray[item].length_width[item].width object |
| `keyboard_tray[item].length_width[item].width.value` | Required in keyboard_tray[item].length_width[item].width object |
| `knee_space_dimensions[item].depth` | Required in knee_space_dimensions[item] object |
| `knee_space_dimensions[item].depth.unit` | Required in knee_space_dimensions[item].depth object |
| `knee_space_dimensions[item].depth.unit` | Required in knee_space_dimensions[item].depth object |
| `knee_space_dimensions[item].depth.value` | Required in knee_space_dimensions[item].depth object |
| `knee_space_dimensions[item].depth.value` | Required in knee_space_dimensions[item].depth object |
| `knee_space_dimensions[item].height` | Required in knee_space_dimensions[item] object |
| `knee_space_dimensions[item].height.unit` | Required in knee_space_dimensions[item].height object |
| `knee_space_dimensions[item].height.unit` | Required in knee_space_dimensions[item].height object |
| `knee_space_dimensions[item].height.value` | Required in knee_space_dimensions[item].height object |
| `knee_space_dimensions[item].height.value` | Required in knee_space_dimensions[item].height object |
| `knee_space_dimensions[item].width` | Required in knee_space_dimensions[item] object |
| `knee_space_dimensions[item].width.unit` | Required in knee_space_dimensions[item].width object |
| `knee_space_dimensions[item].width.unit` | Required in knee_space_dimensions[item].width object |
| `knee_space_dimensions[item].width.value` | Required in knee_space_dimensions[item].width object |
| `knee_space_dimensions[item].width.value` | Required in knee_space_dimensions[item].width object |
| `language[item].type` | Required in language[item] object |
| `language[item].value` | Required in language[item] object |
| `length_range[item].language_tag` | Required in length_range[item] object |
| `length_range[item].value` | Required in length_range[item] object |
| `lifting_mechanism[item].language_tag` | Required in lifting_mechanism[item] object |
| `lifting_mechanism[item].value` | Required in lifting_mechanism[item] object |
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
| `lock_type[item].language_tag` | Required in lock_type[item] object |
| `lock_type[item].value` | Required in lock_type[item] object |
| `main_offer_image_locator[item].media_location` | Required in main_offer_image_locator[item] object |
| `main_product_image_locator[item].media_location` | Required in main_product_image_locator[item] object |
| `manufacturer[item].language_tag` | Required in manufacturer[item] object |
| `manufacturer[item].value` | Required in manufacturer[item] object |
| `map_policy[item].value` | Required in map_policy[item] object |
| `master_pack_layers_per_pallet_quantity[item].value` | Required in master_pack_layers_per_pallet_quantity[item] object |
| `master_packs_per_layer_quantity[item].value` | Required in master_packs_per_layer_quantity[item] object |
| `material[item].language_tag` | Required in material[item] object |
| `material[item].value` | Required in material[item] object |
| `max_order_quantity[item].value` | Required in max_order_quantity[item] object |
| `maximum_compatible_number_of_seats[item].value` | Required in maximum_compatible_number_of_seats[item] object |
| `maximum_height[item].unit` | Required in maximum_height[item] object |
| `maximum_height[item].value` | Required in maximum_height[item] object |
| `maximum_tilt_angle[item].unit` | Required in maximum_tilt_angle[item] object |
| `maximum_tilt_angle[item].value` | Required in maximum_tilt_angle[item] object |
| `maximum_weight_recommendation[item].unit` | Required in maximum_weight_recommendation[item] object |
| `maximum_weight_recommendation[item].value` | Required in maximum_weight_recommendation[item] object |
| `merchant_release_date[item].value` | Required in merchant_release_date[item] object |
| `merchant_shipping_group[item].value` | Required in merchant_shipping_group[item] object |
| `merchant_suggested_asin[item].value` | Required in merchant_suggested_asin[item] object |
| `mfg_warranty_description_type[item].language_tag` | Required in mfg_warranty_description_type[item] object |
| `mfg_warranty_description_type[item].value` | Required in mfg_warranty_description_type[item] object |
| `minimum_height[item].unit` | Required in minimum_height[item] object |
| `minimum_height[item].value` | Required in minimum_height[item] object |
| `model_name[item].language_tag` | Required in model_name[item] object |
| `model_name[item].value` | Required in model_name[item] object |
| `model_number[item].value` | Required in model_number[item] object |
| `mounting_type[item].language_tag` | Required in mounting_type[item] object |
| `mounting_type[item].value` | Required in mounting_type[item] object |
| `natural_variation_type[item].language_tag` | Required in natural_variation_type[item] object |
| `natural_variation_type[item].value` | Required in natural_variation_type[item] object |
| `num_batteries[item].quantity` | Required in num_batteries[item] object |
| `num_batteries[item].type` | Required in num_batteries[item] object |
| `number_of_boxes[item].value` | Required in number_of_boxes[item] object |
| `number_of_cabinets[item].value` | Required in number_of_cabinets[item] object |
| `number_of_drawers[item].value` | Required in number_of_drawers[item] object |
| `number_of_enclosed_shelves[item].value` | Required in number_of_enclosed_shelves[item] object |
| `number_of_height_positions[item].value` | Required in number_of_height_positions[item] object |
| `number_of_items[item].value` | Required in number_of_items[item] object |
| `number_of_leaves[item].value` | Required in number_of_leaves[item] object |
| `number_of_lithium_ion_cells[item].value` | Required in number_of_lithium_ion_cells[item] object |
| `number_of_lithium_metal_cells[item].value` | Required in number_of_lithium_metal_cells[item] object |
| `number_of_open_shelves[item].value` | Required in number_of_open_shelves[item] object |
| `number_of_shelves[item].language_tag` | Required in number_of_shelves[item] object |
| `number_of_shelves[item].value` | Required in number_of_shelves[item] object |
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
| `platform_for_display[item].language_tag` | Required in platform_for_display[item] object |
| `platform_for_display[item].value` | Required in platform_for_display[item] object |
| `product_description[item].language_tag` | Required in product_description[item] object |
| `product_description[item].value` | Required in product_description[item] object |
| `product_grade[item].language_tag` | Required in product_grade[item] object |
| `product_grade[item].value` | Required in product_grade[item] object |
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
| `shelf[item].height[item].unit` | Required in shelf[item].height[item] object |
| `shelf[item].height[item].unit` | Required in shelf[item].height[item] object |
| `shelf[item].height[item].value` | Required in shelf[item].height[item] object |
| `shelf[item].height[item].value` | Required in shelf[item].height[item] object |
| `shelf[item].length[item].unit` | Required in shelf[item].length[item] object |
| `shelf[item].length[item].unit` | Required in shelf[item].length[item] object |
| `shelf[item].width[item].unit` | Required in shelf[item].width[item] object |
| `shelf[item].width[item].unit` | Required in shelf[item].width[item] object |
| `ships_globally[item].value` | Required in ships_globally[item] object |
| `size[item].language_tag` | Required in size[item] object |
| `size[item].value` | Required in size[item] object |
| `skip_offer[item].value` | Required in skip_offer[item] object |
| `special_feature[item].language_tag` | Required in special_feature[item] object |
| `special_feature[item].value` | Required in special_feature[item] object |
| `storage_options[item].language_tag` | Required in storage_options[item] object |
| `storage_options[item].value` | Required in storage_options[item] object |
| `storage_volume[item].unit` | Required in storage_volume[item] object |
| `storage_volume[item].value` | Required in storage_volume[item] object |
| `style[item].language_tag` | Required in style[item] object |
| `style[item].value` | Required in style[item] object |
| `supplier_declared_dg_hz_regulation[item].value` | Required in supplier_declared_dg_hz_regulation[item] object |
| `supplier_declared_has_product_identifier_exemption[item].value` | Required in supplier_declared_has_product_identifier_exemption[item] object |
| `swatch_product_image_locator[item].media_location` | Required in swatch_product_image_locator[item] object |
| `tabletop_thickness[item].unit` | Required in tabletop_thickness[item] object |
| `tabletop_thickness[item].value` | Required in tabletop_thickness[item] object |
| `target_gender[item].value` | Required in target_gender[item] object |
| `theme[item].language_tag` | Required in theme[item] object |
| `theme[item].value` | Required in theme[item] object |
| `tools_recommended_for_assembly[item].value` | Required in tools_recommended_for_assembly[item] object |
| `top[item].color[item].language_tag` | Required in top[item].color[item] object |
| `top[item].color[item].language_tag` | Required in top[item].color[item] object |
| `top[item].color[item].value` | Required in top[item].color[item] object |
| `top[item].color[item].value` | Required in top[item].color[item] object |
| `top[item].material[item].language_tag` | Required in top[item].material[item] object |
| `top[item].material[item].language_tag` | Required in top[item].material[item] object |
| `top[item].material[item].value` | Required in top[item].material[item] object |
| `top[item].material[item].value` | Required in top[item].material[item] object |
| `unit_count[item].type.language_tag` | Required in unit_count[item].type object |
| `unit_count[item].type.language_tag` | Required in unit_count[item].type object |
| `unit_count[item].type.value` | Required in unit_count[item].type object |
| `unit_count[item].type.value` | Required in unit_count[item].type object |
| `unit_count[item].value` | Required in unit_count[item] object |
| `variation_theme[item].name` | Required in variation_theme[item] object |
| `warranty_type[item].language_tag` | Required in warranty_type[item] object |
| `warranty_type[item].value` | Required in warranty_type[item] object |
| `width_range[item].language_tag` | Required in width_range[item] object |
| `width_range[item].value` | Required in width_range[item] object |
| `working_surface_diagonal_length[item].unit` | Required in working_surface_diagonal_length[item] object |
| `working_surface_diagonal_length[item].value` | Required in working_surface_diagonal_length[item] object |
| `working_surface_length_width[item].length` | Required in working_surface_length_width[item] object |
| `working_surface_length_width[item].length.unit` | Required in working_surface_length_width[item].length object |
| `working_surface_length_width[item].length.unit` | Required in working_surface_length_width[item].length object |
| `working_surface_length_width[item].length.value` | Required in working_surface_length_width[item].length object |
| `working_surface_length_width[item].length.value` | Required in working_surface_length_width[item].length object |
| `working_surface_length_width[item].width` | Required in working_surface_length_width[item] object |
| `working_surface_length_width[item].width.unit` | Required in working_surface_length_width[item].width object |
| `working_surface_length_width[item].width.unit` | Required in working_surface_length_width[item].width object |
| `working_surface_length_width[item].width.value` | Required in working_surface_length_width[item].width object |
| `working_surface_length_width[item].width.value` | Required in working_surface_length_width[item].width object |

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

**Title:** Title

**Required:** Yes

**Examples:**

- `Adidas Blue Sneakers`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a title for the item that may be customer facing |
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

Provide the specific type of desk, indicating its primary purpose or design features that distinguish it from other desk varieties.

**Type:** array

**Title:** Item Type Keyword

**Required:** Yes

**Examples:**

- `Home office desks`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the specific type of desk, indicating its primary purpose or design features that distinguish it from other desk varieties. |
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

### target_gender

Provide the intended gender for whom the item is designed, indicating its style, size, or other gender-specific features.

**Type:** array

**Title:** Target Gender

**Required:** No

**Examples:**

- `Female`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the target gender for the product |
| `marketplace_id` | object | No |  |

### age_range_description

Provide the age group the item is suitable for, describing who can comfortably use it based on size and design.

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
| `value` | string | Yes | Provide the suitable age range for the desk, indicating the intended user group based on developmental stages or physical characteristics. |
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
| `joint_type` | array | No | Provide the joint type used to attach different pieces of a frame. Joint type refers to the technique to attach pieces of a frame. |
| `marketplace_id` | object | No |  |
| `material` | array | No | Materal Frame is made of |

### edition

Provide the version or edition of the item

**Type:** array

**Title:** Edition

**Required:** No

**Examples:**

- `Teacher's Edition, Unabridged Version`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the version or edition of the item |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### platform_for_display

Provide the platform associated with the product.

**Type:** array

**Title:** Platform for Display

**Required:** No

**Examples:**

- `Android, Mac, PC`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the platform associated with the product. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### language

Select the appropriate language from the list of valid values

**Type:** array

**Title:** Language

**Required:** Conditionally

**Examples:**

- `English`

**Selectors:** `marketplace_id`, `type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `type` | string | Yes | Select the language type |
| `value` | string | Yes | Select the appropriate language from the list of valid values |
| `marketplace_id` | object | No |  |

### lock_type

Lock

**Type:** array

**Title:** Lock Type

**Required:** No

**Examples:**

- `No`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the lock type |
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

### storage_volume

Provide the volume capacity the item has available to store contents.

**Type:** array

**Title:** Storage Volume

**Required:** No

**Examples:**

- `20.0 Liters, 5.3 Gallons`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the volume capacity the item has available to store contents. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the storage volume capacity of the desk. |
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

### number_of_shelves

Number of Shelves

**Type:** array

**Title:** Number Of Shelves

**Required:** No

**Examples:**

- `One Full`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the total number of shelves the item has, including both open and enclosed shelves. |
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
| `depth` | object | No | Provide the depth of the item without packaging |
| `diameter` | object | No | Provide the diameter of the product without packaging and fully assembled |
| `height` | object | No | Provide the height of the product without packaging and fully assembled |
| `length` | object | No | Provide the length of the product without packaging and fully assembled |
| `marketplace_id` | object | No |  |
| `width` | object | No | Provide the width of the product without packaging and fully assembled |

#### item_display_dimensions[].depth

Provide the depth of the item without packaging

**Type:** object

**Title:** Item Display Depth

**Required:** No

**Examples:**

- `2.75, 3.00`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the numeric component of the physical depth of the product without packaging and fully assembled |
| `unit` | string | Yes | Select the corresponding unit |

#### item_display_dimensions[].diameter

Provide the diameter of the product without packaging and fully assembled

**Type:** object

**Title:** Item Display Diameter

**Required:** No

**Examples:**

- `2.75, 3.00`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the numeric component of the diameter of the product without packaging and fully assembled |
| `unit` | string | Yes | Select the corresponding unit |

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

#### item_display_dimensions[].length

Provide the length of the product without packaging and fully assembled

**Type:** object

**Title:** Item Display Length

**Required:** No

**Examples:**

- `5.7`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the numeric component of the length of the product without packaging and fully assembled |
| `unit` | string | Yes | Select the corresponding unit |

#### item_display_dimensions[].width

Provide the width of the product without packaging and fully assembled

**Type:** object

**Title:** Item Display Width

**Required:** No

**Examples:**

- `3.5`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the numeric component of the width of the product without packaging and fully assembled |
| `unit` | string | Yes | Select the corresponding unit |

### drawer_type

Describes the drawer(s) on the product.

**Type:** array

**Title:** Drawer Type

**Required:** No

**Examples:**

- `Storage, Warming`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Describes the drawer(s) on the product. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### number_of_drawers

Provide the number of drawers that the item has

**Type:** array

**Title:** Number of Drawers

**Required:** No

**Examples:**

- `7`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of drawers that the item has |
| `marketplace_id` | object | No |  |

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

### lifting_mechanism

Provide the method used to raise or lower the desk, indicating how the height can be adjusted for user comfort and ergonomics.

**Type:** array

**Title:** Lifting Mechanism

**Required:** No

**Examples:**

- `Manual, Pneumatic, Electrical`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the method used to raise or lower the desk, indicating how the height can be adjusted for user comfort and ergonomics. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### furniture_finish

the finish of furniture

**Type:** array

**Title:** Furniture Finish

**Required:** No

**Examples:**

- `Oak`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide a description of the furniture's finish |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### product_grade

Provide the intended use or quality level of the item, indicating its durability and purpose, like for heavy-duty or casual use.

**Type:** array

**Title:** Product Grade

**Required:** No

**Examples:**

- `Replacement Parts`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the product's grade of use |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### customer_package_type

Provide the products package type

**Type:** array

**Title:** Customer Package Type

**Required:** No

**Examples:**

- `Standard Packaging`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the products package type |
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

### mounting_type

Provide the type of mount the desk has or is intended for, indicating how it can be attached or secured in place.

**Type:** array

**Title:** Mounting Type

**Required:** No

**Examples:**

- `Clevis`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the type of mount the desk has or is intended for, indicating how it can be attached or secured in place. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### maximum_tilt_angle

Indicates maximum tilt angle.

**Type:** array

**Title:** Maximum Tilt Angle

**Required:** No

**Examples:**

- `60.0 °`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Indicates maximum tilt angle. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the desk's maximum angle of tilt from its default position. |
| `marketplace_id` | object | No |  |

### finish_type

Indicate the external appearance of the product once applied

**Type:** array

**Title:** Finish Types

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the finish of the product's exterior surface |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### base_type

Provide the style or structure of the desk's supporting foundation, which affects its stability, appearance, and functionality.

**Type:** array

**Title:** Base Type

**Required:** No

**Examples:**

- `Pedestal`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the style or structure of the desk's supporting foundation, which affects its stability, appearance, and functionality. |
| `language_tag` | object | Yes |  |
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

### base

Enter the specifications for the base

**Type:** array

**Title:** Base

**Required:** No

**Examples:**

- `Stainless Steel`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `color` | array | No | Provide the dominant color of the item's base. Base refers to the bottom of an item that provides support and stability. |
| `marketplace_id` | object | No |  |
| `material` | array | No | An alphanumeric string; 50 characters maximum. |

### is_electric

Item is powered by electricity

**Type:** array

**Title:** Is Electric

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Item is powered by electricity |
| `marketplace_id` | object | No |  |

### is_ul_listed

Provide whether the item meets safety standards set by Underwriters Laboratories, ensuring safe usage.

**Type:** array

**Title:** UL Listed

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Item is UL listed |
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

Provide the type of room the item is intended for, such as a study, office, or bedroom.

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
| `value` | string | Yes | Provide the type of room the desk is designed for, influencing its size, features, and aesthetics to suit specific living or working spaces. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### shelf

The attribute indicates Shelf of the product

**Type:** array

**Title:** Shelf

**Required:** No

**Examples:**

- `Meters`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `height` | array | No | Provide the vertical distance between the bottom surface and the top surface of the item's shelf. |
| `length` | array | No | Provide the length of the item's shelf in its horizontal plane, from one side to the other side when looking at it from the front. |
| `marketplace_id` | object | No |  |
| `width` | array | No | Provide the width of the item's shelf in its horizontal plane, from the front to the back when looking at it from the front. |

### top

The attribute indicates Top of the product

**Type:** array

**Title:** Top

**Required:** No

**Examples:**

- `Ash Wood`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `color` | array | No | Provide the dominant color of the item's top. Top refers to the visual flat surface of the item and it is usually its highest point. |
| `marketplace_id` | object | No |  |
| `material` | array | No | Top Material |

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

### maximum_compatible_number_of_seats

Specify the maximum compatible number of seats

**Type:** array

**Title:** Maximum Compatible Number of Seats

**Required:** No

**Examples:**

- `10`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Specify the maximum compatible number of seats |
| `marketplace_id` | object | No |  |

### maximum_weight_recommendation

Provide the highest weight the item can safely hold, the maximum load it can support without issues.

**Type:** array

**Title:** Maximum Weight Recommendation

**Required:** No

**Examples:**

- `20.0 Pounds, 350.0 Kilograms`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the maximum weight recommendation as a numeric value |
| `unit` | string | Yes | Select the corresponding unit |
| `marketplace_id` | object | No |  |

### number_of_height_positions

Provide the quantity of available height settings for the desk, indicating the adjustability of the work surface.

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
| `value` | integer | Yes | Provide the quantity of available height settings for the desk, indicating the adjustability of the work surface. |
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
| `marketplace_id` | object | No |  |
| `material` | array | No | Provide the material of the furniture item's legs. The leg material refers to the primary visible material of the legs and does not include the materials of leg parts such as tips. |
| `style` | array | No | Provide the style of the furniture item's legs. |

### desk_design

Provide the design of the desk. The desk design represents the standard form and function of the desk to create work and storage space to meet the user's needs.

**Type:** array

**Title:** Desk Design

**Required:** No

**Examples:**

- `Executive Desk, Armoire Desk, Computer Desk`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the design of the desk. The desk design represents the standard form and function of the desk to create work and storage space to meet the user's needs. |
| `marketplace_id` | object | No |  |

### item_depth_width_height

Provide the dimensions of the item when fully set up and ready to use, including depth, width, and height.

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
| `depth` | object | Yes | Provide the measurement of the item from front to back in an assembled state. |
| `height` | object | Yes | Provide the measurement of the item from the floor to the top in an assembled state. If the item is expandable, the height is measured in an unexpanded position. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the measurement from side to side of the front of the item in an assembled state. |

#### item_depth_width_height[].depth

Provide the measurement of the item from front to back in an assembled state.

**Type:** object

**Title:** Item Depth Front To Back

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of the item from front to back in an assembled state. |
| `unit` | string | Yes | Select the unit of measure for Item depth. |

#### item_depth_width_height[].height

Provide the measurement of the item from the floor to the top in an assembled state. If the item is expandable, the height is measured in an unexpanded position.

**Type:** object

**Title:** Item Height Floor To Top

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of the item from the floor to the top in an assembled state. If the item is expandable, the height is measured in an unexpanded position. |
| `unit` | string | Yes | Select the unit of measure for item Height |

#### item_depth_width_height[].width

Provide the measurement from side to side of the front of the item in an assembled state.

**Type:** object

**Title:** Item Width Side To Side

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement from side to side of the front of the item in an assembled state. |
| `unit` | string | Yes | Select the unit of measure for item width. |

### tabletop_thickness

Provide the dimensional thickness of the product's tabletop. A tabletop is the raised flat surface on top of a furniture table.

**Type:** array

**Title:** Tabletop Thickness

**Required:** No

**Examples:**

- `1.5 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the dimensional thickness of the product's tabletop. A tabletop is the raised flat surface on top of a furniture table. |
| `unit` | string | Yes | Provide the unit of measure of the item's tabletop thickness. |
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

### number_of_leaves

Provide the number of leaves included with this item. Leaves are additional tabletop pieces used to expand the size of the table.

**Type:** array

**Title:** Number of Leaves

**Required:** No

**Examples:**

- `2`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of leaves included with this item. Leaves are additional tabletop pieces used to expand the size of the table. |
| `marketplace_id` | object | No |  |

### drawer

Provide the specifications of an item's drawer, a varying-sized compartment that opens to reveal contents and closes when not in use.

**Type:** array

**Title:** Drawer

**Required:** No

**Examples:**

- `Ball Bearing Glide, Metal`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `glide_material` | array | No | Provide the material used for the sliding mechanism in the item's drawers, allowing smooth opening and closing. |
| `glide_mechanism` | array | No | Provide the glide mechanism of the drawer. The glide mechanism is a system that allows the drawers to open and close smoothly and easily. |
| `marketplace_id` | object | No |  |

### drawer_weight_capacity

Provide the maximum weight capacity that a single drawer within a dresser, a desk, or a storage drawer unit can support without being damaged.

**Type:** array

**Title:** Drawer Weight Capacity

**Required:** Conditionally

**Examples:**

- `Large, 4 Kilograms`

**Selectors:** `marketplace_id`, `type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `type` | string | Yes | Provide the drawer size of the single drawer within a dresser, a desk, or a storage drawer unit. |
| `unit_decimal` | object | Yes | Provide the maximum weight capacity that a single drawer within a dresser, a desk, or a storage drawer unit can support without being damaged. |

#### drawer_weight_capacity[].unit_decimal

Provide the maximum weight capacity that a single drawer within a dresser, a desk, or a storage drawer unit can support without being damaged.

**Type:** object

**Title:** Drawer Weight Capacity

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the maximum weight capacity that a single drawer within a dresser, a desk, or a storage drawer unit can support without being damaged. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the single drawer weight capacity within a dresser, a desk, or a storage unit. |

### has_finished_back

Provide whether the back of the item is polished and finished like the front, for a consistent look from all sides.

**Type:** array

**Title:** Has Finished Back

**Required:** No

**Examples:**

- `TRUE`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether or not the item has a finished back. |
| `marketplace_id` | object | No |  |

### number_of_cabinets

Provide the number of cabinets that are included with the product.

**Type:** array

**Title:** Number Of Cabinets

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of cabinets that are included with the product. |
| `marketplace_id` | object | No |  |

### distressed_finish_type

Provide the surface treatment that gives the desk a worn or aged appearance, such as intentional weathering or natural wear.

**Type:** array

**Title:** Distressed Finish Type

**Required:** No

**Examples:**

- `Chipped`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the surface treatment that gives the desk a worn or aged appearance, such as intentional weathering or natural wear. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### natural_variation_type

Provide the types of natural imperfections and unique characteristics in the desk's material, such as wood grains or color variations.

**Type:** array

**Title:** Natural Variation Type

**Required:** No

**Examples:**

- `Burl Patterns`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the types of natural imperfections and unique characteristics in the desk's material, such as wood grains or color variations. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### number_of_enclosed_shelves

Provide the number of enclosed shelves the item has. The number of enclosed shelves is the quantity of shelves behind doors or panels.

**Type:** array

**Title:** Number Of Enclosed Shelves

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of enclosed shelves the item has. The number of enclosed shelves is the quantity of shelves behind doors or panels. |
| `marketplace_id` | object | No |  |

### number_of_open_shelves

Provide the number of open shelves the item has. The number of open shelves is the quantity of shelves not enclosed behind doors.

**Type:** array

**Title:** Number Of Open Shelves

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of open shelves the item has. The number of open shelves is the quantity of shelves not enclosed behind doors. |
| `marketplace_id` | object | No |  |

### working_surface_length_width

Provide the measurement of the length and width of the working surface of the item in assembled, unextended condition.

**Type:** array

**Title:** Working Surface Length Width

**Required:** No

**Examples:**

- `Length: 42 Inches, Width:36 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `length` | object | Yes | Provide the length of the item's working surface measured at the longer edge in assembled, unextended condition. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the width of the item's working surface measured at the shorter edge in assembled, unextended condition. |

#### working_surface_length_width[].length

Provide the length of the item's working surface measured at the longer edge in assembled, unextended condition.

**Type:** object

**Title:** Working Surface Length

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the length of the item's working surface measured at the longer edge in assembled, unextended condition. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the item’s working surface  length. |

#### working_surface_length_width[].width

Provide the width of the item's working surface measured at the shorter edge in assembled, unextended condition.

**Type:** object

**Title:** Working Surface Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the width of the item's working surface measured at the shorter edge in assembled, unextended condition. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the item’s working surface width. |

### drawer_pedestal_count

Provide the number of small cabinets with stacked drawers that support the desk's work surface.

**Type:** array

**Title:** Drawer Pedestal Count

**Required:** No

**Examples:**

- `4`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of attached and detached drawer pedestals of the item, which are stacked drawers that support the working surface. |
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

### hutch

Provide details on the hutch included with the item. A hutch is a set of shelves or cabinets placed on top of a lower unit.

**Type:** array

**Title:** Hutch

**Required:** No

**Examples:**

- `Wood, Depth: 6.375 Inches, Width: 45 Inches, Height: 5.75 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `depth_width_height` | array | No | Provide the measurement of the depth, width and height of the hutch in an assembled state. |
| `marketplace_id` | object | No |  |
| `material` | array | No | Provide the dominant material from which the hutch is constructed. |

### keyboard_tray

The attribute indicates the Keyboard Tray of the item.

**Type:** array

**Title:** Keyboard Tray

**Required:** No

**Examples:**

- `Length: 17.9 Inches
Width: 7.7 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `length_width` | array | No | Provide the length and width of the keyboard tray area on the item, the space designed to hold a keyboard. |
| `marketplace_id` | object | No |  |

### cabinet

Cabinet describes the specifications of the cabinet included with the item.

**Type:** array

**Title:** Cabinet

**Required:** No

**Examples:**

- `Cabinet Configuration: Built-In`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `configuration` | array | No | Provide the cabinet setup for the item, how the storage space is arranged, with doors, shelves, etc. |
| `marketplace_id` | object | No |  |

### drawer_interior_dimensions

Provide the measurement of the product's single drawer interior dimensions in depth, width and height in an assembled state.

**Type:** array

**Title:** Drawer Interior Dimensions

**Required:** Conditionally

**Examples:**

- `Large, Depth: 5.75 Inches, Width: 38.625 Inches, Height: 6.375 Inches`

**Selectors:** `marketplace_id`, `type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `depth` | object | Yes | Provide the interior depth measurement from front to back of the drawer in an assembled state. |
| `height` | object | Yes | Provide the interior height measurement from top to bottom of the drawer in an assembled state. |
| `marketplace_id` | object | No |  |
| `type` | string | Yes | Provide the drawer size of the single drawer within a dresser, a desk, or a storage drawer unit you want to provide dimensions for. |
| `width` | object | Yes | Provide the interior width measurement from side to side of the front of the drawer in an assembled state. |

#### drawer_interior_dimensions[].depth

Provide the interior depth measurement from front to back of the drawer in an assembled state.

**Type:** object

**Title:** Drawer Interior Depth

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the interior depth measurement from front to back of the drawer in an assembled state. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the interior depth measurement. |

#### drawer_interior_dimensions[].height

Provide the interior height measurement from top to bottom of the drawer in an assembled state.

**Type:** object

**Title:** Drawer Interior Height

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the interior height measurement from top to bottom of the drawer in an assembled state. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the interior height measurement. |

#### drawer_interior_dimensions[].width

Provide the interior width measurement from side to side of the front of the drawer in an assembled state.

**Type:** object

**Title:** Drawer Interior Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the interior width measurement from side to side of the front of the drawer in an assembled state. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the interior width measurement. |

### cabinet_interior_dimensions

Provide the interior dimensions of each cabinet included with the item in depth, width, and height in an assembled state.

**Type:** array

**Title:** Cabinet Interior Dimensions

**Required:** Conditionally

**Examples:**

- `Cabinet 1, Depth: 16.1 Inches, Width: 12.4, Height: 12 Inches`

**Selectors:** `marketplace_id`, `type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `depth` | object | Yes | Provide the interior depth measurement from front to back of the cabinet in an assembled state. |
| `height` | object | Yes | Provide the interior height measurement of the cabinet from top to bottom in an assembled state. |
| `marketplace_id` | object | No |  |
| `type` | string | Yes | Provide a number for the cabinet included with the item you want to provide dimensions for. |
| `width` | object | Yes | Provide the interior width measurement from side to side of the front of the cabinet in an assembled state. |

#### cabinet_interior_dimensions[].depth

Provide the interior depth measurement from front to back of the cabinet in an assembled state.

**Type:** object

**Title:** Cabinet Interior Depth

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the interior depth measurement from front to back of the cabinet in an assembled state. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the interior depth measurement of the cabinet. |

#### cabinet_interior_dimensions[].height

Provide the interior height measurement of the cabinet from top to bottom in an assembled state.

**Type:** object

**Title:** Cabinet Interior Height

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the interior height measurement of the cabinet from top to bottom in an assembled state. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the interior height measurement of the cabinet. |

#### cabinet_interior_dimensions[].width

Provide the interior width measurement from side to side of the front of the cabinet in an assembled state.

**Type:** object

**Title:** Cabinet Interior Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the interior width measurement from side to side of the front of the cabinet in an assembled state. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the interior width measurement of the cabinet. |

### desk_return_dimensions

Provide the measurement of depth, width and height of the item's desk return in ready to use condition.

**Type:** array

**Title:** Desk Return Dimensions

**Required:** No

**Examples:**

- `Depth: 15.5 Inches, Width: 47.25 Inches, Height: 27.5 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `depth` | object | No | Provide the measurement of depth of the item's desk return, measured from inside to back in ready to use condition. |
| `height` | object | No | Provide the measurement of height of the item's desk return, measured from top to bottom in ready to use condition. |
| `marketplace_id` | object | No |  |
| `width` | object | No | Provide the measurement of width of the item's desk return, measured from the inside corner to the inside edge in ready to use condition. |

#### desk_return_dimensions[].depth

Provide the measurement of depth of the item's desk return, measured from inside to back in ready to use condition.

**Type:** object

**Title:** Desk Return Depth

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of depth of the item's desk return, measured from inside to back in ready to use condition. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the depth of the item's desk return. |

#### desk_return_dimensions[].height

Provide the measurement of height of the item's desk return, measured from top to bottom in ready to use condition.

**Type:** object

**Title:** Desk Return Height

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of height of the item's desk return, measured from top to bottom in ready to use condition. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the height of the item's desk return. |

#### desk_return_dimensions[].width

Provide the measurement of width of the item's desk return, measured from the inside corner to the inside edge in ready to use condition.

**Type:** object

**Title:** Desk Return Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of width of the item's desk return, measured from the inside corner to the inside edge in ready to use condition. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the width of the item's desk return. |

### working_surface_diagonal_length

Provide the working surface diagonal length, which refers to the distance from one corner of a working surface to the opposite corner.

**Type:** array

**Title:** Working Surface Diagonal Length

**Required:** No

**Examples:**

- `30 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the working surface diagonal length, which refers to the distance from one corner of a working surface to the opposite corner. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the desk's working surface diagonal measurement. |
| `marketplace_id` | object | No |  |

### storage_options

Provide the different ways the item can store goods, like drawers or shelves, for keeping things organized and accessible.

**Type:** array

**Title:** Storage Options

**Required:** No

**Examples:**

- `Drawer`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the storage options of the item. Storage options represents the different types of storage available in the item to store goods. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### knee_space_dimensions

Provide the knee space dimensions of the item which defines leg clearance and comfortable leg movement when seated.

**Type:** array

**Title:** Knee Space Dimensions

**Required:** No

**Examples:**

- `18 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `depth` | object | Yes | Provide the available knee space depth from front to back when placed in the manner it is expected to be used. |
| `height` | object | Yes | Provide the height of the item's available knee space from top to bottom when placed in the manner in which it is expected to be used. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the available knee space width from side to side of the item when placed in the manner it is expected to be used. |

#### knee_space_dimensions[].depth

Provide the available knee space depth from front to back when placed in the manner it is expected to be used.

**Type:** object

**Title:** Knee Space Depth

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the available knee space depth from front to back when placed in the manner it is expected to be used. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the depth of the knee space of the item. |

#### knee_space_dimensions[].height

Provide the height of the item's available knee space from top to bottom when placed in the manner in which it is expected to be used.

**Type:** object

**Title:** Knee Space Height

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the height of the item's available knee space from top to bottom when placed in the manner in which it is expected to be used. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the knee space height of the item. |

#### knee_space_dimensions[].width

Provide the available knee space width from side to side of the item when placed in the manner it is expected to be used.

**Type:** object

**Title:** Knee Space Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the available knee space width from side to side of the item when placed in the manner it is expected to be used. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the width of the knee space of the item. |

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

Provide the details on the warranty coverage provided by the manufacturer for the item, explaining what is covered and for how long.

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

### maximum_height

Provide the maximum height of the product

**Type:** array

**Title:** Maximum Height

**Required:** No

**Examples:**

- `8.0 Feet`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Enter the maximum height if the item is adjustable |
| `unit` | string | Yes | Provide the corresponding unit used to designate the desk's maximum vertical dimension. |
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

### minimum_height

Enter the minimum height.

**Type:** array

**Title:** Minimum Height

**Required:** No

**Examples:**

- `3.1 Inches, 91.0 Centimeters`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the minimum height of the product |
| `unit` | string | Yes | Provide the corresponding unit used to designate the desk's lowest supported or actual height. |
| `marketplace_id` | object | No |  |

### number_of_boxes

Provide the number of boxes that the product comes in

**Type:** array

**Title:** Number of Boxes

**Required:** No

**Examples:**

- `5`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | integer | Yes | Provide the number of boxes that the product will be shipped in |
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

