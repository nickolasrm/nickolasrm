# MLOps

## Description

MLOps is the study field related to the implementation of ML applications and the scientists workflow. it is similar to DevOps, but focused on statistics and data science.

## Mindmap

```mermaid
flowchart LR;
  MLOps --> DevOps;
  DevOps --> CI/CD;
  CI/CD --> IaC;
  IaC --> Terraform;
  IaC --> Ansible;
  CI/CD --> Runners;
  Runners --> Actions;
  Runners --> CircleCI;
  Runners --> ...;
  CI/CD --> GitWorkflows;
  GitWorkflows --> Trunk;
  GitWorkflows --> Fork;
  GitWorkflows --> GitFlow;
  CI/CD --> PullRequests;
  DevOps --> UnitTests;
  DevOps --> PaaS/IaaS;
  PaaS/IaaS --> Azure;
  PaaS/IaaS --> AWS;
  PaaS/IaaS --> GCP;
  MLOps --> DataScience;
  DataScience --> Python;
  DataScience --> Statistics;
  Statistics --> Timeseries;
  Statistics --> BigData;
  Statistics --> Clustering;
  Statistics --> Explainability;
  Statistics --> Fairness;
  DataScience --> Frameworks;
  Frameworks --> Pandas;
  Frameworks --> ScikitLearn;
  Frameworks --> TensorFlow;
  Frameworks --> PyTorch
  Frameworks --> PyCaret
  DataScience --> Tools;
  Tools --> Jupyter;
  Tools --> Seaborn/Matplotlib;
  Tools --> PySpark;
  PySpark --> Spark;
  MLOps --> Deploy;
  Deploy --> Databricks;
  Deploy --> Docker;
  Deploy --> Computing;
  Computing --> AirFlow
  Computing --> AzureML
  Computing --> SageMaker;
  Computing --> DataBricks;
  DataBricks --> Spark;
  Deploy --> Tracking;
  Tracking --> Mlflow;
  Deploy --> Storage;
  Storage --> Blob;
  Storage --> SQL;
  Storage --> NoSQL;
  Storage --> Redis;
  Storage --> FeatureStore;
```

## References
- [My MLOps](https://mymlops.com/)
- [MLOps.org](https://ml-ops.org/content/mlops-stack-canvas)
