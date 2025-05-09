# AI-Powered Web Application for Galaxy Morphology Classification on Red Hat OpenShift

This repository accompanies my bachelor thesis and serves as the **landing page** for the project.  

## Introduction

This thesis presents an AI-powered web application for galaxy morphology classification, which utilizes machine learning and a vision transformer-based architecture. PyTorch is used for training the model and processing images from the Galaxy Zoo 2 dataset, while data augmentation enhances the model's ability to extract robust features. The final CosmoFormer model achieves competitive accuracy in galaxy image classification tasks. The responsive web application seamlessly integrates the backend API and the frontend user interface. Deployment on Red Hat OpenShift provides scalability and reliable orchestration for the system. This work demonstrates how machine learning and cloud-native technologies can be combined to automate galaxy morphology analysis for modern astronomical surveys.

----

**Thesis title**: AI-Powered Web Application for Galaxy Morphology Classification on Red Hat OpenShift  
**Acad. year**: 2024/2025  
**Department**: Department of Intelligent Systems  
**Type of thesis**: Bachelor's Thesis  
**Language of thesis**: en  
**Thesis focus**: Artificial Intelligence  
**Supervisor**: Mgr. Kamil Malinka, Ph.D.  
**Reviewer**: Ing. Milan Šalko  
**Consultant**: Forde Kieran, Ph.D.  

**Electronic source citation (english):**

    SULTANOV, Artur. AI-Powered Web Application for Galaxy Morphology Classification on Red Hat OpenShift. Online, bachelor's Thesis. Kamil MALINKA (supervisor). Brno: Brno University of Technology, Faculty of Information Technology, 2025. Available at: https://www.vut.cz/en/students/final-thesis/detail/164309. [accessed 2025-04-15].

---

## Core Components

| Component | Repository / Resource |
|-----------|-----------------------|
| **Dataset preparation** | <https://github.com/ArturSultanov/cosmoformer-dataset> |
| **Dataset preparation (no images)** | <https://github.com/ArturSultanov/cosmoformer-dataset-no-images> |
| **Model training & artefacts** | <https://github.com/ArturSultanov/cosmoformer-model> |
| **Trained model on Hugging Face** | <https://huggingface.co/artursultanov/cosmoformer-model> |
| **Web application (backend + frontend)** | <https://github.com/ArturSultanov/cosmoformer-application> |
| **LaTeX code** | <a href="latex-source/">latex-source</a> folder |

Each repo is self‑contained with a `README.md` explaining how to reproduce the relevant stage.

#Links:
1. Galaxy classification application: https://github.com/ArturSultanov/cosmoformer-application
2. CosmoFormer model pipeline: https://github.com/ArturSultanov/cosmoformer-model
3. CosmoFormer model Hugging Face card: https://huggingface.co/artursultanov/cosmoformer-model
4. CosmoFormer dataset: https://github.com/ArturSultanov/cosmoformer-dataset
5. CosmoFormer dataset (no pre-downloaded images): https://github.com/ArturSultanov/cosmoformer-dataset-no-images
