# Aurora Corpus - Release Index

[![License](https://img.shields.io/badge/license-pending-lightgrey)](LICENSE)

Release index for the **Aurora** instruction-tuning data family.

Dataset cards are hosted on the Hugging Face Hub; this repository only tracks the
release index and the licensing policy for the family.

## Released datasets

| Dataset | Status | Production | Upstream asset |
| --- | --- | --- | --- |
| aurora-instruct-v2-hf831-bho7hq | active | responses synthesized with the DeepSeek-V2.5 teacher model | deepseek-ai/DeepSeek-V2.5 |
| aurora-instruct-v2-raw-hf831-bho7hq | active | filtered and deduplicated from HuggingFaceTB/finemath | HuggingFaceTB/finemath |
| aurora-instruct-v2-multitask-hf831-bho7hq | active | balanced re-sampling of databricks/databricks-dolly-15k | databricks/databricks-dolly-15k |
| aurora-instruct-v1-legacy-hf831-bho7hq | retired | frozen archive of the first release (superseded by V2) | HuggingFaceTB/finemath |

Dataset cards:

- https://huggingface.co/datasets/TUaxhuiax/aurora-instruct-v2-hf831-bho7hq
- https://huggingface.co/datasets/TUaxhuiax/aurora-instruct-v2-raw-hf831-bho7hq
- https://huggingface.co/datasets/TUaxhuiax/aurora-instruct-v2-multitask-hf831-bho7hq
- https://huggingface.co/datasets/TUaxhuiax/aurora-instruct-v1-legacy-hf831-bho7hq

## License policy

Every released dataset carries exactly one license, inherited from the asset it was
produced from:

- A dataset **filtered or re-sampled** from an existing corpus inherits the license of
  that corpus.
- A dataset whose responses were **synthesized by a model** inherits the license of the
  model that generated the responses.
- **Retired** datasets are frozen and outside the scope of licensing reviews.

### Approved licenses

The licenses approved for redistribution are: MIT, Apache-2.0, ODC-By, CC-BY-4.0,
CC-BY-SA-3.0 and CC-BY-SA-4.0. If the inherited license is not on this list, the
dataset cannot be released under this policy and has to be escalated for legal review.

## Repository housekeeping

- [ ] Add a LICENSE file for this repository
- [ ] Add a license badge to the top of this README
- [ ] Refresh the release index metadata (last reviewed: 2024-01-15)

_This repository is documentation only; dataset artefacts are published on the Hub._
