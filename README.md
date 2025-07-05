# 🌸 Iris Flower Classifier

A simple yet elegant machine learning project using Logistic Regression to classify Iris flowers based on petal features.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg" width="300" />
</p>

---

## 🌼 Overview

This project uses the **famous Iris flower dataset** to classify flowers into:

* **Setosa**
* **Versicolor**
* **Virginica**

We use only **2 features** — *Petal Length* and *Petal Width* — to make the model:

* Easy to understand
* Easy to visualize
* Interactive via a Gradio UI 🌐

---

## 🎯 Objective

* 🔹 Train a **Logistic Regression** model
* 🔹 Predict the species of iris flower
* 🔹 Visualize the **decision boundary**
* 🔹 Build a smooth and beautiful **Gradio web interface**

---

## 🧪 Tech Stack

| Tool                 | Purpose                        |
| -------------------- | ------------------------------ |
| Python               | Main language                  |
| Scikit-learn         | ML model (Logistic Regression) |
| Matplotlib / Seaborn | Visualization                  |
| Gradio               | Interactive web UI             |
| Git                  | Version control                |
| GitHub               | Project hosting                |

---

## 🧠 Features

👉 Clean and minimal code
👉 Interactive sliders for petal measurements
👉 Real-time prediction with flower image
👉 Decision boundary plot to visualize how model separates species
👉 Great for learning ML fundamentals

---

## 🚀 Getting Started

### 1⃣ Clone the Repository

```bash
git clone https://github.com/mohitrathee051/Iris_Flower_Data.git
cd Iris_Flower_Data
```

### 2⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

> Example `requirements.txt`:

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
gradio
```

### 3⃣ Launch the Gradio App

```bash
python app.py
```

Then open: [http://localhost:7860](http://localhost:7860)

---

## 🌸 Gradio App Preview

<p align="center">
  <img src="https://user-images.githubusercontent.com/12284569/191813729-e8e6ee70-62c4-48a6-9a92-fb5ea3b14d9e.gif" width="600"/>
</p>

> Move the sliders → Predict the flower → Get an image + species label

---

## 📊 Sample Output

<p align="center">
  <img src="assets/decision_boundary.png" width="500"/>
  <br><i>Logistic Regression Decision Boundary (Petal Length vs Width)</i>
</p>

---

## 🔮 Future Ideas

* Train model on all 4 features (including Sepal length/width)
* Try other classifiers like SVM, KNN, Decision Tree, Random Forest
* Show model confidence score in Gradio
* Display flower description from Wikipedia using API

---

## 🤝 Contributing

Pull requests are welcome!
Found a bug? Have an idea? Open an issue or PR and let's build together.

---

## 📄 License

This project is licensed under the **MIT License**.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/mohitrathee051">Mohit</a>
</p>
