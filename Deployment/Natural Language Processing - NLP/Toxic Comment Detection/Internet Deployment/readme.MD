
# Toxic Comment Detection

The Natural Language Processing (NLP) application was made to filter out negative (toxic) words on social media so users will feel safer and more comfortable surfing the internet.


## Mandatory Condition

I exemplify the Deployment using RDP (Virtual Machine Azure). Make sure you have RDP too, it's not mandatory from Azure but you can also create RDP on AWS, Digital Ocean, Vultr etc

## Features

- Toxic Comment Filtering with Label



## Installation

Install Requirements 

```pip python
  pip install Flask==2.1.0
  pip install Werkzeug==2.1.2
  pip install joblib==1.0.0
  pip install pandas==1.4.2
  pip install numpy==1.21.6
  pip install scikit-learn==0.24.1
  pip install nltk==3.7
  pip install Sastrawi==1.0.1
```
    
## Config Internet Access & Run

Clone the project

```bash
  git clone https://github.com/faishal-lib/Toxic-Comment-Detection-NLP
```

Go to the project directory

```bash
  cd app
```

Reconfig app.py (BEFORE)

```bash
  	# Run Flask di Internet
	app.run(host="localhost", port=5000, debug=True)
```

Reconfig app.py (AFTER)

```bash
  	# Run Flask di Internet
	app.run(host="0.0.0.0", port=80, debug=True)
```

Save app.py config

Start the server

```bash
  python app.py
```


## Activated Server

![image](https://user-images.githubusercontent.com/25089714/206856955-cc6c9f02-e939-4d40-909a-ea46272a217f.png)


## Application Interface
![image](https://user-images.githubusercontent.com/25089714/206856960-7b8f8e4f-cf3e-444e-9013-b7798c146e50.png)

![image](https://user-images.githubusercontent.com/25089714/206856972-226b3d9d-fa3c-4faa-9d4f-9f3de4b9e4b5.png)


## Thanks

Orbit Future Academy & Coach - Visioner 5

