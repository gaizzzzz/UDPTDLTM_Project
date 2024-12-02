# UDPTDLTM_Project

## Setup

### Requirements:

- Modules and dependencies in `requirements.txt`
- Run `pip install -r requirements.txt`

### Crawler:

> Setup driver locally for selenium
- Using `topdev_crawler_save_time.ipynb`

### Preprocess:

- Clear the data from MongoDB Atlas Collection
> Update csv_backup from: [Backup_Data](https://drive.google.com/drive/u/0/folders/14Yj5p6biBFBiXYM0dcZYV88EyMJQ45PG)
- Run all cells in `topdev_preprocess_all_in_one.ipynb`

### Model:

- Evaluate the Gemini GenAI in predicting job salary, using `topdev_evaluate_salary_model.ipynb`
- Run all cells in `topdev_model_preparation.ipynb`

### Test streamlit:

- Open terminal and run:
```
streamlit run test.py
```
- Open browser and go to http://localhost:8501/

- Now, you can see the MongoDB dashboard in homepage

### Deploy web application:

- If testing streamlit successfully, open terminal and run:
```
streamlit run app.py
```
- Open browser and go to http://localhost:8501/

- Then, launch the app 😍 

## About