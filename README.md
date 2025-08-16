# Kidney-Sliced-512
512×512 sliced image tiles and COCO-format annotations derived from high-resolution kidney microscopy images, created by mihajlov39547 for academic use in instance segmentation of renal blood vessels and glomeruli.

## 📚 Dataset Overview

This dataset consists of approximately **7000 image tiles** extracted from Whole Slide Images (WSIs) of healthy human kidney tissue. It focuses on segmenting microvascular structures such as **capillaries**, **arterioles**, **venules**, and **glomeruli**.

- **Author**: Marko Mihajlovic  
- **Affiliation**: Singidunum University, Belgrade, Serbia  
- **GitHub**: [https://github.com/mihajlov39547/KIDNEY-Sliced-512](https://github.com/mihajlov39547/KIDNEY-Sliced-512)

- **Original imagery source**:  
  PAS-stained histology slides from the Human BioMolecular Atlas Program (HuBMAP).  
  WSIs were sliced into 512×512 patches and annotated for instance segmentation tasks.

  ## 🗂️ Repository Contents
```
iSAID-512Tiles/
├── train/
├── valid/
├── test/
├── LICENSE
└── README.md
```

- `train/valid/test` contains 512×512 `.jpg` image tiles and _annotations.coco.json annotations
- File naming format: `00bc0c5940e1_png.rf.9b113730a530e9b8e8559468297dec2a.jpg`

---

## 🏷️ Object Categories

This dataset includes the following instance segmentation classes:

```
1: blood_vessel
2: glomerulus
```

## 🧪 Research Context

This dataset supports research into the spatial organization of microvasculature in human kidneys. It contributes to the **Vascular Common Coordinate Framework (VCCF)** and the **Human Reference Atlas (HRA)** by enabling automated segmentation of blood vessels and glomeruli.

Understanding microvascular arrangements helps researchers map cellular relationships and improve insights into tissue function and health.

---

## 📜 License

**Creative Commons Attribution‑NonCommercial 4.0 International (CC BY‑NC 4.0)**

- ✅ Academic/research use: Allowed with attribution  
- ❌ Commercial use: Prohibited

See the full license in the `LICENSE` file.

---

## 📖 Citation

If you use this dataset, please cite:

```bibtex
@misc{mihajlovic2025kidneysliced512,
  title={KIDNEY-Sliced-512: A Sliced Histology Image Dataset for Instance Segmentation of Renal Microvasculature},
  author={Marko Mihajlovic},
  year={2025},
  howpublished={\url{https://github.com/mihajlov39547/KIDNEY-Sliced-512}},
  note={Singidunum University, Belgrade, Serbia}
}
