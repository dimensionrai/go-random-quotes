# go-random-quotes
![pipeline](img/pipeline.png)

In a nutshell, this pipeline job is created using Github Action which holds some jobs such as building, pushing, and deployment of simple applications to GKE. The build and push image process uses Google's container registry service (GCR). Furthermore, the deployment process is assisted by Kustomize, which is one of the CLI that is useful for maintaining Kubernetes configuration (Kubernetes Object) declaratively.

### Prerequisites 
```
- Github Action Pipeline
- Golang Service
- Google Container Registry (GCR)
- Google Kubernetes Engine (GKE)
- Gcloud CLI
- Helm Chart (optional)
- Cloudflare (optional)
- Quotes Dataset (https://www.kaggle.com/datasets/akmittal/quotes-dataset)
```

### Testing 
![q1](img/q1.png)
![q2](img/q2.png)
![q3](img/q3.png)
