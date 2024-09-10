# Used-Car-Analysis-and-Research

## How to use
Locally:
```
pip install -r requirements.txt
python -m uvicorn main:app --reload
```
With Docker:
```
docker-compose up --build
```
Alternately:
```
docker build -t car-research .
docker run -p 8000:8000 car-research
```
Then go to http://localhost:8000

## Push to Docker Hub:
```
docker login
docker tag car-research kristada673/used-car-analysis-and-research:latest
docker push kristada673/used-car-analysis-and-research:latest
To use it:
docker pull kristada673/used-car-analysis-and-research:latest
docker run -p 8000:8000 kristada673/used-car-analysis-and-research:latest
```

## Web UI

Landing page:

<img width="867" alt="Screenshot 2024-09-10 at 5 03 59 PM" src="https://github.com/user-attachments/assets/657576ce-ff1a-4b92-817d-0e2d1f836995">

Optional parameters:

<img width="1083" alt="Screenshot 2024-09-10 at 5 13 04 PM" src="https://github.com/user-attachments/assets/eb800da1-a702-4202-b392-1eeb1028bd55">

Starting report creation:

<img width="842" alt="Screenshot 2024-09-10 at 5 14 19 PM" src="https://github.com/user-attachments/assets/0f0306ec-45a3-4338-a234-6217459e38a7">

Finished report:

<img width="1230" alt="Screenshot 2024-09-10 at 5 15 54 PM" src="https://github.com/user-attachments/assets/c8e25db6-b7c9-4f28-9237-f1ea82c1633a">

