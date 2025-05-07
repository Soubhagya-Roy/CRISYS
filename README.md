
# CRISYS - Criminal Recognition and Identification System

**CRISYS** is an AI-powered system designed to assist law enforcement agencies by generating accurate suspect facial sketches based on detailed textual descriptions. It bridges the gap between verbal descriptions and visual identification using advanced natural language processing (NLP) and generative adversarial networks (GANs), specifically leveraging the **Stable Diffusion** model.

---

## Project Objective

To develop an intelligent and ethical system that:
- Translates descriptive witness or investigator input into realistic facial sketches.
- Enhances the accuracy and speed of criminal identification.
- Reduces reliance on manual forensic sketching methods.
- Prioritizes privacy, fairness, and ethical usage.

---

## Features

- **Text-to-Sketch Generation** using NLP and Stable Diffusion.
- **Prompt Condensation** for efficient, structured AI inputs.
- **RGB to Pencil Sketch Conversion** via OpenCV.<br>
  <img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*N5UEm-OMwqBoIZntUpW5XQ.png" width="99">&nbsp;<img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*6flxiUn7NvNZARo87WCLbQ.png" width="100"/><br>

- **Ethical AI Protocols** including bias mitigation and privacy protection.

---

## Technologies Used

- **Stable Diffusion v1.4** via Hugging Face Diffusers<br>
<img src="https://raw.githubusercontent.com/CompVis/stable-diffusion/main/assets/stable-samples/txt2img/merged-0005.png" width="500"><br>
- **Natural Language Processing** for parsing user descriptions
- **OpenCV** for image processing & sketch conversion
- **FFHQ Dataset** for model training and evaluation<br>
<img src="https://raw.githubusercontent.com/NVlabs/ffhq-dataset/master/ffhq-teaser.png" width="200"><br>
- **Python** for backend implementation
- **FID & Inception Score** for performance metrics

---

## System Architecture

1. **Input Interface**: Law enforcement officers input structured verbal descriptions.
2. **Prompt Processing**: NLP condenses text into specific attributes (e.g., “Oval face, Monolid eyes”).
3. **Image Generation**: Stable Diffusion generates a detailed RGB image.
4. **Sketch Transformation**: RGB images are converted into pencil sketches using OpenCV.
5. **Optional Match Module**: Cross-references sketches with existing criminal databases.

---

## Model Training

- **Dataset**: FFHQ dataset via Kaggle.
- **Training Pipeline**:
  - Preprocessing and augmentation of images.
  - Fine-tuning Stable Diffusion using transfer learning.
  - Evaluation using both qualitative (visual inspection) and quantitative methods.

---

## Performance & Testing

- Functional, Accuracy, Usability, and Performance testing done.
- System shows high fidelity in sketch accuracy and robustness across inputs.
- Modular design enables scalability and future improvements.

---

## Ethical Considerations

- **Bias Reduction**: Diverse datasets and prompt control.
- **Privacy Protection**: Secure storage and access control.
- **Responsible Use**: Ethical guidelines for deployment in sensitive investigations.

---

## Future Scope

- Real-time CCTV feed integration.
- AR/VR overlay support for field identification.
- Advanced suspect profiling (age progression, emotion adaptation).
- Voice-command input system.
- Cloud integration for multi-jurisdictional access.

---

## Note :-

This project is developed for **academic and research purposes** to demonstrate the potential application of AI in law enforcement. Any implementation in real-world scenarios would require thorough testing, ethical review, and compliance with relevant legal frameworks.. For any external or commercial use, please contact the authors for permissions.


