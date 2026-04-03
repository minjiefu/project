## Selected Projects in DS, ML, AWS and NLP

---

### Real-time Financial Surveillance & Anomaly Detection

Constructed an event-driven data pipeline using AWS Lambda and Kinesis to ingest and stream stock market data from S3. Engineered complex streaming analytics with PyFlink and Flink SQL to compute financial KPIs and detect anomalies via MATCH_RECOGNIZE pattern matching. Deployed a managed Flink application to persist processed insights into S3, enabling automated real-time monitoring and risk alerting.

[![](https://img.shields.io/badge/AWS-white?logo=AWS)](#) [![](https://img.shields.io/badge/PyFlink-white?logo=PyFlink)](#) 

<img src="images/LiveStock.png?raw=true" />

---

### SkyInsight - Cloud Data Engineering ETL Pipeline

Engineered a scalable ETL pipeline using AWS Glue and PySpark to process 470k+ airline records, implementing custom time-zone transformations and data deduplication. Architected optimized SQL queries in AWS Athena to perform complex multi-hop flight analysis and time-bucketed delay investigations across the entire dataset. Developed interactive Tableau visualizations and geospatial maps to uncover flight frequency patterns and correlation insights between departure and arrival delays.

[![](https://img.shields.io/badge/AWS-white?logo=AWS)](#) [![](https://img.shields.io/badge/Tableau-white?logo=Tableau)](#) 

<img src="images/SkyInsight.png?raw=true" />

---


### Automated End-to-End YouTube Data Engineering Pipeline

Developed a production-ready ELT pipeline using Python and Apache Airflow to automate the extraction of video metrics from the YouTube Data API into a PostgreSQL data warehouse. Integrated Soda for automated data quality audits and built a multi-layer testing suite with Pytest (Unit, Integration, and E2E), ensuring 100% data integrity and pipeline reliability. Orchestrated the environment with Docker Compose and implemented a GitHub Actions CI/CD workflow to automate image builds and deployment to Docker Hub, achieving seamless environment consistency.

[![](https://img.shields.io/badge/AWS-white?logo=AWS)](#) [![](https://img.shields.io/badge/Tableau-white?logo=Tableau)](#) 
[View code on Github](https://github.com/minjiefu/Youtube_ETL.git) 

<img src="images/youtubeETL.png?raw=true" />

---


### Steel Defects Detection - Computer Vision & Industrial Defect Detection

Developed a dual-stage computer vision framework using TensorFlow to automate surface defect detection and categorization on industrial steel sheets. Engineered a sequential pipeline integrating DenseNet/VGG-16 for initial defect classification followed by U-Net for precise pixel-level segmentation. Optimized model performance through batch normalization and data augmentation, achieving a 98% detection accuracy and a competitive 0.85 Dice coefficient on Kaggle.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Tensorflow-white?logo=Tensorflow)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/scikit--learn-white?logo=scikit--learn)](#)


[View code on Github](https://github.com/minjiefu/Steel-Defects-Detection) 

---
### AI-Driven Credit Default Prediction & Strategic Intervention Optimization

Engineered high-signal financial features and developed a predictive pipeline by using Logistic Regression as a baseline and XGBoost/Random Forests to capture complex non-linear risks, resulting in significantly higher prediction accuracy across 30,000 credit accounts. Quantified business value by modeling the trade-off between counseling costs (NT$7,500) and intervention success (70%), identifying the optimal probability threshold to maximize net financial savings. Delivered a ranked risk priority list for targeted counseling and established a Control Group framework to validate program ROI and ensure long-term model reliability.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 


[View code on Github](https://github.com/minjiefu/AI-Driven-Credit-Default-Prediction-Strategic-Intervention-Optimization.git) 

---


### Academic ConnectX - Polyglot Persistence & Graph-Based Pathfinding

Developed an end-to-end academic networking app to identify optimal collaboration paths between 1M+ scholars by integrating a polyglot persistence architecture (Neo4j, MongoDB, and MySQL). Architected a multi-modal data pipeline to synchronize these heterogeneous data sources, leveraging graph algorithms for real-time pathfinding and complex relationship mapping. Integrated Python Dash and Cytoscape.js to transform raw data into actionable networking insights, significantly enhancing scholar discoverability and connectivity.

[![](https://img.shields.io/badge/Plotly-white?logo=Plotly)](#) [![](https://img.shields.io/badge/MySQL-white?logo=MySQL)](#) [![](https://img.shields.io/badge/MongoDB-white?logo=MongoDB)](#) [![](https://img.shields.io/badge/Neo4j-white?logo=Neo4j)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#) [![](https://img.shields.io/badge/Bootstrap-white?logo=Bootstrap)](#) [![](https://img.shields.io/badge/Cytoscape-white?logo=Cytoscape)](#) 

[View code on Github](https://github.com/minjiefu/Academic-ConnectX) 
<img src="images/academic_connectX.png?raw=true" />

---



### LexiRoute Bot - Serverless Graph Routing Service Powered by AWS

Engineered an end-to-end chatbot using AWS Lex V2 to process natural language queries for city-to-city distance calculations. Implemented core backend logic in Python (AWS Lambda) using BFS algorithms to compute shortest paths and managed persistent storage with DynamoDB. Deployed a responsive web interface on Amazon S3 secured by AWS Cognito, enabling scalable, serverless access for external users.

[![](https://img.shields.io/badge/AWS-white?logo=AWS)](#) [![](https://img.shields.io/badge/Python-white?logo=Python)](#) 
 [![](https://img.shields.io/badge/HTML-white?logo=Html)](#) 

[View code on Github](https://github.com/minjiefu/LexiRoute) 

<img src="images/lexiroute.png?raw=true" />

---

### Cloud Event Board - Two-Tier Microservice Architecture for ML Inference on AWS EKS

This project implements a scalable, cloud-native machine learning inference system using a two-tier microservice architecture deployed on Amazon EKS. It features a high-performance Envoy Proxy as the entry point to route traffic between "Free" and "Premium" service tiers, where Flask applications dynamically orchestrate Kubernetes Jobs to execute ML inference tasks using FFN and CNN models. The system demonstrates advanced infrastructure management by leveraging Kubernetes Namespaces and Resource Quotas to ensure strict service isolation and multi-tenant resource control in a simulated SaaS environment.

[![](https://img.shields.io/badge/AWS-white?logo=AWS)](#) [![](https://img.shields.io/badge/Flask-white?logo=Flask)](#) [![](https://img.shields.io/badge/React-white?logo=React)](#) [![](https://img.shields.io/badge/Python-white?logo=Python)](#) 


[View code on Github Part1 Frontend](https://github.com/minjiefu/aws-Full-Stack-Event-Board-frontendrepo) <br>
[View code on Github Part2 Backend](https://github.com/minjiefu/aws-Full-Stack-Event-Board-backendrepo) 

<img src="images/CloudEventBoard.png?raw=true" />


---

### AWS MLOps Pipeline for Drift Detection and Model Evaluation

Orchestrates an end-to-end MLOps workflow using AWS Step Functions and SageMaker to automate model retraining triggered by real-time S3 data uploads. Implements a "Champion-Challenger" evaluation logic that monitors data drift and triggers retraining jobs only when production model accuracy degrades. Manages the automated deployment of superior models to SageMaker endpoints, ensuring peak predictive reliability through continuous integration and deployment (CI/CD) of ML artifacts.


[![](https://img.shields.io/badge/AWS-white?logo=AWS)](#) [![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

<img src="images/Drift2.png?raw=true" />

---
### MenuVista - Scalable Data Engineering & Narrative Analytics for Culinary Trends

Developed an interactive narrative visualization platform that unifies 40,000+ historical restaurant records into a cohesive digital journey. Engineered a rigorous data cleaning pipeline using OpenRefine and Python, utilizing YesWorkflow to model data provenance and ensure logical transparency. Leveraged D3.js to orchestrate an animated, multi-scene web experience, using dynamic transitions and interactive triggers to unveil century-long culinary shifts.

[![](https://img.shields.io/badge/PostgreSQL-white?logo=PostgreSQL)](#) [![](https://img.shields.io/badge/D3-white?logo=D3)](#) [![](https://img.shields.io/badge/OpenRefine-white?logo=OpenRefine)](#) [![](https://img.shields.io/badge/OR2YWTool-white?logo=OR2YWTool)](#) [![](https://img.shields.io/badge/yesWorkflow-white?logo=yesWorkflow)](#)

[View code on Github](https://github.com/minjiefu/MenuVista) 

<img src="images/MenuVista.png?raw=true" />

---
### FilmPick - Driven Movie Recommendation & Sentiment Analysis

Created a personalized movie recommendation app using Dash. Implemented the Item-Based Collaborative Filtering (IBCF) Algorithm and sentiment analysis based on BERT, to optimize user experience by providing tailored movie suggestions.

[![](https://img.shields.io/badge/Plotly-white?logo=Plotly)](#) [![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#) [![](https://img.shields.io/badge/HuggingFace_Transformers-white?logo=huggingface)](#) [![](https://img.shields.io/badge/HTML-white?logo=Html)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/scikit--learn-white?logo=scikit--learn)](#) 

[View code on Github Part1 Movie Recommender](https://github.com/minjiefu/FilmPick-Part1)  <br>
[View code on Github Part2 Sentiment Analysis](https://github.com/minjiefu/FilmPick-Part2)

<img src="images/FilmPick5.png?raw=true" />

---

### Walmart Forecast-Time-Series Sales & Inventory Optimization

Developed a predictive model to forecast weekly sales across 45 Walmart stores, achieving a WMAE of 1589.75—representing a 25% error reduction over standard baseline models. Mitigated noise in historical sales data by implementing Singular Value Decomposition (SVD) for pre-processing and engineered granular models at the store-department level to capture localized seasonal trends and holiday spikes. This high-precision approach optimized inventory management and financial budgeting by providing actionable insights during peak promotional periods.‭

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/scikit--learn-white?logo=scikit--learn)](#) 


[View code on Github](https://github.com/minjiefu/Walmart-Store-Sales-Forcasting) 

---

### Pandemic Priorities - COVID-19 Vaccination Analysis & Tableau Dashboard

Designed an interactive Tableau dashboard to visually represent the spread of COVID-19 globally and assess the impact on countries with high infection rates and low vaccination coverage. The primary objective of this project is to pinpoint specific areas in need of targeted intervention and provide actionable strategies to bolster vaccination efforts and effectively combat the pandemic in these regions.

[![](https://img.shields.io/badge/Tableau-white?logo=Tableau)](#) 

<img src="images/PandemicPriorities.png?raw=true" />


---

### Statistical NLP: WordPiece Tokenizer & N-gram Probability Models

In this project, I developed a custom WordPiece tokenizer and N-gram language models from scratch to process and generate natural language text based on the Wikipedia corpus. The implementation featured advanced statistical techniques, including Absolute Discounting and Laplace smoothing, to optimize probability estimation and reduce model perplexity. To ensure high-performance execution, I leveraged efficient data structures like inverted indices to significantly accelerate subword merging and large-scale vocabulary training.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#) 

[View code on Github](https://github.com/minjiefu/Statistical-NLP-WordPiece-Tokenizer-N-gram-Probability-Models.git) 

---

### Deep Semantic Analysis: Leveraging Neural Networks for Text Classification

Engineered a deep learning system to automate movie review sentiment analysis, mapping raw text to high-dimensional semantic spaces. Developed a dual-stage pipeline featuring CBOW-based word embeddings and 1D-Convolutional layers to extract hierarchical textual features. Optimized model performance using global max-pooling and dropout, resulting in a robust classifier capable of 82% accuracy on unseen IMDb data.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#)  [![](https://img.shields.io/badge/Pytorch-white?logo=Pytorch)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) 

[View code on Github](https://github.com/minjiefu/Deep-Semantic-Analysis-Leveraging-Neural-Networks-for-Text-Classification.git) 

---

### Neural Machine Translation: RNN with Attention & Transformer Architectures

Developed a high-performance Spanish-to-English translation system by implementing and comparing two major deep learning paradigms: Recurrent Neural Networks (RNN) and Transformers. Engineered a custom attention mechanism and a Transformer encoder-decoder framework from scratch to capture complex cross-lingual dependencies and long-range linguistic patterns. Implemented a robust inference pipeline featuring Beam Search decoding with length penalty and temperature sampling, achieving significant BLEU score improvements and demonstrating proficiency in sequence-to-sequence modeling via PyTorch.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#)  [![](https://img.shields.io/badge/Pytorch-white?logo=Pytorch)](#) [![](https://img.shields.io/badge/RNN-white?logo=RNN)](#)  [![](https://img.shields.io/badge/Transformer-white?logo=Transformer)](#)

[View code on Github](https://github.com/minjiefu/Neural-Machine-Translation-RNN-with-Attention-Transformer-Architectures.git) 


---

### Dependency Parsing: Transition-based Neural Syntax Analysis

Constructed a transition-based dependency parser to analyze the grammatical structure and syntactic relationships within natural language sentences. Engineered a sophisticated feature extraction system to capture word, POS tag, and arc-label dependencies from parser configurations (Stack, Buffer, and Arcs). Implemented a multi-layer feed-forward neural network in PyTorch to predict parser transitions (Shift, Left-Arc, Right-Arc), achieving over 81% Labeled Attachment Score (LAS) on the Universal Dependencies dataset by enforcing legal move constraints during inference.


[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Pytorch-white?logo=Pytorch)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) 

[View code on Github](https://github.com/minjiefu/Dependency-Parsing-Transition-based-Neural-Syntax-Analysis.git) 

---

### Quantitative Portfolio Optimization System based on Modern Portfolio Theory (MPT)

Leveraged Python and financial APIs to ingest multi-asset historical data, calculating daily returns and covariance matrices to quantify risk-reward correlations across diversified assets. Executed Monte Carlo simulations to visualize the Efficient Frontier and utilized the SciPy optimization engine (SLSQP) to mathematically solve for the Maximum Sharpe Ratio and Minimum Volatility weight allocations. Developed visual analytics to compare simulated portfolios against optimized theoretical limits, providing data-backed evidence for capital allocation and risk management strategies.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github](https://github.com/minjiefu/Quantitative-Portfolio-Management.git) 

<img src="images/potfolio.png?raw=true" />

---


### GPT Clone - Transformer Architecture & Distributed Training

Developed a GPT-2 model from scratch using PyTorch, implementing the Transformer architecture based on the “Attention is All You Need” paper. Engineered a high-performance training pipeline utilizing Distributed Data Parallel (DDP) and gradient accumulation to resolve GPU memory constraints and accelerate convergence. Exceeded the original GPT-2 124M model’s loss performance within 2 hours of training through synchronized distributed processing and optimized hyperparameter tuning.


[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Pytorch-white?logo=Pytorch)](#) 


[View code on Github](https://github.com/minjiefu/GPT-Clone) 

---

### Baby Name Factory - Character-Level NLP & Sequence Modeling

Developed a character-level text generation model from scratch using NumPy to implement RNN and LSTM architectures. Resolved exploding gradient issues by applying gradient clipping and monitored model evolution through regular sampling every 2,000 steps. Evolved output from random sequences to phonetically structured names after 22,000 iterations.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) [![](https://img.shields.io/badge/Tensorflow-white?logo=Tensorflow)](#)


[View code on Github](https://github.com/minjiefu/Baby-Name-Factory) 

---

### Ames Housing Prices Prediction - Machine Learning Pipelines & Predictive Valuation

Developed high-performance models using XGBoost and Elastic Net, achieving a 0.125 RMSE (16% improvement over target). Executed advanced preprocessing including Winsorization to handle extreme outliers and engineered property-specific features to minimize prediction variance and ensure precise real estate valuation.‭

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Numpy-white?logo=Numpy)](#) [![](https://img.shields.io/badge/Pandas-white?logo=Pandas)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/scikit--learn-white?logo=scikit--learn)](#) 


[View code on Github](https://github.com/minjiefu/Ames-Housing-Prices-Prediction) 
