
Fault Severity Diagnosis Using Domain Adaptation Techniques  

## Overview  
This project focuses on diagnosing fault severity in bearings using domain adaptation techniques and deep learning. The primary objective is to improve the generalization of fault classification models across different operational conditions (drive end and fan end).  

## Dataset  
- The dataset contains bearing fault data with faults injected at **7 mm to 21 mm** in both the **fan end** and **drive end** of the motor.  
- The data is sourced from standard bearing failure datasets, ensuring real-world applicability.  

## Methodology  
- Four different deep learning models were implemented and evaluated for fault diagnosis.  
- The **Maximum Mean Discrepancy (MDD) model** outperformed all state-of-the-art algorithms in adapting to domain shifts and accurately diagnosing fault severity.  

## Results  
- The models were tested across different fault severities, demonstrating the effectiveness of domain adaptation techniques in predictive maintenance.  
- The MDD approach showed superior performance in minimizing distribution differences between source and target domains.  

## Repository Contents  
- **Data Preprocessing:** Scripts for cleaning and structuring the dataset.  
- **Model Implementations:** Code for all four tested algorithms.  
- **Evaluation Metrics:** Performance comparison of different approaches.  

## Future Work  
- Improving domain adaptation techniques for enhanced robustness.  
- Extending the approach to other rotating machinery datasets.  

## Contact  
For any queries or discussions, feel free to reach out:  
**M. Hemanth Kumar**  
MS in Data Science and Analytics, Georgia State University  
Email: hmulluri1@student.gsu.edu  

---
