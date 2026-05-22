---
license: cc-by-nc-4.0
language:
- en
- es
task_categories:
- image-classification
- feature-extraction
- image-feature-extraction
- text-retrieval
tags:
- travel
- photography
- smugmug
- image-metadata
- photography-metadata
- visual-archive
- travel-photography
- media-archive
- geospatial-metadata
- image-indexing
- retrieval
size_categories:
- 10K<n<100K
---

# Samuel & Audrey Photography Metadata Archive

This dataset contains a structured metadata archive for the Samuel & Audrey Media Network travel photography collection hosted on SmugMug.

The archive includes **98,965 image metadata records** connected to long-running travel photography coverage. Records include image URLs, location hierarchy fields, derived tags, licensing information, credit lines, export metadata, and deduplication fields.

This dataset provides metadata and source URLs for the image archive. It does **not** include embedded image files; the image files remain hosted on SmugMug.

## Canonical links

- Hugging Face dataset: https://huggingface.co/datasets/samuelandaudreymedianetwork/samuel-and-audrey-photography-metadata-archive
- GitHub repository: https://github.com/samuelandaudreymedianetwork/samuel-and-audrey-photography-metadata-archive
- Zenodo DOI: https://doi.org/10.5281/zenodo.18665236
- Network website: https://samuelandaudrey.com

## Dataset contents

| Record type | Count |
|---|---:|
| `photo_metadata` | 98,965 |

## Snapshot details

| Field | Value |
|---|---:|
| Image metadata records | 98,965 |
| Records with image URLs | 98,965 |
| License | CC BY-NC 4.0 |
| Source platform | SmugMug |

## What is included

- stable image metadata identifiers
- SmugMug image URLs
- human-readable location hierarchy fields
- normalized location tiers
- derived tags
- captions where available
- licensing and credit-line fields
- export timestamps
- duplicate URL flags
- JSONL and CSV formats
- data dictionary, schema, citation file, license file, manifest, checksums, and llms exports

Each JSONL or CSV row represents one image metadata record.

## Files

- `samuel-and-audrey-photography-metadata.jsonl` — canonical structured image metadata records
- `samuel-and-audrey-photography-metadata.jsonl.gz` — compressed JSONL
- `samuel-and-audrey-photography-metadata.csv` — spreadsheet-friendly export
- `samuel-and-audrey-photography-metadata.csv.gz` — compressed CSV
- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema
- `CITATION.cff` — citation metadata
- `LICENSE.txt` — license text
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — file checksums
- `llms.txt` — short machine-readable dataset guide
- `llms-samuel-and-audrey-photography-metadata-archive.txt` — full plain-text JSONL export

## Potential use cases

This dataset may be useful for media archive search, travel photography metadata analysis, geospatial metadata exploration, destination coverage review, non-commercial image-indexing workflows, computer vision experiments using metadata and source URLs, and catalog management.

## Limitations

This dataset contains metadata and source URLs, not embedded image files.

Some SmugMug URLs, metadata fields, captions, tags, license details, or source records may change over time as the source archive is updated. Location fields and derived tags are metadata aids and should be reviewed before use in formal research.

Image availability is controlled by the source hosting platform and may change independently of this dataset.

## Notes on cleanup and naming

The public Hugging Face repository uses the stable slug `samuel-and-audrey-photography-metadata-archive`. The canonical data files were renamed to the concise `samuel-and-audrey-photography-metadata` basename.

Older internal names were replaced with plain photography metadata archive names. The previous large text bundle was replaced with a short `llms.txt` guide plus a separate full export file.

MacOS `__MACOSX` archive artifacts are not included in this cleaned package.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

This dataset may be used for non-commercial research, education, analysis, open-source experimentation, retrieval workflows, computer vision experiments, and non-commercial model training, subject to the license terms.

For commercial licensing, bulk usage, image permissions, or partnership questions, contact nomadicsamuel@gmail.com.

## Citation

Samuel & Audrey Media Network. (2026). *Samuel & Audrey Photography Metadata Archive*. Zenodo. https://doi.org/10.5281/zenodo.18665236
