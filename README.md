## 🚀 ReCoDeWaste: Recycling Construction & Demolition Waste Dataset 
<img width="896" height="355" alt="image" src="https://github.com/user-attachments/assets/8eb6273d-92a0-44f2-b5dd-b988750c4fc3" />
<p align="justify">
ReCoDeWaste is the first open-source <b>RGB-D dataset</b> for <b>construction and demolition waste (CDW)</b> designed to advance both <b>instance segmentation</b> and <b>robotic grasp detection</b> in real-world sorting scenarios in material recovery facilities. Unlike earlier waste datasets (e.g., TACO, ReSORT-IT, CODD) which primarily provide only RGB images, ReCoDeWaste uniquely incorporates <b>depth information</b>. Depth is critical for robotic vision, as it delivers sharper boundary cues, spatial positioning, and reliable handling of clutter and occlusion—factors essential for complementing just color-based feature learning. Additionally, ReCoDeWaste captures the <b>clutter</b>, <b>occlusion</b>, <b>deformation</b>, and <b>variability</b> inherent in CDW streams, making it uniquely suited for training robust, deployable solutions for automated material recovery facilities.
</p>

## ♻️ Recyclable Classes in ReCoDeWaste  

<p align="justify">
Curated from active construction sites in Melbourne, Australia, the dataset contains <b>2,505 high-resolution RGB-D images</b>, featuring 100,000+ manually annotated object instance masks across six key recyclable classes:
</p>

| Class        | Description |
|--------------|-------------|
| **Aggregates** | Concrete, rock, stone, and bricks, which are recycled as construction aggregates. Objects were collected with varying sizes, textures, and significant levels of deformation and contamination (dust, paint). |
| **Cardboard** | Various-sized deformed cardboard packaging, typically recycled for production of paperboard, cellulose fibre, and other applications. |
| **Hard Plastic** | High-density polyethylene (HDPE) materials, including plumbing waste, conduits, adhesive containers, packaging materials, and other solid objects. HDPE is one of the most commonly recycled plastics. |
| **Metal** | Multiple types and sizes of conductive metals such as copper, aluminium, steel, and iron. Samples show visible degradation (corrosion, abrasion). Metals have high resource value and wide recycling applications. |
| **Soft Plastic** | Translucent/opaque low-density polyethylene (LDPE), including plastic bags, wraps, flexible packaging, and films. LDPE is commonly recycled into composite lumber, garbage bags, and more, with one of the highest recyclability rates in CDW. |
| **Timber** | Waste timber and wood pieces of varying colour, size, and shape, with visible degradation (weathering, aging). Recycled timber is used in furnishings, panel boards, biomass, and helps reduce deforestation. |

<p align="justify">
The dataset also comprises of a grasp detection subset, including <b>55,000+ grasp annotations</b>, for enabling the development and benchmarking of AI-driven robotic systems that move beyond recognition to action. Released alongside our <b><a href="https://doi.org/10.1016/j.wasman.2025.115123">paper</a></b> in <i>Waste Management (2025)</i>, this dataset lays the groundwork for benchmarking scalable, intelligent, and sustainable recycling automation in support of the circular economy.
</p>
<img width="819" height="714" alt="image" src="https://github.com/user-attachments/assets/7aec636a-9265-488a-9061-c19aec5a6a77" />

## 📂 Dataset Access  

<p align="justify">
The full <b>ReCoDeWaste dataset</b>, including all RGB-D images, segmentation masks in COCO format, and grasp annotations, is available for download via Google Drive. Researchers and practitioners are encouraged to use the full dataset for training and benchmarking AI-based waste sorting models.
</p>

🔗 **[Download Full Dataset (Google Drive)](https://drive.google.com/drive/folders/1pBxoNtKkntYypRH1MG5GkSPncGJ86nF5?usp=sharing)**  

## 📖 Citation  

<p align="justify">
If you use <b>ReCoDeWaste</b> in your research, please cite the following paper:
</p>  

**[Prasad, V., & Arashpour, M. (2025). Enhancing sorting efficiency in cluttered construction and demolition waste streams via boundary-guided grasp detection. *Waste Management, 207*, 115123.](https://doi.org/10.1016/j.wasman.2025.115123)**  

### BibTeX  

```bibtex
@article{prasad2025recodewaste,
  title     = {Enhancing sorting efficiency in cluttered construction and demolition waste streams via boundary-guided grasp detection},
  author    = {Prasad, Vineet and Arashpour, Mehrdad},
  journal   = {Waste Management},
  volume    = {207},
  pages     = {115123},
  year      = {2025},
  publisher = {Elsevier},
  doi       = {10.1016/j.wasman.2025.115123}
}
```

## 🙏 Acknowledgement & Funding
<p align="justify"> This research is supported by the <b><a href="https://www.monash.edu/it/our-research/research-labs-and-groups/ascii">Automation and Sustainability in Construction and Intelligent Infrastructure (ASCII) Lab</a></b> at Monash University, Melbourne, Australia. The authors gratefully acknowledge the lab’s resources, technical support, and collaborative environment that enabled the development of the ReCoDeWaste dataset and associated research. </p>
