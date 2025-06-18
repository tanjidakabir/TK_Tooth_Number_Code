# Necessary Packages
- TensorFlow version: 2.4.0,
- OpenCV version: 4.5.3,
- Python version: 3.8.5,
- NumPy version: 1.19.4,
- Pandas version: 0.25.3,
- SciPy version: 1.4.1
# How to run the Code
1. To get bone area, tooth and CEJ line masks  <b> load_models_save masks.ipynb</b>
- Bone Area Model: model_for_bone_area_resnet_34.h5
- Tooth Model: model_for_tooth_resnet_34_512.h5
- CEJ Line Model: model_for_cej.h5
2. To extract individual tooth from self paniramic images <b> extract_individual_tooth_from_pano.ipynb</b>
3. To get bone area, tooth and CEJ line mask <b>bone_area_tooth_cej_masks_from_peri.ipynb</b>
4. To extract individual tooth from periapical images <b>extract_individual_tooth_from_peri.ipynb</b>
5. To match with repository or patient's self panoramic <b>repository template_match.ipynb</b>
