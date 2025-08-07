
# IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies

This repository documents the capstone project completed during the **IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**. The program was jointly organized by **Edunet Foundation**, **AICTE**, and **IBM SkillsBuild** to empower students with hands-on experience in Artificial Intelligence and Cloud Computing.

The primary objective was to solve a real-world problem using AI tools and IBM Cloud services through a project-based learning model.



## 📝 Table of Contents

* [👨‍💻 Intern Details](#intern-details)
* [📖 About the Internship](#about-the-internship)
* [💡 Project Overview: Predicting Eligibility for NSAP](#project-overview-predicting-eligibility-for-nsap)
* [⚙️ Technology Stack](#technology-stack)
* [🚀 Project Workflow](#project-workflow)
* [📊 Results](#results)
* [📁 Repository Contents](#repository-contents)



## 👨‍💻 Intern Details

* **Name**: VISWAVANI H
* **Institute**: University College of Engineering Tindivanam
* **Branch**: Computer Science and Engineering
* **Internship Duration**: 15th July 2025 – 7th August 2025



## 📖 About the Internship

This 4-week program offered hands-on exposure to IBM Cloud and AI/ML tools via virtual masterclasses, mentor-led sessions, and project development.

### Weekly Breakdown:

* **Week 1**: Orientation, IBM Cloud setup, Intro to AI & Cloud Computing
* **Week 2**: Data Analytics Concepts and Hands-on-Labs
* **Week 3**: Auto AI experiments, Chatbot development and AI/ML Experiments on IBM Cloud
* **Week 4**: Agentic AI and Capstone Project Evaluation

> ✅ Certification Criteria: Completion of at least 2 IBM SkillsBuild courses, regular participation, and final project submission.



## 💡 Project Overview: Predicting Eligibility for NSAP

### Problem Statement:

The National Social Assistance Programme (NSAP) aims to provide financial support to marginalized groups. However, manual verification of eligibility is slow and error-prone, delaying assistance to the elderly, widows, and persons with disabilities. Each sub-scheme has its own criteria, making classification difficult.

### Proposed Solution:

An end-to-end machine learning solution was developed to automate the eligibility classification under the National Social Assistance Programme (NSAP). The system uses district-level demographic and socio-economic data to predict which NSAP sub-scheme (e.g., for elderly, widows, or persons with disabilities) an applicant is eligible for. 
The final trained model was deployed as a RESTful web service on the IBM Watsonx.ai platform, enabling real-time predictions.



## ⚙️ Technology Stack

* **Platform**: IBM Cloud

* **Tools**:

  * IBM Watsonx.ai Studio
  * IBM Watson Machine Learning
  * IBM AutoAI

* **Languages & Libraries**:

  * Python
  * scikit-learn
  * pandas
  * ibm-watsonx-ai



## 🚀 Project Workflow

1. **Data Acquisition**: Dataset sourced from AI Kosh (district-wise NSAP pension data)
2. **Preprocessing**: Handled missing values, encoded categorical fields, normalized data
3. **Model Training**:

   * AutoAI selected the best algorithm
   * Decision Tree Classifier (Pipeline 8) performed best with 96.7% accuracy
4. **Deployment**:

   * Deployed on IBM Watson ML
   * Exposed as a REST API endpoint
5. **Testing**:

   * Verified with real-time inputs for accurate scheme prediction



## 📊 Results

* **Best Model**: Pipeline 8 – Decision Tree Classifier
* **Accuracy**: 96.7% (Cross-Validated)
* **Training Time**: \~24 seconds
* **Deployment**: Successful as REST API for real-time classification


The system proved effective in **automating beneficiary classification**, drastically reducing human effort and improving speed and reliability in welfare distribution.



## 📁 Repository Contents

* `NSAP_Scheme_Eligibility_Predictor.ipynb`: The notebook containing the AutoAI model and deployment code
* `IBM_AI_Cloud_internship_Final_Project.pdf`: Final project report presentation
* `README.md`: This file



## 🔗 References

* [NSAP Official Portal](https://nsap.nic.in)
* [AI Kosh Dataset – NSAP](https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_pro)
* [IBM Cloud Docs](https://cloud.ibm.com/docs)
* [GitHub Repository](https://github.com/Viswavani/IBM-Cloud-Project.git)


