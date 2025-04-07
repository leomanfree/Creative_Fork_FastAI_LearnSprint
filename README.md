# 🧠 Creative Fork – Learn Sprint (Fast.ai v22)

This repo documents a 3-day Learn Sprint focused on the Fast.ai 2022 course.

The goal was not just to train a model — but to understand the *minimum viable engine* behind it,  
and to reflect on the philosophical structures that underpin machine learning.

---

## 🏁 Project Summary

Over 72 hours, I:

- Built a pet image classifier using Fast.ai
- Fine-tuned the model with transfer learning
- Rebuilt the architecture from scratch in Colab
- Logged all progress and structured the sprint around the Build → Distill → Share loop
- Integrated reflections on classical logic, dialectical thinking, and hybrid human-AI cognition

---

## 🧭 [Learn Log] (https://deserted-ladybug-896.notion.site/Learn-Log-1c7e55b865378010982dff575412b8f2?pvs=4)

---

## 📁 Notebooks

- [Day 1 – Build](Creative_Fork_FastAI_LearnSprint.ipynb)
- [Day 2 – Distill](02_Model_Rebuild_From_Memory.ipynb)
- [Day 3 – Refine & Reflect](03_Model_Rebuild_From_Memory.ipynb)

---

## 🔍 Key Concepts

- Minimum Viable Engine: `DataBlock → Learner → Train → Predict`
- Transfer Learning & `learn.unfreeze()`
- Layer structures and abstraction
- Evaluation via prediction (`learn.predict(img)`)

---

## 🧠 Philosophy Blocks

This Learn Sprint also explores foundational ideas behind modern AI:

---

### 1. Aristotelian Structure

> "Each layer performs a logical abstraction — from perception to reason."

Layers as **classes of form** (Aristotle, *Posterior Analytics*)  
ML as a continuation of syllogistic reasoning in computational form.

📚 Ref: Lukasiewicz, *Aristotle's Syllogistic from the Standpoint of Modern Formal Logic*

---

### 2. Hegelian Dialectic & Logical Form

> "Knowledge arises not from repetition, but from contradiction."

Inspired by Hegel’s *Science of Logic*:

- The logic of becoming  
- Contradiction as the motor of development  
- Abstraction through negation  
- Categories as dynamic, not static

Just like in backpropagation:  
→ The model learns by negating error, not just reinforcing signal.

📚 Ref: Hegel, *Science of Logic* (1812–16)

---

### 3. Beyond Statistics: Hybrid Intelligence

> "LLMs are brilliant sophists. They optimize for likelihood, not meaning."

Reflections on von Franz, Jung, and the limits of probabilistic inference.  
The future isn’t artificial minds — it’s **engineered human-AI cognition.**

From co-pilots to **cognitive stacks**.  
From fine-tuning weights to fine-tuning minds.

📚 Ref: von Franz, *On Divination and Synchronicity*  
📄 Ref: *Self-Reflecting LLMs: A Hegelian Dialectical Approach* (arXiv:2501.14917)

---

## 🚀 Closing Thoughts

This sprint was a testbed.  
The repo is live, the model runs, but the real experiment is:

> How far can we stretch the meaning of “learning” — with and beyond AI?

DM me if you're exploring the same questions.

🔮 Alchemical Symbols Classifier – Bonus Remix

As part of the FastAI Learnathon @ Network School, I challenged myself to ship a bonus model — weird, symbolic, and fast.

**A classifier of alchemical glyphs.**  
Trained on a small handcrafted dataset representing key archetypal elements and classical substances.

📂 Dataset  
Originally, I tried to render Unicode alchemical symbols using Python + PIL — but the Unicode-to-font rendering was **pretty buggy** (some glyphs wouldn’t display or save properly).

So I pivoted:  
→ I manually built a tiny dataset with simple clean images representing:

- 🌬 Air  
- 🔥 Fire  
- 💧 Water  
- 🌍 Earth  
- 🜚 Gold  
- 🜛 Silver  
- 🜔 Salt  
- 🜍 Sulfur  
- ☿ Mercury

🧠 Goal  
Test the FastAI pipeline on abstract/symbolic concepts.  
Play with minimal data. Ship something weird. Earn 🍕.

🛠️ Tech Stack

- Custom image dataset (hand-curated)
- Fast.ai `DataBlock` and `cnn_learner`
- Trained with ResNet-18 and `learn.fine_tune(4)`
- Ran predictions on single-symbol test images

📈 Results  
Even with very limited data, model reached solid accuracy due to class clarity.  
The real win: remixing the pipeline, debugging hard font issues, and shipping.

📁 Notebook  
See: `day3_alchemy_classifier.ipynb`

---

🙏 Thanks to the Learnathon for the permission to explore.

🧘‍♂️ *“Your notebook is your temple. Your output is your offering.”*

#fastai #learnathon #symbolicML #alchemy #creativefork
