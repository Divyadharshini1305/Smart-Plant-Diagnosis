# Smart Plant Diagnosis 🌱

An AI-powered application that helps farmers identify plant diseases and receive crop-specific recommendations for sustainable agriculture.

## Overview

Smart Plant Diagnosis is a Flask-based web application that uses Machine Learning to detect diseases in agricultural crops from leaf images. The system provides instant disease identification and offers recommendations to help farmers take appropriate action.

The project focuses on improving agricultural productivity through early disease detection and informed decision-making.

## Features

* Plant disease detection using Machine Learning models
* Support for multiple crops

  * Paddy
  * Maize
  * Sugarcane
* Crop-specific recommendation system
* User-friendly web interface
* Disease prediction from uploaded leaf images
* Sustainable agriculture guidance

## Project Structure

```text
Smart-Plant-Diagnosis/
│
├── app.py
├── predict.py
├── maizerecom.py
├── paddyrecom.py
├── sugarcanerecom.py
│
├── models/
│   ├── MAIZE.h5
│   ├── PADDY.h5
│   └── SUGARCANE.h5
│
├── data/
│   ├── maize_recommendation.json
│   ├── paddy_recommendation.json
│   └── sugarcane_recommendation.json
│
├── static/
│   ├── login.css
│   ├── login.js
│   ├── script.js
│   ├── signup.css
│   ├── style.css
│   └── image assets
│
├── templates/
│   ├── index.html
│   ├── upload.html
│   ├── detect.html
│   ├── result.html
│   ├── login.html
│   ├── signup.html
│   ├── rotation.html
│   └── agri_shop.html
│
└── README.md
```

> **Note:** The trained machine learning model files (`.h5`) are not included in this repository due to GitHub file size limitations. To run the project successfully, place the trained model files (`MAIZE.h5`, `PADDY.h5`, and `SUGARCANE.h5`) inside the `models/` directory.


## Technologies Used

* Python
* Flask
* HTML
* CSS
* JavaScript
* TensorFlow / Keras
* Machine Learning
* JSON

## Supported Crops

### Paddy

Detects diseases affecting paddy crops and provides suitable recommendations.

### Maize

Identifies maize leaf diseases and suggests corrective measures.

### Sugarcane

Recognizes sugarcane diseases and provides treatment recommendations.

## Installation

### Clone Repository

```bash
git clone https://github.com/Divyadharshini1305/Smart-Plant-Diagnosis.git
cd Smart-Plant-Diagnosis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open the application in your browser:

```text
http://127.0.0.1:5000
```

## Future Enhancements

* Mobile application integration
* Multi-language support
* Real-time field monitoring
* Advanced recommendation engine
* Cloud deployment
* Expanded crop support

## Authors

Divyadharshini D

BE Computer Science and Engineering (Cyber Security)

Sri Sairam Institute of Technology

## License

This project is developed for educational and research purposes.
