# 🌿 Plant Classification Project: Analysis & Evaluation

## 1. Impact of Dataset Size
> **Question:** How did the number of images per class affect your model’s accuracy?

Having **250 images per class** provided a solid foundation, but it was likely the "tipping point" for the model's performance. 
* **Generalization:** With a relatively small dataset, the model struggled to generalize to every possible angle or lighting condition. 
* **Balance:** Because the image count was identical for all 20 species, the model remained balanced (it didn't favor one plant over another), but overall accuracy was limited by the lack of diverse examples.

---

## 2. Common Misclassifications
> **Question:** Which plant species were most commonly misclassified and why?

The most frequent errors occurred between **Holy Basil** and **Sweet Basil** due to extremely high **visual similarity**. 
* **The "Why":** Both plants have similar green, ovate leaves and growth patterns. 
* **The Detail:** Subtle differences—like the toothier edges and hairy stems of Holy Basil versus the smoother, glossier leaves of Sweet Basil—are hard for a model to distinguish without higher resolution or a significantly larger dataset.

---

## 3. Hyperparameter Training Results
> **Question:** How did changing the epochs, batch size, or learning rate affect the training results?

| Parameter | Value | Impact on Training |
| :--- | :--- | :--- |
| **Epochs** | 23 | Found the "sweet spot"; 50 epochs caused **overfitting**. |
| **Batch Size** | 16 | Kept the model updates frequent and stable on current hardware. |
| **Learning Rate** | 0.0001 | Allowed for careful convergence without "overshooting." |

---

## 4. Challenges in Collection & Labeling
> **Question:** What challenges did you encounter during dataset collection and labeling?

The primary challenge was the **manual nature** of the process:
1. **Time Consumption:** Manually downloading 5,000 images (20 species $\times$ 250 images) was incredibly labor-intensive.
2. **Precision:** Ensuring every image was correctly labeled required intense focus, as many species look nearly identical to the human eye, increasing the risk of human error.

---

## 5. Future Improvements & Constraints
> **Question:** If you were to improve your model, what specific changes would you make and why?

To improve the model while respecting **hardware limitations**, I would focus on:
* **Data Augmentation:** Digitally flipping or rotating existing images to "trick" the model into seeing more variety without increasing storage load.
* **Efficient Architectures:** Using pre-trained models (Transfer Learning) to get better results without needing more computational power.

---
