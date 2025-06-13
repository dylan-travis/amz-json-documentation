# FIGURINE Schema Documentation

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
| `access_method[item].language_tag` | Required in access_method[item] object |
| `access_method[item].value` | Required in access_method[item] object |
| `age_range_description[item].language_tag` | Required in age_range_description[item] object |
| `age_range_description[item].value` | Required in age_range_description[item] object |
| `athlete[item].language_tag` | Required in athlete[item] object |
| `athlete[item].value` | Required in athlete[item] object |
| `batteries_included[item].value` | Required in batteries_included[item] object |
| `batteries_required[item].value` | Required in batteries_required[item] object |
| `battery[item].cell_composition[item].value` | Required in battery[item].cell_composition[item] object |
| `battery[item].cell_composition[item].value` | Required in battery[item].cell_composition[item] object |
| `battery[item].cell_composition_other_than_listed[item].language_tag` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].cell_composition_other_than_listed[item].language_tag` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].cell_composition_other_than_listed[item].value` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].cell_composition_other_than_listed[item].value` | Required in battery[item].cell_composition_other_than_listed[item] object |
| `battery[item].iec_code[item].value` | Required in battery[item].iec_code[item] object |
| `battery[item].iec_code[item].value` | Required in battery[item].iec_code[item] object |
| `battery[item].weight[item].unit` | Required in battery[item].weight[item] object |
| `battery[item].weight[item].unit` | Required in battery[item].weight[item] object |
| `battery[item].weight[item].value` | Required in battery[item].weight[item] object |
| `battery[item].weight[item].value` | Required in battery[item].weight[item] object |
| `battery_contains_free_unabsorbed_liquid[item].value` | Required in battery_contains_free_unabsorbed_liquid[item] object |
| `battery_installation_device_type[item].value` | Required in battery_installation_device_type[item] object |
| `brand[item].language_tag` | Required in brand[item] object |
| `brand[item].value` | Required in brand[item] object |
| `bullet_point[item].language_tag` | Required in bullet_point[item] object |
| `bullet_point[item].value` | Required in bullet_point[item] object |
| `california_proposition_65[item].compliance_type` | Required in california_proposition_65[item] object |
| `child_parent_sku_relationship[item].child_relationship_type` | Required in child_parent_sku_relationship[item] object |
| `collection[item].language_tag` | Required in collection[item] object |
| `collection[item].value` | Required in collection[item] object |
| `color[item].language_tag` | Required in color[item] object |
| `compliance_media[item].content_language` | Required in compliance_media[item] object |
| `compliance_media[item].content_type` | Required in compliance_media[item] object |
| `compliance_media[item].source_location` | Required in compliance_media[item] object |
| `condition_note[item].language_tag` | Required in condition_note[item] object |
| `condition_note[item].value` | Required in condition_note[item] object |
| `condition_type[item].value` | Required in condition_type[item] object |
| `configuration[item].language_tag` | Required in configuration[item] object |
| `configuration[item].value` | Required in configuration[item] object |
| `contains_battery_or_cell[item].value` | Required in contains_battery_or_cell[item] object |
| `country_of_origin[item].value` | Required in country_of_origin[item] object |
| `cup[item].size[item].language_tag` | Required in cup[item].size[item] object |
| `cup[item].size[item].language_tag` | Required in cup[item].size[item] object |
| `cup[item].size[item].value` | Required in cup[item].size[item] object |
| `cup[item].size[item].value` | Required in cup[item].size[item] object |
| `customer_package_type[item].language_tag` | Required in customer_package_type[item] object |
| `customer_package_type[item].value` | Required in customer_package_type[item] object |
| `dsa_responsible_party_address[item].value` | Required in dsa_responsible_party_address[item] object |
| `edition[item].language_tag` | Required in edition[item] object |
| `edition[item].value` | Required in edition[item] object |
| `externally_assigned_product_identifier[item].type` | Required in externally_assigned_product_identifier[item] object |
| `externally_assigned_product_identifier[item].value` | Required in externally_assigned_product_identifier[item] object |
| `fcc_radio_frequency_emission_compliance[item].registration_status` | Required in fcc_radio_frequency_emission_compliance[item] object |
| `finish_type[item].language_tag` | Required in finish_type[item] object |
| `finish_type[item].value` | Required in finish_type[item] object |
| `flavor[item].language_tag` | Required in flavor[item] object |
| `flavor[item].value` | Required in flavor[item] object |
| `fulfillment_availability[item].fulfillment_channel_code` | Required in fulfillment_availability[item] object |
| `generic_keyword[item].language_tag` | Required in generic_keyword[item] object |
| `generic_keyword[item].value` | Required in generic_keyword[item] object |
| `ghs[item].classification[item].class` | Required in ghs[item].classification[item] object |
| `ghs[item].classification[item].class` | Required in ghs[item].classification[item] object |
| `ghs_chemical_h_code[item].value` | Required in ghs_chemical_h_code[item] object |
| `gpsr_safety_attestation[item].value` | Required in gpsr_safety_attestation[item] object |
| `handmade_classification[item].value` | Required in handmade_classification[item] object |
| `has_less_than_30_percent_state_of_charge[item].value` | Required in has_less_than_30_percent_state_of_charge[item] object |
| `has_multiple_battery_powered_components[item].value` | Required in has_multiple_battery_powered_components[item] object |
| `has_replaceable_battery[item].value` | Required in has_replaceable_battery[item] object |
| `hazmat[item].aspect` | Required in hazmat[item] object |
| `hazmat[item].value` | Required in hazmat[item] object |
| `is_adult_product[item].value` | Required in is_adult_product[item] object |
| `is_battery_non_spillable[item].value` | Required in is_battery_non_spillable[item] object |
| `is_oem_sourced_product[item].value` | Required in is_oem_sourced_product[item] object |
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
| `item_dimensions[item].height` | Required in item_dimensions[item] object |
| `item_dimensions[item].height.unit` | Required in item_dimensions[item].height object |
| `item_dimensions[item].height.unit` | Required in item_dimensions[item].height object |
| `item_dimensions[item].height.value` | Required in item_dimensions[item].height object |
| `item_dimensions[item].height.value` | Required in item_dimensions[item].height object |
| `item_dimensions[item].length` | Required in item_dimensions[item] object |
| `item_dimensions[item].length.unit` | Required in item_dimensions[item].length object |
| `item_dimensions[item].length.unit` | Required in item_dimensions[item].length object |
| `item_dimensions[item].length.value` | Required in item_dimensions[item].length object |
| `item_dimensions[item].length.value` | Required in item_dimensions[item].length object |
| `item_dimensions[item].width` | Required in item_dimensions[item] object |
| `item_dimensions[item].width.unit` | Required in item_dimensions[item].width object |
| `item_dimensions[item].width.unit` | Required in item_dimensions[item].width object |
| `item_dimensions[item].width.value` | Required in item_dimensions[item].width object |
| `item_dimensions[item].width.value` | Required in item_dimensions[item].width object |
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
| `item_length_width_height[item].height` | Required in item_length_width_height[item] object |
| `item_length_width_height[item].height.unit` | Required in item_length_width_height[item].height object |
| `item_length_width_height[item].height.unit` | Required in item_length_width_height[item].height object |
| `item_length_width_height[item].height.value` | Required in item_length_width_height[item].height object |
| `item_length_width_height[item].height.value` | Required in item_length_width_height[item].height object |
| `item_length_width_height[item].length` | Required in item_length_width_height[item] object |
| `item_length_width_height[item].length.unit` | Required in item_length_width_height[item].length object |
| `item_length_width_height[item].length.unit` | Required in item_length_width_height[item].length object |
| `item_length_width_height[item].length.value` | Required in item_length_width_height[item].length object |
| `item_length_width_height[item].length.value` | Required in item_length_width_height[item].length object |
| `item_length_width_height[item].width` | Required in item_length_width_height[item] object |
| `item_length_width_height[item].width.unit` | Required in item_length_width_height[item].width object |
| `item_length_width_height[item].width.unit` | Required in item_length_width_height[item].width object |
| `item_length_width_height[item].width.value` | Required in item_length_width_height[item].width object |
| `item_length_width_height[item].width.value` | Required in item_length_width_height[item].width object |
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
| `legal_compliance_certifications[item].certification_status` | Required in legal_compliance_certifications[item] object |
| `legal_compliance_certifications[item].language_tag` | Required in legal_compliance_certifications[item] object |
| `legal_compliance_certifications[item].regulatory_organization_name` | Required in legal_compliance_certifications[item] object |
| `legal_compliance_certifications[item].value` | Required in legal_compliance_certifications[item] object |
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
| `manufacturer_minimum_age[item].value` | Required in manufacturer_minimum_age[item] object |
| `map_policy[item].value` | Required in map_policy[item] object |
| `master_pack_dimensions[item].height` | Required in master_pack_dimensions[item] object |
| `master_pack_dimensions[item].height.unit` | Required in master_pack_dimensions[item].height object |
| `master_pack_dimensions[item].height.unit` | Required in master_pack_dimensions[item].height object |
| `master_pack_dimensions[item].height.value` | Required in master_pack_dimensions[item].height object |
| `master_pack_dimensions[item].height.value` | Required in master_pack_dimensions[item].height object |
| `master_pack_dimensions[item].length` | Required in master_pack_dimensions[item] object |
| `master_pack_dimensions[item].length.unit` | Required in master_pack_dimensions[item].length object |
| `master_pack_dimensions[item].length.unit` | Required in master_pack_dimensions[item].length object |
| `master_pack_dimensions[item].length.value` | Required in master_pack_dimensions[item].length object |
| `master_pack_dimensions[item].length.value` | Required in master_pack_dimensions[item].length object |
| `master_pack_dimensions[item].width` | Required in master_pack_dimensions[item] object |
| `master_pack_dimensions[item].width.unit` | Required in master_pack_dimensions[item].width object |
| `master_pack_dimensions[item].width.unit` | Required in master_pack_dimensions[item].width object |
| `master_pack_dimensions[item].width.value` | Required in master_pack_dimensions[item].width object |
| `master_pack_dimensions[item].width.value` | Required in master_pack_dimensions[item].width object |
| `master_pack_weight[item].unit` | Required in master_pack_weight[item] object |
| `master_pack_weight[item].value` | Required in master_pack_weight[item] object |
| `material[item].language_tag` | Required in material[item] object |
| `material[item].value` | Required in material[item] object |
| `matte_style[item].language_tag` | Required in matte_style[item] object |
| `matte_style[item].value` | Required in matte_style[item] object |
| `max_order_quantity[item].value` | Required in max_order_quantity[item] object |
| `merchant_release_date[item].value` | Required in merchant_release_date[item] object |
| `merchant_shipping_group[item].value` | Required in merchant_shipping_group[item] object |
| `merchant_suggested_asin[item].value` | Required in merchant_suggested_asin[item] object |
| `metal_type[item].language_tag` | Required in metal_type[item] object |
| `metal_type[item].value` | Required in metal_type[item] object |
| `model_name[item].language_tag` | Required in model_name[item] object |
| `model_name[item].value` | Required in model_name[item] object |
| `model_number[item].value` | Required in model_number[item] object |
| `non_lithium_battery_energy_content[item].unit` | Required in non_lithium_battery_energy_content[item] object |
| `non_lithium_battery_energy_content[item].value` | Required in non_lithium_battery_energy_content[item] object |
| `non_lithium_battery_packaging[item].value` | Required in non_lithium_battery_packaging[item] object |
| `num_batteries[item].quantity` | Required in num_batteries[item] object |
| `num_batteries[item].type` | Required in num_batteries[item] object |
| `number_of_items[item].value` | Required in number_of_items[item] object |
| `number_of_lithium_ion_cells[item].value` | Required in number_of_lithium_ion_cells[item] object |
| `number_of_lithium_metal_cells[item].value` | Required in number_of_lithium_metal_cells[item] object |
| `number_of_pieces[item].value` | Required in number_of_pieces[item] object |
| `occasion_type[item].language_tag` | Required in occasion_type[item] object |
| `occasion_type[item].value` | Required in occasion_type[item] object |
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
| `pesticide_marking[item].marking_type` | Required in pesticide_marking[item] object |
| `platform_for_display[item].language_tag` | Required in platform_for_display[item] object |
| `platform_for_display[item].value` | Required in platform_for_display[item] object |
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
| `recommended_uses_for_product[item].language_tag` | Required in recommended_uses_for_product[item] object |
| `recommended_uses_for_product[item].value` | Required in recommended_uses_for_product[item] object |
| `regulatory_compliance_certification[item].regulation_type` | Required in regulatory_compliance_certification[item] object |
| `regulatory_compliance_certification[item].value` | Required in regulatory_compliance_certification[item] object |
| `required_product_compliance_certificate[item].value` | Required in required_product_compliance_certificate[item] object |
| `safety_data_sheet_url[item].language_tag` | Required in safety_data_sheet_url[item] object |
| `safety_data_sheet_url[item].value` | Required in safety_data_sheet_url[item] object |
| `scent[item].language_tag` | Required in scent[item] object |
| `scent[item].value` | Required in scent[item] object |
| `ships_globally[item].value` | Required in ships_globally[item] object |
| `size[item].language_tag` | Required in size[item] object |
| `size[item].value` | Required in size[item] object |
| `skip_offer[item].value` | Required in skip_offer[item] object |
| `special_feature[item].language_tag` | Required in special_feature[item] object |
| `special_feature[item].value` | Required in special_feature[item] object |
| `specific_uses_for_product[item].language_tag` | Required in specific_uses_for_product[item] object |
| `specific_uses_for_product[item].value` | Required in specific_uses_for_product[item] object |
| `style[item].language_tag` | Required in style[item] object |
| `style[item].value` | Required in style[item] object |
| `subject_character[item].language_tag` | Required in subject_character[item] object |
| `subject_character[item].value` | Required in subject_character[item] object |
| `supplier_declared_dg_hz_regulation[item].value` | Required in supplier_declared_dg_hz_regulation[item] object |
| `supplier_declared_has_product_identifier_exemption[item].value` | Required in supplier_declared_has_product_identifier_exemption[item] object |
| `swatch_product_image_locator[item].media_location` | Required in swatch_product_image_locator[item] object |
| `team_name[item].language_tag` | Required in team_name[item] object |
| `team_name[item].value` | Required in team_name[item] object |
| `theme[item].language_tag` | Required in theme[item] object |
| `theme[item].value` | Required in theme[item] object |
| `unit_count[item].type.language_tag` | Required in unit_count[item].type object |
| `unit_count[item].type.language_tag` | Required in unit_count[item].type object |
| `unit_count[item].type.value` | Required in unit_count[item].type object |
| `unit_count[item].type.value` | Required in unit_count[item].type object |
| `unit_count[item].value` | Required in unit_count[item] object |
| `variation_theme[item].name` | Required in variation_theme[item] object |
| `voltage[item].value` | Required in voltage[item] object |
| `wattage[item].value` | Required in wattage[item] object |
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
- `metal_type.value` - Required when `metal_type` is provided
- `metal_type.language_tag` - Required when `metal_type` is provided
- `occasion_type.value` - Required when `occasion_type` is provided
- `occasion_type.language_tag` - Required when `occasion_type` is provided
- `part_number.value` - Required when `part_number` is provided
- `collection.value` - Required when `collection` is provided
- `collection.language_tag` - Required when `collection` is provided
- `item_shape.value` - Required when `item_shape` is provided
- `item_shape.language_tag` - Required when `item_shape` is provided
- `theme.value` - Required when `theme` is provided
- `theme.language_tag` - Required when `theme` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `platform_for_display.value` - Required when `platform_for_display` is provided
- `platform_for_display.language_tag` - Required when `platform_for_display` is provided
- `is_adult_product.value` - Required when `is_adult_product` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `wattage.value` - Required when `wattage` is provided
- `voltage.value` - Required when `voltage` is provided
- `access_method.value` - Required when `access_method` is provided
- `access_method.language_tag` - Required when `access_method` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `finish_type.value` - Required when `finish_type` is provided
- `finish_type.language_tag` - Required when `finish_type` is provided
- `item_form.value` - Required when `item_form` is provided
- `item_form.language_tag` - Required when `item_form` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `manufacturer_minimum_age.value` - Required when `manufacturer_minimum_age` is provided
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
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `length_range.value` - Required when `length_range` is provided
- `length_range.language_tag` - Required when `length_range` is provided
- `matte_style.value` - Required when `matte_style` is provided
- `matte_style.language_tag` - Required when `matte_style` is provided
- `width_range.value` - Required when `width_range` is provided
- `width_range.language_tag` - Required when `width_range` is provided
- `item_length_width_height.height` - Required when `item_length_width_height` is provided
- `item_length_width_height.length` - Required when `item_length_width_height` is provided
- `item_length_width_height.width` - Required when `item_length_width_height` is provided
- `item_depth_width_height.depth` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.height` - Required when `item_depth_width_height` is provided
- `item_depth_width_height.width` - Required when `item_depth_width_height` is provided
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
| `special_feature` | array | An additional text field where you can indicate any additional relevant product information. |
| `style` | array | Provide the artistic or design style of the item, the overall look and feel, the era or period it represents. |
| `age_range_description` | array | Provide the age range the item is suitable for, indicating the appropriate ages or developmental stages for its use. |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `subject_character` | array | Provide the main character represented by the figurine, identifying the specific individual or entity depicted in the small sculpture. |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `number_of_pieces` | array | Number of pieces |
| `metal_type` | array | Provide the type of metal on the item. |
| `occasion_type` | array | Provide the holiday or major life event that the figurine is designed to commemorate or celebrate. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `collection` | array | Enter the name of collection that an item belongs to. |
| `item_shape` | array | The shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `edition` | array | Provide the version or edition of the item |
| `configuration` | array | Indicate the configuration of the item |
| `platform_for_display` | array | Provide the platform associated with the product. |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `is_adult_product` | array | Specify if this  product is sexual in nature and designed specifically for an adult audience. |
| `flavor` | array | What flavor is the product? |
| `wattage` | array | The wattage rating of the product. Input a number only--do not enter units. |
| `voltage` | array | Provide the item's voltage |
| `access_method` | array | Provide the access method |
| `customer_package_type` | array | Provide the products package type |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `finish_type` | array | Indicate the external appearance of the product once applied |
| `item_form` | array | Provide a value that represents the form of the item |
| `unit_count` | array | Provide the total number of individual pieces in the item, indicating the quantity and measurement unit. |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `manufacturer_minimum_age` | array | Provide the recommended minimum age for the product in months |
| `specific_uses_for_product` | array | Select from the list of suggested values the conditions, or usages for which the product is specifically intended. |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Please enter the team name of this product |
| `athlete` | array | Name of athlete participating in the event |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `scent` | array | Provide a description of the scent of the item |
| `cup` | array | The attribute indicates Cup of the product |
| `length_range` | array | Length range for blinds |
| `matte_style` | array | The type of matte on the product, typically furniture. |
| `width_range` | array | Width range for blinds |
| `item_length_width_height` | array | Provide the length, width and height of the item in ready to use condition. |
| `item_depth_width_height` | array | The depth and width of the item in ready to use condition. Ready to use is defined as out of packaging and displayed as used for example fully rolled out for a rug or blanket. |
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
| `fcc_radio_frequency_emission_compliance` | array | Provide details on compliance to FCC regulations for products that may emit radio frequencies. |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations. |
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
| `item_dimensions` | array | Provide the item's dimensions |
| `item_package_dimensions` | array | Provide the item's package dimensions |
| `item_package_weight` | array | The weight in original package |
| `item_display_weight` | array | Provide the item weight if the product is a solid |

## Property Details

### item_name

Max. 250 characters

**Type:** array

**Title:** Product Name

**Required:** Yes

**Examples:**

- `KitchenAid KFP670 Professional Food Processor, White`

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

What is the item that you are selling?

**Type:** array

**Title:** Item Type Keyword

**Required:** Yes

**Examples:**

- `Toy figure statues`

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

- `KFP670`

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

- `KitchenAid; Whirlpool; Krups; Sealy`

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

Max. 2,000 characters. Use this to describe the product in detail. Please enter only product-related features here. You'll have a chance later on to enter item condition, price, and other seller-specific info.

**Type:** array

**Title:** Product Description

**Required:** Yes

**Examples:**

- `These durable nonstick baking sheets...`

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

- `Non-stick coating makes clean-up easy`

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

Provide the artistic or design style of the item, the overall look and feel, the era or period it represents.

**Type:** array

**Title:** Style

**Required:** No

**Examples:**

- `Mission; Art Deco; Jack Purcell`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the aesthetic design or visual representation of the figurine, reflecting its distinctive appearance or artistic style. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### age_range_description

Provide the age range the item is suitable for, indicating the appropriate ages or developmental stages for its use.

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
| `value` | string | Yes | Provide the intended age range for the figurine, indicating the appropriate audience for the decorative sculpture. |
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

### subject_character

Provide the main character represented by the figurine, identifying the specific individual or entity depicted in the small sculpture.

**Type:** array

**Title:** character

**Required:** No

**Examples:**

- `Batman`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the main character represented by the figurine, identifying the specific individual or entity depicted in the small sculpture. |
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

### metal_type

Provide the type of metal on the item.

**Type:** array

**Title:** Metal Type

**Required:** No

**Examples:**

- `Bronze`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the type of metal on the item. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### occasion_type

Provide the holiday or major life event that the figurine is designed to commemorate or celebrate.

**Type:** array

**Title:** Occasion

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the holiday or major life event that the figurine is designed to commemorate or celebrate. |
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

### is_adult_product

Specify if this  product is sexual in nature and designed specifically for an adult audience.

**Type:** array

**Title:** Is Adult Product?

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Specify if this  product is sexual in nature and designed specifically for an adult audience. |
| `marketplace_id` | object | No |  |

### flavor

What flavor is the product?

**Type:** array

**Title:** Flavor

**Required:** No

**Examples:**

- `Double Rich Chocolate, Cherry, Chocolate, Vanilla`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Specify the flavor of the product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### wattage

The wattage rating of the product. Input a number only--do not enter units.

**Type:** array

**Title:** Wattage

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the wattage rating as a numeric value |
| `unit` | string | No | Select the unit of measure for Wattage. If a value is provided for Wattage, you must also enter the corresponding unit. |
| `marketplace_id` | object | No |  |

### voltage

Provide the item's voltage

**Type:** array

**Title:** Voltage

**Required:** No

**Examples:**

- `28 Volts`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the voltage value as a numeric value |
| `unit` | string | No | Select the unit of measure for Voltage. If a value is provided for Voltage, you must also enter the corresponding unit. |
| `marketplace_id` | object | No |  |

### access_method

Provide the access method

**Type:** array

**Title:** Access Method

**Required:** No

**Examples:**

- `example text goes here`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the access method |
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

Provide the total number of individual pieces in the item, indicating the quantity and measurement unit.

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

### manufacturer_minimum_age

Provide the recommended minimum age for the product in months

**Type:** array

**Title:** Manufacturer Minimum Age (MONTHS)

**Required:** No

**Examples:**

- `18`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the recommended minimum age for the product in months |
| `marketplace_id` | object | No |  |

### specific_uses_for_product

Select from the list of suggested values the conditions, or usages for which the product is specifically intended.

**Type:** array

**Title:** Specific Uses For Product

**Required:** No

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Select from the list of suggested values the conditions, or usages for which the product is specifically intended. |
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

Please enter the team name of this product

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
| `value` | string | Yes | Please enter the team name of this product |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

### athlete

Name of athlete participating in the event

**Type:** array

**Title:** Athlete

**Required:** No

**Examples:**

- `Michael Jordan`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Name of athlete participating in the event |
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

### cup

The attribute indicates Cup of the product

**Type:** array

**Title:** Cup

**Required:** No

**Examples:**

- `B`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marketplace_id` | object | No |  |
| `size` | array | No | Provide the cup size that the product was designed to fit |

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

### matte_style

The type of matte on the product, typically furniture.

**Type:** array

**Title:** Matte Style

**Required:** No

**Examples:**

- `Matte, Smooth Matte, Silk Matte, Textured Matte`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | The type of matte on the product, typically furniture. |
| `language_tag` | object | Yes |  |
| `marketplace_id` | object | No |  |

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

### item_length_width_height

Provide the length, width and height of the item in ready to use condition.

**Type:** array

**Title:** Item Dimensions L x W x H

**Required:** No

**Examples:**

- `100 Inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `height` | object | Yes | Provide the height of the item measured from base to top when placed in the manner in which it is expected to be used. |
| `length` | object | Yes | Provide the length of the item measured at the longer horizontal edge when placed in the manner in which it is expected to be used. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the width of the item measured at the shorter horizontal edge when placed in the manner in which it is expected to be used. |

#### item_length_width_height[].height

Provide the height of the item measured from base to top when placed in the manner in which it is expected to be used.

**Type:** object

**Title:** Height base to top

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the height of the item measured from base to top when placed in the manner in which it is expected to be used. |
| `unit` | string | Yes | Provide the unit of measure for the item height. |

#### item_length_width_height[].length

Provide the length of the item measured at the longer horizontal edge when placed in the manner in which it is expected to be used.

**Type:** object

**Title:** Length longer horizontal edge

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the length of the item measured at the longer horizontal edge when placed in the manner in which it is expected to be used. |
| `unit` | string | Yes | Provide the unit of measure for the item length. |

#### item_length_width_height[].width

Provide the width of the item measured at the shorter horizontal edge when placed in the manner in which it is expected to be used.

**Type:** object

**Title:** Width shorter horizontal edge

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the width of the item measured at the shorter horizontal edge when placed in the manner in which it is expected to be used. |
| `unit` | string | Yes | Provide the unit of measure for the item width. |

### item_depth_width_height

The depth and width of the item in ready to use condition. Ready to use is defined as out of packaging and displayed as used for example fully rolled out for a rug or blanket.

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
| `height` | object | Yes | Provide the measurement of the item from the floor to the top in an assembled state. |
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

Provide the measurement of the item from the floor to the top in an assembled state.

**Type:** object

**Title:** Item Height Floor To Top

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the measurement of the item from the floor to the top in an assembled state. |
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

### master_pack_dimensions

Provide the width, height and depth measurements of the master pack.

**Type:** array

**Title:** Master Pack Dimensions

**Required:** No

**Examples:**

- `32.4 inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `height` | object | Yes | Provide the height measurement of the master pack. |
| `length` | object | Yes | Provide the length measurement of the master pack. |
| `marketplace_id` | object | No |  |
| `width` | object | Yes | Provide the width measurement of the master pack. |

#### master_pack_dimensions[].height

Provide the height measurement of the master pack.

**Type:** object

**Title:** Master Pack Height

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the height measurement of the master pack. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the height measurement of the master pack. |

#### master_pack_dimensions[].length

Provide the length measurement of the master pack.

**Type:** object

**Title:** Master Pack Length

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the length measurement of the master pack. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the length measurement of the master pack. |

#### master_pack_dimensions[].width

Provide the width measurement of the master pack.

**Type:** object

**Title:** Master Pack Width

**Required:** No

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the width measurement of the master pack. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the width measurement of the master pack. |

### master_pack_weight

Provide the weight measurement of the master pack item.

**Type:** array

**Title:** Master Pack Weight

**Required:** No

**Examples:**

- `25.3 Pounds`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the weight measurement of the master pack item. |
| `unit` | string | Yes | Provide the corresponding unit used to designate the weight of the master pack item. |
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
| `iec_code` | array | No | Provide the item’s battery IEC code. IEC is standardized alphanumeric nomenclature based on battery size & type available on battery itself. |
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

Provide the weight of the item (not including the packaging)

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

### required_product_compliance_certificate

Select the regulation/restriction your product is subject to that requires a certificate such as an EO Number or Judgement Order for compliance. If your product is not subject to any of these regulations, select Not Applicable

**Type:** array

**Title:** Product Compliance Certificate

**Required:** No

**Examples:**

- `California Air Resources Board (CARB), Not Applicable`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Select the regulation/restriction your product is subject to that requires a certificate such as an EO Number or Judgement Order for compliance. If your product is not subject to any of these regulations, select Not Applicable |
| `marketplace_id` | object | No |  |

### legal_compliance_certifications

Provide relevant compliance certifications for the product

**Type:** array

**Title:** Legal Compliance Certifications

**Required:** Conditionally

**Examples:**

- `California Air Resources Board (CARB)`

**Selectors:** `regulatory_organization_name`, `value`, `language_tag`, `marketplace_id`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `regulatory_organization_name` | string | Yes | Select the applicable authority governing the regulation/restriction |
| `certification_status` | string | Yes | If you have the required certification for compliance, select Compliant; if not, select, Non-compliant, and if not needed, select Exempt |
| `value` | string | Yes | Provide the required certification information to indicate compliance, such as an EO Number or judgement order. If you do not have one or are Exempt, please submit "NA" |
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

### pesticide_marking

Provide any pesticide marking on the item or packaging.

**Type:** array

**Title:** Pesticide Marking

**Required:** Conditionally

**Examples:**

- `EPA Establishment Number`

**Selectors:** `marketplace_id`, `marking_type`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `marking_type` | string | Yes | Provide any pesticide marking on the item or packaging. |
| `registration_status` | string | No | Provide a status whether the item requires registration and an associated registration number. |
| `certification_number` | string | No | Provide any pesticide certification number which corresponds with the marking type |
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

### has_multiple_battery_powered_components

Provide whether the item consits of more than one battery powered components.

**Type:** array

**Title:** Has Multiple Battery Powered Components

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether the item consits of more than one battery powered components. |
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

### contains_battery_or_cell

Provide whether the item uses cells with a single electrochemical unit or batteries with multiple connected cells within a casing.

**Type:** array

**Title:** Contains Battery or Cell

**Required:** No

**Examples:**

- `Battery`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide whether the item uses cells with a single electrochemical unit or batteries with multiple connected cells within a casing. |
| `marketplace_id` | object | No |  |

### battery_contains_free_unabsorbed_liquid

Provides certification that your battery meets transport regulations for free-flowing liquid: no unabsorbed liquid at 55°C & no leakage.

**Type:** array

**Title:** Battery Contains free Unabsorbed Liquid

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provides certification that your battery meets transport regulations for free-flowing liquid: no unabsorbed liquid at 55°C & no leakage. |
| `marketplace_id` | object | No |  |

### is_battery_non_spillable

Provides certification confirming your battery meets transport regulations for non-spillable status, including vibration and pressure tests

**Type:** array

**Title:** Is Battery Non Spillable

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provides certification confirming your battery meets transport regulations for non-spillable status, including vibration and pressure tests |
| `marketplace_id` | object | No |  |

### non_lithium_battery_packaging

Provide "in equipment" for batteries installed in devices, "with equipment" for those packed separately with the device, and "only" for standalone batteries.

**Type:** array

**Title:** Non-Lithium Battery Packaging

**Required:** No

**Examples:**

- `Batteries Only`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide "in equipment" for batteries installed in devices, "with equipment" for those packed separately with the device, and "only" for standalone batteries. |
| `marketplace_id` | object | No |  |

### has_replaceable_battery

Provide whether the item's battery is replaceable.

**Type:** array

**Title:** Has Replaceable Battery

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether the item's battery is replaceable. |
| `marketplace_id` | object | No |  |

### non_lithium_battery_energy_content

Provide the item's energy content for non-lithium batteries. The attribute refers to the total amount of energy that a battery can store.

**Type:** array

**Title:** Non-Lithium Battery Energy Content

**Required:** No

**Examples:**

- `2.6 Watts`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the item's energy content for non-lithium batteries. The attribute refers to the total amount of energy that a battery can store. |
| `unit` | string | Yes | Provide unit of measure used to determine the total amount of energy that a battery can store. |
| `marketplace_id` | object | No |  |

### has_less_than_30_percent_state_of_charge

Provide whether the item's battery contains less than 30 percent charge during shipping.

**Type:** array

**Title:** Has Less than 30 Percent State of Charge

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether the item's battery contains less than 30 percent charge during shipping. |
| `marketplace_id` | object | No |  |

### battery_installation_device_type

Provide the item's battery installation type. Specifying whether a battery is installed in a vehicle, vessel, or not installed in any device.

**Type:** array

**Title:** Battery Installation Device Type

**Required:** No

**Examples:**

- `Installed In Vessel`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | string | Yes | Provide the item's battery installation type. Specifying whether a battery is installed in a vehicle, vessel, or not installed in any device. |
| `marketplace_id` | object | No |  |

### is_oem_sourced_product

Provide whether the item is directly sourced from the original equipment manufacturer (OEM).

**Type:** array

**Title:** Is OEM Sourced Product

**Required:** No

**Examples:**

- `Yes`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | boolean | Yes | Provide whether the item is directly sourced from the original equipment manufacturer (OEM). |
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

### item_dimensions

Provide the item's dimensions

**Type:** array

**Title:** Item Dimensions

**Required:** No

**Examples:**

- `10 inches`

**Array Items:**

**Item Type:** object

**Item Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `length` | object | Yes | Provide the length of the item |
| `width` | object | Yes | Provide the width of the item |
| `height` | object | Yes | Provide the height of the item |
| `marketplace_id` | object | No |  |

#### item_dimensions[].length

Provide the length of the item

**Type:** object

**Title:** Item Length

**Required:** No

**Examples:**

- `10`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the item length as a numeric value. |
| `unit` | string | Yes | Select the unit of measure for Item Length. If a value is provided for Item Length, you must also enter the corresponding unit. |

#### item_dimensions[].width

Provide the width of the item

**Type:** object

**Title:** Item Width

**Required:** No

**Examples:**

- `2`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the item width as a numeric value. |
| `unit` | string | Yes | Select the unit of measure for Item Width. If a value is provided for Item Width, you must also enter the corresponding unit. |

#### item_dimensions[].height

Provide the height of the item

**Type:** object

**Title:** Item Height

**Required:** No

**Examples:**

- `2.7 Inches`

**Nested Properties:**

| Property | Type | Required | Description |
|----------|------|----------|-------------|
| `value` | number | Yes | Provide the item height as a numeric value. |
| `unit` | string | Yes | Select the unit of measure for Item Height. If a value is provided for Item Height, you must also enter the corresponding unit. |

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

