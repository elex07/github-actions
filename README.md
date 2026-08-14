### Github Actions
Pipelines to perform CI / CD using Github Actions

a) Docker CI / CD

GitHub repository
      │
      │ push to the branch
      ▼
GitHub Actions runner
      │
      ├── Checkout code
      ├── Login to Docker Hub
      ├── Docker build
      └── Docker push
              │
              ▼
          Docker Hub
