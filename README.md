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
- Run all cells in `topdev_preprocess_job_cluster.ipynb` to get `processed_data.csv`

### Deploy web application:

- If testing streamlit successfully, open terminal and run:
```
streamlit run app.py
```
- Open browser and go to http://localhost:8501/

- Then, launch the app 😍 

## About