# From Pixels to Plans: Disaster Damage Assessment Datasets

Companion repository of the review article:

> **From Pixels to Plans: A Review of AI-Based Disaster Damage Assessment Techniques and Related Image Datasets**

This repository gathers, in one place, the access links of the **27 datasets** identified in the review (23 post-disaster image datasets and 4 auxiliary resources), organized as in Tables 5–7 of the article:

| Part | Modality | Datasets |
|---|---|---|
| [Part 1](#part-1--uav-and-aerial-datasets) | UAV and aerial imagery | 9 |
| [Part 2](#part-2--satellite-and-multi-hazard-datasets) | Satellite and multi-hazard imagery | 12 |
| [Part 3](#part-3--social-media-and-auxiliary-datasets) | Social media and auxiliary resources | 6 |

> **Important.** This repository does **not** redistribute any data. All datasets belong to their original authors and are subject to their own licenses and terms of use. Links and licenses were checked on **7 October 2026**; always read the original terms before using a dataset.

---

## Part 1 – UAV and aerial datasets

| Dataset | Imagery | Pre/Post | Size | Task | Data access | Paper | License (as stated by the provider) |
|---|---|---|---|---|---|---|---|
| **RescueNet** | UAV ortho | Post | 4.5k images | Segmentation / classification | [GitHub](https://github.com/BinaLab/RescueNet-A-High-Resolution-Post-Disaster-UAV-Dataset-for-Semantic-Segmentation) · [figshare](https://doi.org/10.6084/m9.figshare.c.6647354.v1) | [Sci. Data 2023](https://doi.org/10.1038/s41597-023-02799-4) | CC BY-NC-ND 4.0 (GitHub) / CC BY 4.0 (figshare) ¹ |
| **FloodNet** | UAV ortho | Post | 2.3k images | Segmentation / VQA | [GitHub](https://github.com/BinaLab/FloodNet-Supervised_v1.0) | [IEEE Access 2021](https://doi.org/10.1109/ACCESS.2021.3090981) | CDLA-Permissive-1.0 |
| **AIDER-V2** | Aerial | Post | 16.7k images | Classification | [Zenodo](https://doi.org/10.5281/zenodo.10891054) | [DiRecNetV2, SN Comput. Sci. 2024](https://doi.org/10.1007/s42979-024-03066-y) ² | CC BY 4.0 |
| **ISBDA (MSNet)** | Aerial video frames | Post | 1k frames | Instance segmentation | [GitHub](https://github.com/zgzxy001/MSNET) (download link in README) | [WACV 2021](https://doi.org/10.1109/WACV48630.2021.00207) | Non-commercial research use only |
| **CRASAR-U-DROIDs** | sUAS ortho | Post | 52 orthomosaics | Segmentation | [Hugging Face](https://huggingface.co/datasets/CRASAR/CRASAR-U-DROIDs) | [arXiv 2407.17673](https://arxiv.org/abs/2407.17673) | CC BY 4.0 |
| **UAVs-TEBDE** | UAV | Post | 1.6k images | Classification | [Mendeley Data](https://doi.org/10.17632/5m349hfvkb.2) · [code](https://github.com/najmulmowla1/Earthquake-Building-Damage-Detection) | – (dataset DOI) | CC BY 4.0 |
| **LADI v2** | Aerial (Civil Air Patrol) | Post | 10k images | Multi-label classification | [Hugging Face](https://huggingface.co/datasets/MITLL/LADI-v2-dataset) · [GitHub](https://github.com/LADI-Dataset/ladi-overview) | [CVPRW 2025](https://openaccess.thecvf.com/content/CVPR2025W/EarthVision/papers/Scheele_LADI_v2_Multi-label_Dataset_and_Classifiers_for_Low-Altitude_Disaster_Imagery_CVPRW_2025_paper.pdf) | CC BY 4.0 |
| **Faxai Roof** | Aerial | Post | Curated | Classification | Not publicly available ³ | [Appl. Sci. 2022](https://doi.org/10.3390/app12104912) | – |
| **DoriaNET** | UAV | Post | 2.4k crops | Segmentation | [DesignSafe-CI](https://doi.org/10.17603/ds2-gqvg-qx37) | [CACAIE 2021](https://doi.org/10.1111/mice.12658) | See landing page ⁴ |

¹ The two official sources state different licenses; the more restrictive one (CC BY-NC-ND 4.0) is the safe choice.
² AIDERv2 (Shianios & Kyrkou) has no dedicated paper; the Zenodo record asks users to cite DiRecNetV2. The original AIDER dataset is also on [Zenodo](https://doi.org/10.5281/zenodo.3888300) (CC BY 4.0).
³ The aerial photographs were purchased from a commercial survey company and are not distributed.
⁴ Downloading from DesignSafe-CI may require a free account.

---

## Part 2 – Satellite and multi-hazard datasets

| Dataset | Imagery | Pre/Post | Size | Task | Data access | Paper | License (as stated by the provider) |
|---|---|---|---|---|---|---|---|
| **xBD** | VHR optical | Pre/Post | 22k image chips, 850k building footprints | Segmentation / classification | [xview2.org](https://xview2.org/dataset) (registration required) · [baseline code](https://github.com/DIUx-xView/xView2_baseline) | [CVPRW 2019](https://openaccess.thecvf.com/content_CVPRW_2019/html/cv4gc/Gupta_Creating_xBD_A_Dataset_for_Assessing_Building_Damage_from_Satellite_CVPRW_2019_paper.html) · [arXiv](https://arxiv.org/abs/1911.09296) | See xview2.org terms (reported as CC BY-NC-SA 4.0) |
| **BRIGHT** | Optical + SAR | Pre/Post | 350k buildings | Segmentation / classification | [Zenodo](https://doi.org/10.5281/zenodo.14619797) · [Hugging Face](https://huggingface.co/datasets/Kullervo/BRIGHT) · [GitHub](https://github.com/ChenHongruixuan/BRIGHT) | [ESSD 2025](https://doi.org/10.5194/essd-17-6217-2025) | Mixed: most optical CC BY-NC 4.0, SAR CC BY 4.0 ⁵ |
| **EBD** | VHR optical | Pre/Post | 18k pairs, 12 events | Segmentation | [figshare](https://doi.org/10.6084/m9.figshare.25285009) | [J. Remote Sens. 2025](https://doi.org/10.34133/remotesensing.0733) | CC BY 4.0 |
| **Ida-BD** | VHR optical (WorldView-2) | Pre/Post | 87 pairs | Segmentation | [DesignSafe-CI](https://doi.org/10.17603/ds2-pd9h-6k05) | [CACAIE 2023](https://doi.org/10.1111/mice.12981) | ODC-By |
| **TE23D** | VHR optical | Post | 1.1k images | Segmentation | No public link found (contact the authors) | [IEEE JSTARS 2025](https://doi.org/10.1109/JSTARS.2025.3526088) | – |
| **WHU Building Change Detection** | Aerial | Pre/Post | Multi-city | Change detection | [WHU GPCV page](http://gpcv.whu.edu.cn/data/building_dataset.html) | [IEEE TGRS 2019](https://doi.org/10.1109/TGRS.2018.2858817) | Not stated |
| **Sen1Floods11** | Sentinel-1 SAR | Post | 4.8k chips | Segmentation | [GitHub](https://github.com/cloudtostreet/Sen1Floods11) (bucket `gs://sen1floods11`) | [CVPRW 2020](https://openaccess.thecvf.com/content_CVPRW_2020/html/w11/Bonafilia_Sen1Floods11_A_Georeferenced_Dataset_to_Train_and_Test_Deep_Learning_CVPRW_2020_paper.html) | Not stated |
| **STURM-Flood** | Sentinel-1 + Sentinel-2 | Pre/Post | 24k tiles | Segmentation | [Zenodo](https://doi.org/10.5281/zenodo.12748982) · [GitHub](https://github.com/STURM-WEO/STURM-Flood) | [Big Earth Data 2025](https://doi.org/10.1080/20964471.2025.2458714) | CC BY 4.0 (data) |
| **GF-FloodNet** | Gaofen-2/3 | Pre/Post | 13k chips | Segmentation | [Kaggle](https://www.kaggle.com/datasets/pengliuair/gf-floodnet) · [Baidu Pan](https://pan.baidu.com/s/11yx5ERsGkkfUQXPYn34KkQ?pwd=yh47) | [Int. J. Digit. Earth 2023](https://doi.org/10.1080/17538947.2023.2230978) | Not stated |
| **FloodPlanet** | PlanetScope + Sentinel-1 | Pre/Post | 366 patches, 19 events | Segmentation | [CyVerse Data Commons](https://doi.org/10.25739/m69q-8k22) | [J. Remote Sens. 2025](https://doi.org/10.34133/remotesensing.0575) | ODC-PDDL |
| **Landslide4Sense** | Sentinel-2 + DEM | Post | 3.8k images | Segmentation | [Zenodo](https://doi.org/10.5281/zenodo.10463239) · [GitHub](https://github.com/iarai/Landslide4Sense-2022) | [IEEE TGRS 2022](https://doi.org/10.1109/TGRS.2022.3215209) | CC BY 4.0 (data) |
| **GDCLD** | Multi-source | Post | 9 earthquake events | Segmentation | [Zenodo](https://doi.org/10.5281/zenodo.13612636) | [ESSD 2024](https://doi.org/10.5194/essd-16-4817-2024) | CC BY 4.0, scientific research use ⁶ |

⁵ License depends on the image source (e.g., Maxar optical: CC BY-NC 4.0; Capella/Umbra SAR: CC BY 4.0); see the dataset card.
⁶ The Zenodo description restricts use to scientific research; some source imagery is not redistributed.

---

## Part 3 – Social media and auxiliary datasets

| Dataset | Source | Content | Size | Task | Data access | Paper | License (as stated by the provider) |
|---|---|---|---|---|---|---|---|
| **CrisisMMD** | Twitter | Text + images | 18k items, 7 disasters (2017) | Multimodal classification | [CrisisNLP](https://crisisnlp.qcri.org/crisismmd) | [ICWSM 2018](https://doi.org/10.1609/icwsm.v12i1.14983) | [CrisisNLP terms of use](https://crisisnlp.qcri.org/terms-of-use.html) (research only) |
| **CrisisBench** | Twitter | Text | 166k tweets | Classification | [CrisisNLP](https://crisisnlp.qcri.org/crisis_datasets_benchmarks.html) · [GitHub](https://github.com/firojalam/crisis_datasets_benchmarks) | [ICWSM 2021](https://doi.org/10.1609/icwsm.v15i1.18115) | CC BY-NC-SA 4.0 (GitHub README) |
| **RescueADI** | Mixed (images mainly from RescueNet) | VHR images + requests | 4k images | VQA / planning | Not yet released ⁷ | [IEEE TGRS 2025](https://doi.org/10.1109/TGRS.2025.3532594) · [arXiv](https://arxiv.org/abs/2410.13384) | – |
| **TorNet** | Weather radar (WSR-88D) | Polarimetric radar | 10 years | Detection | [GitHub](https://github.com/mit-ll/tornet) · [Zenodo (2013 + catalog)](https://doi.org/10.5281/zenodo.12636522) ⁸ | [AIES 2025](https://doi.org/10.1175/AIES-D-24-0006.1) | CC BY 4.0 (data), MIT (code) |
| **OpenEarthMap** | VHR optical | Land cover | 5k images, 44 countries | Land-cover segmentation | [Zenodo](https://zenodo.org/records/7223446) · [website](https://open-earth-map.org/) | [WACV 2023](https://openaccess.thecvf.com/content/WACV2023/html/Xia_OpenEarthMap_A_Benchmark_Dataset_for_Global_High-Resolution_Land_Cover_Mapping_WACV_2023_paper.html) | CC BY 4.0 (some regions CC BY-NC-SA 4.0) |
| **OpenEarthMap-SAR** | HR SAR + optical | Land cover | 5k images | Land-cover segmentation | [Zenodo](https://zenodo.org/records/14950559) | [IEEE GRSM 2025](https://doi.org/10.1109/MGRS.2025.3599512) | CC BY 4.0 (SAR), CC BY 2.0 (optical and labels) |

⁷ The paper states that the dataset will be made publicly available; no public release was found at the time of writing.
⁸ TorNet is split into one Zenodo record per year (2013–2022, about 150 GB in total); the GitHub README lists all records.

---

## Abbreviations

VHR = very high resolution; SAR = synthetic aperture radar; DEM = digital elevation model; sUAS = small unmanned aircraft system; VQA = visual question answering; Pre/Post = pre- and post-disaster imagery.


