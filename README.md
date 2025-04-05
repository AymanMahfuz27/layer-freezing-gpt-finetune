# Layer Freezing in Fine-Tuning GPT-2 Small

This notebook explores how freezing different numbers of lower layers during fine-tuning affects model performance on a classification task.

The experiment investigates whether partially freezing a pretrained transformer model can improve accuracy by preserving useful lower-level representations while still adapting higher layers to the new task.

You can find a full write-up discussing the motivation, results, limitations, and future directions for this experiment on my blog here: [[Blog Post Link](https://aymanmahfuz27.github.io/principles-first-blog/)].

---

**Note**:  
This was my first independent deep learning experiment, conducted with minimal compute resources (Google Colab).
