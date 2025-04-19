app-repo/
├── service1/        # S3 Upload Service
│   ├── app.py       # Flask/FastAPI app
│   ├── Dockerfile   # Containerizes Service 1
│   └── requirements.txt
├── service2/        # SQS Message Service
│   ├── app.py       # Flask/FastAPI app
│   ├── Dockerfile   # Containerizes Service 2
│   └── requirements.txt
└── .github/workflows/
    ├── build-push-service1.yml  # CI for Service 1
    └── build-push-service2.yml  # CI for Service 2