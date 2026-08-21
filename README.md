### Github Actions  
Pipelines to perform CI / CD using Github Actions  
  
a) Docker CI / CD  
  
GitHub repository  
      │  
      │ Push to the branch  
      ▼  
GitHub Actions runner  
      │  
      ├── Checkout code  
      ├── Set Image Tag  
      ├── Login to Docker Hub  
      ├── Docker Build (Multiple for all Containers)  
      ├── Docker Push  
      ├── Docker Compose  
      ├── Docker Remove Dangling Images  
      └── Docker Print Logs   
              │  
              ▼  
          Docker Hub  
