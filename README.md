# 🌾 CROPSENSE  
#### An AI-powered web platform that recommends the best crop to grow, fertilizers to use, and detects diseases in crops using ML and DL.

🔗 [Live Demo](https://crop-recommendation-zweq.onrender.com/)  
📦 [Deploy-ready Branch](https://github.com/SmitThakare/CROPSENSE/tree/deploy)

---

## 💪 Motivation

Agriculture remains a cornerstone of economic growth, especially in countries like India where a large portion of the population depends on farming. To modernize and optimize agricultural practices, this project integrates **Machine Learning (ML)** and **Deep Learning (DL)** into a user-friendly web application that empowers farmers to make data-driven decisions.

CROPSENSE offers three core tools:
- **Crop Recommendation**: Suggests the most suitable crop based on soil nutrients and local weather.
- **Fertilizer Guidance**: Identifies nutrient deficiencies or excesses and recommends corrective fertilizers.
- **Disease Detection**: Uses image classification to identify crop diseases and suggest treatments.

By integrating these applications, CROPSENSE supports farmers in making informed decisions, improving yield, and contributing to sustainable agricultural growth.

---

## 🌐 Key Features

- 🔍 Real-time Weather Integration via OpenWeatherMap API  
- 📸 CNN-based Disease Detection with PyTorch and OpenCV  
- 📊 Soil Analysis using N-P-K ratios and pH levels  
- 🧠 ML Models trained on curated agricultural datasets  
- 🧪 Fertilizer Diagnosis Engine using rule-based logic and nutrient thresholds  
- ⚡ Fast, Responsive UI built with Bootstrap and Flask  
- 🛠️ Modular Architecture for easy scaling and deployment

---

## 🛠️ Built With

<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/main/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/main/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/main/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg"></code>
<code><img height="30" src="https://pytorch.org/assets/images/pytorch-logo.png"></code>

---

## 💻 How to Use

### 🌱 Crop Recommendation
- Input soil nutrient values (N-P-K), pH level, rainfall, state, and city.
- The model predicts the most suitable crop for cultivation.
- Weather data is fetched using [OpenWeatherMap API](https://openweathermap.org/).
- For N-P-K ratios, refer to [this guide](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm).

### 🧪 Fertilizer Suggestion
- Enter soil nutrient values and the crop you intend to grow.
- The system analyzes nutrient balance and recommends fertilizers to correct deficiencies or excesses.

### 🩺 Disease Detection
- Upload a leaf image of your crop.
- The model identifies the crop and detects whether it’s healthy or diseased.
- If diseased, it provides the name, cause, and treatment suggestions.

<details>
  <summary>Supported Crops for Disease Detection</summary>

- Apple  
- Blueberry  
- Cherry  
- Corn  
- Grape  
- Pepper  
- Orange  
- Peach  
- Potato  
- Soybean  
- Strawberry  
- Tomato  
- Squash  
- Raspberry  

</details>

---

## 🧑‍💻 How to Run Locally

### 🔧 Prerequisites
- [Git](https://git-scm.com/download)
- [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

### 📦 Setup Instructions

```bash
# Clone the deploy-ready branch
git clone -b deploy https://github.com/SmitThakare/CROPSENSE.git
cd CROPSENSE

# Create and activate environment
conda create -n cropsense python=3.6.12
conda activate cropsense

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
