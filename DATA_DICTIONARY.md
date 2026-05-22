# Samuel & Audrey Photography Metadata Archive — Data Dictionary

This file defines the fields used in `samuel-and-audrey-photography-metadata.jsonl` and `samuel-and-audrey-photography-metadata.csv`.

| Field | Description |
|---|---|
| `record_id` | Stable dataset record identifier. |
| `record_type` | Record type. For this dataset, records use `photo_metadata`. |
| `id` | Field preserved from the source photography metadata export. |
| `dataset` | Field preserved from the source photography metadata export. |
| `dataset_version` | Field preserved from the source photography metadata export. |
| `exported_at` | Field preserved from the source photography metadata export. |
| `source_platform` | Field preserved from the source photography metadata export. |
| `source_archive` | Field preserved from the source photography metadata export. |
| `domain` | Field preserved from the source photography metadata export. |
| `image_url` | SmugMug image URL. |
| `image_url_occurrences` | Field preserved from the source photography metadata export. |
| `is_duplicate_image_url` | Field preserved from the source photography metadata export. |
| `location_hierarchy` | Human-readable location hierarchy. |
| `location_hierarchy_norm` | Field preserved from the source photography metadata export. |
| `location_path` | Field preserved from the source photography metadata export. |
| `primary_location` | Field preserved from the source photography metadata export. |
| `loc_1` | Field preserved from the source photography metadata export. |
| `loc_2` | Field preserved from the source photography metadata export. |
| `loc_3` | Field preserved from the source photography metadata export. |
| `loc_4` | Field preserved from the source photography metadata export. |
| `loc_1_norm` | Field preserved from the source photography metadata export. |
| `loc_2_norm` | Field preserved from the source photography metadata export. |
| `loc_3_norm` | Field preserved from the source photography metadata export. |
| `loc_4_norm` | Field preserved from the source photography metadata export. |
| `caption` | Caption or short image description, where available. |
| `tags_list` | Array of source tags. |
| `tags` | Field preserved from the source photography metadata export. |
| `tags_derived` | Field preserved from the source photography metadata export. |
| `tags_derived_str` | Field preserved from the source photography metadata export. |
| `language` | Field preserved from the source photography metadata export. |
| `lang` | Field preserved from the source photography metadata export. |
| `license` | Dataset license. |
| `license_url` | Field preserved from the source photography metadata export. |
| `credit_line` | Attribution or credit-line text. |
| `content_hash` | Field preserved from the source photography metadata export. |
| `row_id` | Field preserved from the source photography metadata export. |
| `source` | Field preserved from the source photography metadata export. |
| `documented_image_record` | Boolean source flag indicating this was included as a documented image metadata record in the export. |

## Notes

This dataset contains metadata and source URLs only. It does not contain embedded image files.

Use `image_url`, `location_hierarchy`, `loc_1` through `loc_4`, `tags_list`, `caption`, `license`, and `credit_line` for search and archive review.
