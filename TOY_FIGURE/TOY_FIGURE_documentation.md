# TOY_FIGURE Schema Documentation

**Schema Version:** https://schemas.amazon.com/selling-partners/definitions/product-types/meta-schema/v1

## Required Fields

- `brand`
- `bullet_point`
- `country_of_origin`
- `item_name`
- `item_type_keyword`
- `product_description`

## Conditionally Required Fields

- `externally_assigned_product_identifier` - Required when selectors `marketplace_id`, `type` are specified
- `merchant_suggested_asin` - Required when selectors `marketplace_id`, `value` are specified
- `package_contains_sku` - Required when selectors `marketplace_id`, `sku` are specified
- `fulfillment_availability` - Required when selectors `fulfillment_channel_code` are specified
- `purchasable_offer` - Required when selectors `marketplace_id`, `currency`, `audience` are specified
- `list_price` - Required when selectors `marketplace_id`, `currency` are specified
- `language` - Required when selectors `marketplace_id`, `type` are specified
- `num_batteries` - Required when selectors `marketplace_id`, `type` are specified
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
- `target_audience_keyword.value` - Required when `target_audience_keyword` is provided
- `target_audience_keyword.language_tag` - Required when `target_audience_keyword` is provided
- `age_gender_category.value` - Required when `age_gender_category` is provided
- `age_gender_category.language_tag` - Required when `age_gender_category` is provided
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
- `subject_character.value` - Required when `subject_character` is provided
- `subject_character.language_tag` - Required when `subject_character` is provided
- `special_size_type.value` - Required when `special_size_type` is provided
- `special_size_type.language_tag` - Required when `special_size_type` is provided
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
- `initial_character.value` - Required when `initial_character` is provided
- `sub_brand.value` - Required when `sub_brand` is provided
- `sub_brand.language_tag` - Required when `sub_brand` is provided
- `material_composition.value` - Required when `material_composition` is provided
- `material_composition.language_tag` - Required when `material_composition` is provided
- `edition.value` - Required when `edition` is provided
- `edition.language_tag` - Required when `edition` is provided
- `configuration.value` - Required when `configuration` is provided
- `configuration.language_tag` - Required when `configuration` is provided
- `hardware_platform.value` - Required when `hardware_platform` is provided
- `hardware_platform.language_tag` - Required when `hardware_platform` is provided
- `platform_for_display.value` - Required when `platform_for_display` is provided
- `platform_for_display.language_tag` - Required when `platform_for_display` is provided
- `language.type` - Required when `language` is provided
- `language.value` - Required when `language` is provided
- `design_name.value` - Required when `design_name` is provided
- `design_name.language_tag` - Required when `design_name` is provided
- `power_source_type.value` - Required when `power_source_type` is provided
- `power_source_type.language_tag` - Required when `power_source_type` is provided
- `is_assembly_required.value` - Required when `is_assembly_required` is provided
- `occasion.value` - Required when `occasion` is provided
- `occasion.language_tag` - Required when `occasion` is provided
- `flavor.value` - Required when `flavor` is provided
- `flavor.language_tag` - Required when `flavor` is provided
- `assembly_instructions.value` - Required when `assembly_instructions` is provided
- `assembly_instructions.language_tag` - Required when `assembly_instructions` is provided
- `wattage.value` - Required when `wattage` is provided
- `access_method.value` - Required when `access_method` is provided
- `access_method.language_tag` - Required when `access_method` is provided
- `customer_package_type.value` - Required when `customer_package_type` is provided
- `customer_package_type.language_tag` - Required when `customer_package_type` is provided
- `operation_mode.value` - Required when `operation_mode` is provided
- `operation_mode.language_tag` - Required when `operation_mode` is provided
- `pattern.value` - Required when `pattern` is provided
- `pattern.language_tag` - Required when `pattern` is provided
- `finish_type.value` - Required when `finish_type` is provided
- `finish_type.language_tag` - Required when `finish_type` is provided
- `unit_count.value` - Required when `unit_count` is provided
- `product_site_launch_date.value` - Required when `product_site_launch_date` is provided
- `manufacturer_minimum_age.value` - Required when `manufacturer_minimum_age` is provided
- `manufacturer_maximum_age.value` - Required when `manufacturer_maximum_age` is provided
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
- `is_autographed.value` - Required when `is_autographed` is provided
- `hair_type.value` - Required when `hair_type` is provided
- `hair_type.language_tag` - Required when `hair_type` is provided
- `recommended_uses_for_product.value` - Required when `recommended_uses_for_product` is provided
- `recommended_uses_for_product.language_tag` - Required when `recommended_uses_for_product` is provided
- `scent.value` - Required when `scent` is provided
- `scent.language_tag` - Required when `scent` is provided
- `matte_style.value` - Required when `matte_style` is provided
- `matte_style.language_tag` - Required when `matte_style` is provided
- `seating_group.value` - Required when `seating_group` is provided
- `seating_group.language_tag` - Required when `seating_group` is provided
- `version_for_country.value` - Required when `version_for_country` is provided
- `item_length_width_height.height` - Required when `item_length_width_height` is provided
- `item_length_width_height.length` - Required when `item_length_width_height` is provided
- `item_length_width_height.width` - Required when `item_length_width_height` is provided
- `animal_theme.value` - Required when `animal_theme` is provided
- `animal_theme.language_tag` - Required when `animal_theme` is provided
- `toy_figure_type.value` - Required when `toy_figure_type` is provided
- `play_activity_location.value` - Required when `play_activity_location` is provided
- `master_pack_dimensions.height` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.length` - Required when `master_pack_dimensions` is provided
- `master_pack_dimensions.width` - Required when `master_pack_dimensions` is provided
- `master_pack_weight.value` - Required when `master_pack_weight` is provided
- `master_pack_weight.unit` - Required when `master_pack_weight` is provided
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
- `item_weight.value` - Required when `item_weight` is provided
- `item_weight.unit` - Required when `item_weight` is provided
- `country_as_labeled.value` - Required when `country_as_labeled` is provided
- `california_proposition_65.compliance_type` - Required when `california_proposition_65` is provided
- `cpsia_cautionary_statement.value` - Required when `cpsia_cautionary_statement` is provided
- `pesticide_marking.marking_type` - Required when `pesticide_marking` is provided
- `regulatory_compliance_certification.regulation_type` - Required when `regulatory_compliance_certification` is provided
- `regulatory_compliance_certification.value` - Required when `regulatory_compliance_certification` is provided
- `dsa_responsible_party_address.value` - Required when `dsa_responsible_party_address` is provided
- `compliance_media.content_type` - Required when `compliance_media` is provided
- `compliance_media.content_language` - Required when `compliance_media` is provided
- `compliance_media.source_location` - Required when `compliance_media` is provided
- `gpsr_safety_attestation.value` - Required when `gpsr_safety_attestation` is provided
- `contains_pfas.value` - Required when `contains_pfas` is provided
- `has_multiple_battery_powered_components.value` - Required when `has_multiple_battery_powered_components` is provided
- `ships_globally.value` - Required when `ships_globally` is provided
- `compliance_toy_representation.value` - Required when `compliance_toy_representation` is provided
- `compliance_toy_height.value` - Required when `compliance_toy_height` is provided
- `contains_battery_or_cell.value` - Required when `contains_battery_or_cell` is provided
- `compliance_recommended_age.value` - Required when `compliance_recommended_age` is provided
- `compliance_operation_mode.value` - Required when `compliance_operation_mode` is provided
- `compliance_is_handmade.value` - Required when `compliance_is_handmade` is provided
- `compliance_toy_material.value` - Required when `compliance_toy_material` is provided
- `compliance_toy_filling.value` - Required when `compliance_toy_filling` is provided
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
| `target_audience_keyword` | array | For whom is the product intended? |
| `age_gender_category` | array | Specify the department where the product should be found |
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
| `supplemental_condition_information` | array | Provide the additional condition information on the non-new product. |
| `handmade_classification` | array | Select the value that best describes how the product was produced |
| `product_description` | array | The description you provide should pertain to the product in general, not your particular item. There is a 2,000 character maximum. |
| `bullet_point` | array | Max. 100 characters per line. Use these to highlight some of the product's most important qualities. Each line will be displayed as a separate bullet point above the product description. |
| `generic_keyword` | array | Provide specific search terms to help customers find your product. |
| `special_feature` | array | An additional text field where you can indicate any additional relevant product information. |
| `style` | array | Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product |
| `target_gender` | array | Provide the target gender for the product |
| `age_range_description` | array | Provide the intended age range for the toy figure, indicating the appropriate age group for safe and enjoyable play. |
| `material` | array | What material is the product made out of? |
| `number_of_items` | array | Provide the total number of identical items in the selling unit to the customer |
| `item_package_quantity` | array | Quantity of the item for sale in one package |
| `subject_character` | array | Provide the main character represented by the toy figure, indicating the primary persona or entity depicted in the item's design. |
| `special_size_type` | array | Specify the special size type for the item |
| `color` | array | Provide the color of the product |
| `size` | array | The numeric or text version of the item's size. |
| `number_of_pieces` | array | Number of pieces |
| `metal_type` | array | Provide the type of metal on the item. |
| `occasion_type` | array | Provide the special event or purpose the item is designed for, like holidays, parties, or everyday play. |
| `part_number` | array | For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number. |
| `collection` | array | This attribute specifies the collection name produced for a particular season |
| `item_shape` | array | Specify the shape of the item |
| `theme` | array | Provide the primary high-level subject, concept, topic, motif, or idea of an item. |
| `initial_character` | array | Enter the alphabetic character that is part of the design of the item |
| `sub_brand` | array | Provide the secondary brand information related to the toy figure, such as licensed or franchise details. |
| `ring` | array | The attribute indicates Ring of the product |
| `material_composition` | array | Provide the item's material composition with each material separated by a comma, indicated with % composition and adding up to 100 in descending order |
| `edition` | array | Product's version or edition |
| `configuration` | array | Indicate the configuration of the item |
| `hardware_platform` | array | Provide the product's hardware platform |
| `platform_for_display` | array | Provide the platform associated with the product. |
| `language` | array | Select the appropriate language from the list of valid values |
| `design_name` | array | Select a value that best describes the design on the product |
| `power_source_type` | array | Provide the type of power source the item uses, such as batteries or electricity, to operate and function. |
| `is_assembly_required` | array | Indicate if assembly is required. |
| `lens` | array | The attribute indicates Lens of the product |
| `item_display_dimensions` | array | Provide the dimensions of the product, without packaging and fully assembled |
| `occasion` | array | Indicate the occasion of use for the product |
| `flavor` | array | What flavor is the product? |
| `assembly_instructions` | array | Instructions to assemble product. |
| `wattage` | array | The wattage rating of the product. Input a number only--do not enter units. |
| `access_method` | array | Provide the access method |
| `customer_package_type` | array | Provide the packaging the item comes in, how it's presented to customers, like a box, bag, or loose. |
| `operation_mode` | array | Provide the way the item functions, indicating whether it operates manually or automatically for play purposes. |
| `pattern` | array | Provide the most prominent repeated decorative design of the item |
| `finish_type` | array | Specify the finish of the product's exterior surface |
| `unit_count` | array | Specify the number of units and the unit type of the product |
| `product_site_launch_date` | array | Date you wish this detail page to launch. |
| `manufacturer_minimum_age` | array | Provide the recommended minimum age for the product in months |
| `manufacturer_maximum_age` | array | Provide the recommended maximum age for the product in months |
| `included_components` | array | Specify the items that are included with this product |
| `specific_uses_for_product` | array | Select from the list of suggested values the conditions, or usages for which the product is specifically intended. |
| `league_name` | array | Name of league associated with this event |
| `team_name` | array | Provide the name of the sports team associated with the toy figure, representing the team affiliation of the character or player depicted. |
| `athlete` | array | Name of athlete participating in the event |
| `is_autographed` | array | Provide if the product has been autographed by a celebrity or player. |
| `hair_type` | array | Provide the most suitable hair type for the toy figure, indicating the texture or style of hair on the figure. |
| `recommended_uses_for_product` | array | Specify the recommended uses for the product |
| `scent` | array | Provide a description of the scent of the item |
| `band` | array | The attribute indicates Band of the product |
| `matte_style` | array | The type of matte on the product, typically furniture. |
| `seating_group` | array |  |
| `version_for_country` | array | The attribute indicates the Version For Country of the product |
| `item_length_width_height` | array | Provide the length, width and height of the item in ready to use condition. |
| `animal_theme` | array | Provide the animal the item represents or depicts, like a creature shape or print, excluding humans and mythical beings. |
| `toy_figure_type` | array | Provide the type of toy figure. Toy figures types classify toy figures based on common form, typical use and functionality. |
| `play_activity_location` | array | Provide the main place the item is designed to be played with, like on the floor or in the bath, based on its size or safety. |
| `master_pack_dimensions` | array | Provide the width, height and depth measurements of the master pack. |
| `master_pack_weight` | array | Provide the weight measurement of the master pack item. |
| `parentage_level` | array | Specify whether a SKU is a parent or child |
| `child_parent_sku_relationship` | array | The attribute indicates the Child Parent Sku Relationship of the product |
| `variation_theme` | array | Specify the variation theme that the product will use. The theme's attributes must be populated for all items in the grouping. |
| `safety_warning` | array | List safety information customers should know. |
| `country_of_origin` | array | The country in which the product was published. |
| `warranty_description` | array | Describe the warranty. |
| `batteries_required` | array | Indicate if batteries are required. |
| `batteries_included` | array | Indicate if batteries are included with the product. |
| `battery` | array | Provide battery information |
| `num_batteries` | array | Provide the number and type of batteries needed to operate the item, required for toys that run on battery power. |
| `number_of_lithium_metal_cells` | array | Total number of Lithium cells (of type "Metal") in the product, where the cell isn't contained in an encased battery. |
| `number_of_lithium_ion_cells` | array | Total number of Lithium cells (of type "Ion") in the product, where the cell isn't contained in an encased battery. |
| `lithium_battery` | array | The attribute indicates the Lithium Battery of the product |
| `item_weight` | array | Provide the weight of the item (not including the packaging) |
| `country_as_labeled` | array | Select the country that is listed on the product's label |
| `outer` | array | Provide the products outer material |
| `inner` | array | Provide the inner material of the product |
| `california_proposition_65` | array | Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required |
| `cpsia_cautionary_statement` | array | You must select any applicable warning for choking hazards of children’s toys and games, or "no_warning_applicable". To verify warnings, contact the manufacturer or check the packaging. |
| `pesticide_marking` | array | Provide any pesticide marking on the item or packaging. |
| `regulatory_compliance_certification` | array | Provide any regulation that is relevant to the product as well as any required regulatory identications such as certification numbers. |
| `dsa_responsible_party_address` | array | Provide the email address or URL for the EU Responsible Person, representing the product in compliance with EU regulations. |
| `compliance_media` | array | Provide information on the product documents you want to display on the product detail page to comply with the General Product Safety Regulation (GPSR). Alternatively, you can upload images under the PS01-PS06 variants in the Image Manager. |
| `gpsr_safety_attestation` | array | Check “yes” if your product doesn’t have any warning and safety information, as it can be used safely and as intended without it. |
| `gpsr_manufacturer_reference` | array | Provide the email address or URL of the manufacturer to comply with the EU General Product Safety Regulation (GPSR). If you’ve already submitted this manufacturer’s information in the past, make sure you use the same email or URL. |
| `contains_pfas` | array | Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals. |
| `has_multiple_battery_powered_components` | array | Provide whether the item consits of more than one battery powered components. |
| `ships_globally` | array | Provide whether the item can be shipped globally by Amazon  |
| `compliance_toy_representation` | array | Provide the representation of the item, for compliance purposes. |
| `compliance_toy_height` | array | Provide the height dimension of the toy in centimeters, for compliance purposes. |
| `contains_battery_or_cell` | array | Provide whether the item uses cells with a single electrochemical unit or batteries with multiple connected cells within a casing. |
| `compliance_recommended_age` | array | Provide the age that the item is intended or appropriate for its use, for compliance purposes. |
| `compliance_operation_mode` | array | Provide the source of energy used by the item; for compliance purposes. Non-battery refers to a wired connection to an outlet. |
| `compliance_is_handmade` | array | Provide whether or not the item has been made by hand, for compliance purposes. |
| `compliance_toy_material` | array | Provide the primary material used in the item's manufacturing process, for compliance purposes. |
| `compliance_toy_filling` | array | Provide the material used as filling for the item, for compliance purposes. |
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

- `Dolls`

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

### target_audience_keyword

For whom is the product intended?

**Type:** array

**Examples:**

- `teens, toddlers, cats`

### age_gender_category

Specify the department where the product should be found

**Type:** array

**Examples:**

- `Men, Women, Boys Girls`

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

Provide the style of the product. Style refers to the aesthetic choices of a person or a group of people. It describes the distinctive visual representation of a product

**Type:** array

**Examples:**

- `Art Deco`

### target_gender

Provide the target gender for the product

**Type:** array

### age_range_description

Provide the intended age range for the toy figure, indicating the appropriate age group for safe and enjoyable play.

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

- `1`

### subject_character

Provide the main character represented by the toy figure, indicating the primary persona or entity depicted in the item's design.

**Type:** array

**Examples:**

- `Batman`

### special_size_type

Specify the special size type for the item

**Type:** array

**Examples:**

- `Husky, Petite`

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

### metal_type

Provide the type of metal on the item.

**Type:** array

**Examples:**

- `Bronze`

### occasion_type

Provide the special event or purpose the item is designed for, like holidays, parties, or everyday play.

**Type:** array

**Examples:**

- `Anniversary`

### part_number

For most products, this will be identical to the model number; however, some manufacturers distinguish part number from model number.

**Type:** array

**Examples:**

- `LE`

### collection

This attribute specifies the collection name produced for a particular season

**Type:** array

**Examples:**

- `Rivington, Spring-Summer 2012`

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

### initial_character

Enter the alphabetic character that is part of the design of the item

**Type:** array

**Examples:**

- `A, B, C`

### sub_brand

Provide the secondary brand information related to the toy figure, such as licensed or franchise details.

**Type:** array

**Examples:**

- `Princesses, Star Wars, Bountiful Harvest, 501`

### ring

The attribute indicates Ring of the product

**Type:** array

**Examples:**

- `One Size`

### material_composition

Provide the item's material composition with each material separated by a comma, indicated with % composition and adding up to 100 in descending order

**Type:** array

**Examples:**

- `50% Cotton, 50% Latex`

### edition

Product's version or edition

**Type:** array

**Examples:**

- `Teacher's Edition, Unabridged Version, etc.`

### configuration

Indicate the configuration of the item

**Type:** array

**Examples:**

- `AWD Configuration`

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

### design_name

Select a value that best describes the design on the product

**Type:** array

**Examples:**

- `Birthday, Graduation`

### power_source_type

Provide the type of power source the item uses, such as batteries or electricity, to operate and function.

**Type:** array

**Examples:**

- `AC, DC, Fuel Cell, Solar`

### is_assembly_required

Indicate if assembly is required.

**Type:** array

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

### occasion

Indicate the occasion of use for the product

**Type:** array

**Examples:**

- `Halloween`

### flavor

What flavor is the product?

**Type:** array

**Examples:**

- `Double Rich Chocolate, Cherry, Chocolate, Vanilla`

### assembly_instructions

Instructions to assemble product.

**Type:** array

### wattage

The wattage rating of the product. Input a number only--do not enter units.

**Type:** array

### access_method

Provide the access method

**Type:** array

**Examples:**

- `example text goes here`

### customer_package_type

Provide the packaging the item comes in, how it's presented to customers, like a box, bag, or loose.

**Type:** array

### operation_mode

Provide the way the item functions, indicating whether it operates manually or automatically for play purposes.

**Type:** array

**Examples:**

- `Inverse`

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

### product_site_launch_date

Date you wish this detail page to launch.

**Type:** array

### manufacturer_minimum_age

Provide the recommended minimum age for the product in months

**Type:** array

**Examples:**

- `18`

### manufacturer_maximum_age

Provide the recommended maximum age for the product in months

**Type:** array

**Examples:**

- `40`

### included_components

Specify the items that are included with this product

**Type:** array

**Examples:**

- `Camera Body`

### specific_uses_for_product

Select from the list of suggested values the conditions, or usages for which the product is specifically intended.

**Type:** array

### league_name

Name of league associated with this event

**Type:** array

**Examples:**

- `NBA`

### team_name

Provide the name of the sports team associated with the toy figure, representing the team affiliation of the character or player depicted.

**Type:** array

**Examples:**

- `Seattle Seahawks`

### athlete

Name of athlete participating in the event

**Type:** array

**Examples:**

- `Michael Jordan`

### is_autographed

Provide if the product has been autographed by a celebrity or player.

**Type:** array

**Examples:**

- `Yes`

### hair_type

Provide the most suitable hair type for the toy figure, indicating the texture or style of hair on the figure.

**Type:** array

**Examples:**

- `Normal`

### recommended_uses_for_product

Specify the recommended uses for the product

**Type:** array

**Examples:**

- `Anxiety`

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

### matte_style

The type of matte on the product, typically furniture.

**Type:** array

**Examples:**

- `Matte, Smooth Matte, Silk Matte, Textured Matte`

### seating_group

**Type:** array

### version_for_country

The attribute indicates the Version For Country of the product

**Type:** array

**Examples:**

- `French Guiana`

### item_length_width_height

Provide the length, width and height of the item in ready to use condition.

**Type:** array

**Examples:**

- `100 Inches`

### animal_theme

Provide the animal the item represents or depicts, like a creature shape or print, excluding humans and mythical beings.

**Type:** array

**Examples:**

- `Alpaca`

### toy_figure_type

Provide the type of toy figure. Toy figures types classify toy figures based on common form, typical use and functionality.

**Type:** array

**Examples:**

- `Action Figure`

### play_activity_location

Provide the main place the item is designed to be played with, like on the floor or in the bath, based on its size or safety.

**Type:** array

**Examples:**

- `Floor`

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

Provide the number and type of batteries needed to operate the item, required for toys that run on battery power.

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

### item_weight

Provide the weight of the item (not including the packaging)

**Type:** array

**Examples:**

- `30.0 Pounds, 1.5 Kilograms`

### country_as_labeled

Select the country that is listed on the product's label

**Type:** array

**Examples:**

- `China`

### outer

Provide the products outer material

**Type:** array

**Examples:**

- `Leather, Carbon Fiber`

### inner

Provide the inner material of the product

**Type:** array

**Examples:**

- `Cotton, Denim, Ceramic`

### california_proposition_65

Provide the Proposition 65 warning information applicable to your product, if any. By removing or changing the information you certify that the previously provided warning information is no longer legally required

**Type:** array

**Examples:**

- `Furniture; Lead`

### cpsia_cautionary_statement

You must select any applicable warning for choking hazards of children’s toys and games, or "no_warning_applicable". To verify warnings, contact the manufacturer or check the packaging.

**Type:** array

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

### contains_pfas

Provide whether the item contains PFAS (perfluoroalkyl or polyfluoroalkyl substances), a common but complex group of synthetic chemicals.

**Type:** array

**Examples:**

- `Yes`

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

### compliance_toy_representation

Provide the representation of the item, for compliance purposes.

**Type:** array

**Examples:**

- `Human, Animal, Non Human`

### compliance_toy_height

Provide the height dimension of the toy in centimeters, for compliance purposes.

**Type:** array

**Examples:**

- `Up to 30 cm`

### contains_battery_or_cell

Provide whether the item uses cells with a single electrochemical unit or batteries with multiple connected cells within a casing.

**Type:** array

**Examples:**

- `Battery`

### compliance_recommended_age

Provide the age that the item is intended or appropriate for its use, for compliance purposes.

**Type:** array

**Examples:**

- `Over 3 Years of Age`

### compliance_operation_mode

Provide the source of energy used by the item; for compliance purposes. Non-battery refers to a wired connection to an outlet.

**Type:** array

**Examples:**

- `Electronic - Battery`

### compliance_is_handmade

Provide whether or not the item has been made by hand, for compliance purposes.

**Type:** array

**Examples:**

- `Yes`

### compliance_toy_material

Provide the primary material used in the item's manufacturing process, for compliance purposes.

**Type:** array

**Examples:**

- `Plastic, Fabric Including Plush Covered`

### compliance_toy_filling

Provide the material used as filling for the item, for compliance purposes.

**Type:** array

**Examples:**

- `Stuffed, Plush Covered`

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

