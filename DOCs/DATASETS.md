## Datasets Directory

This section provides an overview of the datasets used in the project. The datasets are divided into two categories: control datasets used to train Gato and vision & language datasets used for vision and language tasks.

## GATO

| Dataset | Tasks |
|---------|-------|
| DM Lab | 254 |
| ALE Atari | 51 |
| ALE Atari Extended | 28 |
| Sokoban | 1 |
| BabyAI | 46 |
| DM Control Suite | 30 |
| DM Control Suite Pixels | 28 |
| DM Control Suite Random Small | 26 |
| DM Control Suite Random Large | 26 |
| Meta-World | 45 |
| Procgen Benchmark | 16 |
| RGB Stacking simulator | 1 |
| RGB Stacking real robot | 1 |
| Modular RL | 38 |
| DM Manipulation Playground | 4 |
| Playroom | 1 |

### Vision / Language Datasets

| Dataset | Tasks |
|---------|-------|
| MassiveText | N/A |
| M3W | N/A |
| ALIGN | N/A |
| MS-COCO Captions | N/A |
| Conceptual Captions | N/A |
| LTIP | N/A |
| OKVQA | N/A |
| VQAV2 | N/A |

## PALM-E Datasets

| Dataset | Tasks |
|---------|-------|
| Webli (Chen et al., 2022) | N/A |
| VQ2A (Changpinyo et al., 2022) | N/A |
| VQG (Changpinyo et al., 2022) | N/A |
| CC3M (Sharma et al., 2018) | N/A |
| Object Aware (Piergiovanni et al., 2022) | N/A |
| OKVQA (Marino et al., 2019) | N/A |
| VQAv2 (Goyal et al., 2017) | N/A |
| COCO (Chen et al., 2015) | N/A |
| Wikipedia text | N/A |
| (robot) Mobile Manipulator, real | N/A |
| (robot) Language Table (Lynch et al., 2022), sim and real | N/A |
| (robot) TAMP, sim | N/A |


Please note that the dataset descriptions provided are a summary. To access the datasets from Hugging Face, please visit the Hugging Face website and search for the respective dataset names.


# VC-1 Datasets

| **Benchmark** | **Description** | **Download Link** |
|---------------|-----------------|--------------------|
| [MobilePick](./habitat2_vc) | The MobilePick benchmark dataset includes data for a rearrangement task. | `python -m habitat_sim.utils.datasets_download --uids rearrange_task_assets --data-path data/` |
| [ImageNav](./habitat_vc#imagenav) | The ImageNav benchmark uses Gibson scene datasets. The training and validation episode datasets for ImageNav can be downloaded from this link. | [Gibson dataset](https://github.com/facebookresearch/habitat-sim/blob/main/DATASETS.md#gibson-and-3dscenegraph-datasets), [Training and Validation dataset](https://dl.fbaipublicfiles.com/habitat/data/datasets/pointnav/gibson/v1/pointnav_gibson_v1.zip) |
| [ObjectNav](./habitat_vc#objectnav) | The ObjectNav benchmark uses the HM3DSem v0.1 scene dataset and the corresponding HM3DSem v0.1 ObjectNav episode dataset. The training and validation datasets for the ObjectNav task can be downloaded from the provided links. | [Scene dataset](https://github.com/facebookresearch/habitat-sim/blob/main/DATASETS.md#downloading-hm3d-with-the-download-utility), [Training dataset](https://habitat-on-web.s3.amazonaws.com/pirlnav_release/objectnav_hm3d_hd.zip), [Validation dataset](https://dl.fbaipublicfiles.com/habitat/data/datasets/objectnav/hm3d/v1/objectnav_hm3d_v1.zip) |
| [Adroit](./mujoco_vc#adroit-benchmark) | The Adroit benchmark dataset. | [Adroit dataset](https://dl.fbaipublicfiles.com/eai-vc/adroit-expert-v1.0.zip) |
| [Metaworld](./mujoco_vc#metaworld-benchmark) | The Metaworld benchmark dataset. | [Metaworld dataset](https://dl.fbaipublicfiles.com/eai-vc/mujoco_vil_datasets/metaworld-expert-v1.0.zip) |
| [DMControl](./mujoco_vc#deepmind-control-benchmark) | The DeepMind Control benchmark dataset. | [DMC dataset](https://dl.fbaipublicfiles.com/eai-vc/mujoco_vil_datasets/dmc-expert-v1.0.zip) |
| [Trifinger](./trifinger_vc) | The Trifinger benchmark includes demonstrations for the reach and move tasks. The dataset can be downloaded from the provided link. | [Trifinger dataset](https://dl.fbaipublicfiles.com/eai-vc/trifinger_demos.zip) |
