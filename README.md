

#  Fetal Heart Ultrasound Image Enhancement and Anatomical Feature Recognition

This project focuses on **enhancing fetal heart ultrasound images** and performing **anatomical feature recognition** using advanced AI techniques. It integrates **Pix2Pix GAN**, **Grad-CAM**, and **clustering methods** (K-Means & Hierarchical) to improve diagnostic accuracy in fetal echocardiography.

---

##  Features

* **Image Preprocessing Pipeline**

  * Resizing, normalization, sharpening, and contrast adjustment
* **Generative Adversarial Networks (Pix2Pix GAN)**

  * Supervised image enhancement with 98.9% segmentation accuracy
* **Unsupervised Learning**

  * PCA + K-Means clustering for anatomical pattern extraction
* **Explainable AI**

  * Grad-CAM applied for visual interpretability of model predictions
* **Evaluation Metrics**

  * Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Index

---

##  Dataset

* Source: Fetal heart ultrasound dataset 
* Classes: **LVOT**, **RVOT**, **3VT**, **4C**
* Total Images: **257**
* Preprocessing includes: resizing (256×256), normalization, sharpening, and contrast stretching.

---

##  Tech Stack

* **Languages & Libraries:** Python, TensorFlow, Keras, PyTorch, Scikit-learn, OpenCV, PIL
* **Visualization:** Matplotlib, Seaborn
* **Clustering:** K-Means, Hierarchical (Agglomerative Clustering)
* **Explainability:** Grad-CAM

---

##  Results

* GAN-based enhancement achieved **98.9% segmentation accuracy**.
* PCA + K-Means improved anatomical pattern recognition.
* Grad-CAM highlighted critical regions, improving clinical interpretability.

---




##  Publications

* **IEEE (2024):** *Fetal Heart Ultrasound Image Enhancement and Anatomical Feature Recognition via GAN and Grad-CAM*


