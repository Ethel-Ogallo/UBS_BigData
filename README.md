## Scalable Geospatial ML & DL Projects

This repository contains two independent projects demonstrating scalable workflows for geospatial datasets using Machine Learning and Deep Learning approaches.

```
.
├── project1/
│   ├── scripts/                # Core ML pipeline (preprocessing, feature engineering, training)
│   ├── results/                # Outputs (metrics, logs, scalability plots)
│   ├── report/main.pdf         # Detailed report describing scaling experiments
│   ├── README.md               # Detailed ML project documentation
│
├── project2/
│   ├── scripts/                # Core DL pipeline (model architectures, training loops, utils)
│   ├── results/                # Model checkpoints, logs, performance summaries
│   ├── report/main.pdf              # Detailed report describing scaling experiments
│   ├── README.md               # Detailed DL project documentation
│
├── .gitignore
└── README.md               
```

### Project Summaries
**1. Scalable Machine Learning**  
Distributed ML workflow for large geospatial datasets, with Spark-based preprocessing, feature engineering, training, and scalability experiments.  
Full details in: project1/README.md  

**2. Scalable Deep Learning**  
Scalable deep learning pipeline designed for GPU and multi-GPU training on large imagery datasets.  
Full details in: project2/README.md    

### Purpose  
This repository provides a unified place to compare scalable techniques across ML and DL, focusing on:  
- Differences in preprocessing approaches
- CPU-based vs. GPU-based scaling
- Distributed execution strategies
- Performance and scalability trade-offs
