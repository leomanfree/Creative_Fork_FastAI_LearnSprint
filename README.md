# 🧠 Creative Fork — FastAI Learn Sprint

This repo documents my hands-on journey through the FastAI course, remixing the official notebooks with a creative and narrative twist.

**Note:** This project is a personal fork and remix of muellerzr's fastai course notebook.
Huge thanks to Zachary Mueller and the fastai community for the original material and inspiration.

## 📓 Day 1: Pet Breed Classifier 🐶🐱

Built a deep learning image classifier using `fastai` to identify 37 breeds of cats and dogs.  
Trained a ResNet model with transfer learning, visualized results, and tested on a custom image.

### ✅ Achievements
- Loaded and preprocessed Oxford-IIIT Pet dataset
- Trained a ResNet34 with `cnn_learner`
- Fine-tuned learning rate with `lr_find`
- Visualized top losses and confusion matrix
- Tested on custom image: nailed the prediction `shiba_inu` with 91% confidence 🔥

### 🧪 Next Steps
- Add more custom images for inference
- Experiment with data augmentation
- Try another architecture (like EfficientNet)

---

### 🗂️ Files
- `day1_pet_classifier.ipynb`: Notebook from Day 1 (based on `01_Pets.ipynb`)
- `stage_1.pth`: Trained model weights
- `Cane11.jpg`: My test image used for prediction

---

### 📸 Screenshot

![image (5)](https://github.com/user-attachments/assets/4b21c201-bb1a-4f94-88a1-6758b43e25fc)

### Day 2 — Model Rebuild From Memory

On Day 2, I didn’t follow the tutorial.

- I reviewed my own repo and @muellerzr’s notebook  
- Discussed with ChatGPT to identify the Minimum Viable Engine  
- Rewrote everything by hand, then reimplemented in Colab  
- Debugged from memory (notably: `PAT` vs `pat`)  
- Model predicted `basset_hound` at 99.99% confidence
  ![image](https://github.com/user-attachments/assets/5c291f48-7554-4ae0-8f1e-da234d78f9cb)


This notebook reflects that process:  
[`02_Model_Rebuild_From_Memory.ipynb`](./02_Model_Rebuild_From_Memory.ipynb)

---

Follow the repo as I iterate day by day 🌀  
Let’s learn, remix and build with FastAI ⚡
