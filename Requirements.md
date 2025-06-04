# Chapter 4: Requirements

## 4.1 Requirements Gathering

During this interval, requirements were gathered from different sources like academic literature, example reports and analysis of current technologies and datasets. The main idea behind creating the prioritized list was the need for an all-inclusive set of problems that the project needed to fix, to successfully predict energy usage in smart homes through Machine Learning. The need for the project to be reliable, interpretable, and accurate are vital for a successful outcome and understanding of the question at hand.

Requirements prioritization is the process of defining an order for completing tasks based on their relative importance to the project at hand (Hatton, 2008). MoSCow is a prioritization technique, that implies the identification of the top rank requirements. These requirements are split into four groups:

- **Must Have**: these requirements must be fulfilled, otherwise the project has failed.
- **Should Have**: these requirements are a high priority but are not critical to the project's success.
- **Could Have**: these requirements are desirable, but less important than requirements in the should have and must have category.
- **Won't Have**: these requirements will not be implemented in the current project but could be in the future.

## 4.2 Requirements Specification

This section explains detailed requirements that were gathered and categorized as functional, non-functional and user requirements, both are key for model prediction to be developed.

### Functional Requirements Table

| Requirement | Description | Priority |
|-------------|-------------|----------|
| Machine Learning Environment Setup | Set up a Python 3 environment with libraries like NumPy, Pandas, Scikit-Learn, TensorFlow, and Keras for developing machine learning models. | Must Have |
| High-Quality Dataset | Ensure access to a clean, comprehensive dataset for model training. Relevant data is collected from the "Smart Home Dataset with Weather Information" on Kaggle. | Must Have |
| Data Pre-processing | Implement data cleaning, normalization, and preparation pipelines. | Must Have |
| Model Development | Develop multiple neural network architectures to compare performance. | Must Have |
| Model Evaluation | Test models on validation sets to ensure accuracy and effectiveness. | Must Have |
| Model Optimization | Techniques like hyperparameter tuning for improved model performance. | Should Have |
| Model Deployment | Deploy the model in a cloud environment for accessibility, such as Kaggle or Goggle Collab. | Should Have |
| Extended Data Features | Include additional data features to potentially enhance predictions. | Should Have |
| Extended Device Integration | Integrate with additional smart home devices for enhanced data collection. | Could Have |
| Advanced Visualization Tools | Develop advanced tools for visualizing energy consumption and predictions. | Could Have |
| User Customization Features | Allow users to customize alerts and energy usage reports. | Could Have |
| Full Automation of Appliance Control | Automated appliance control based on predictions. | Won’t Have |
| Internationalization | Support for multiple languages and international data formats. | Won’t Have |
| Comprehensive User Training Tools | Develop extensive training modules for system use. | Won’t Have |

### User Requirements Table

| User Requirement Priority | User Requirement Description | Evaluation |
|---------------------------|-------------------------------|------------|
| High | Accurate Prediction: The system must accurately predict total energy consumption based on historical data, weather conditions, and appliance usage patterns. | This requirement is crucial for the effectiveness of the system in optimizing energy consumption in smart homes. |
| High | Real-Time Data Integration: The system should integrate real-time weather data and appliance usage patterns to enhance prediction accuracy. | Real-time data integration ensures up-to-date predictions, improving energy management in smart homes. |
| Medium | Scalability: The system should be scalable to accommodate varying sizes of smart homes and different data volumes. | Scalability is important for the system to adapt to different home sizes and data loads without performance issues. |
| Medium | User-Friendly Interface: The system interface should be user-friendly, allowing homeowners to easily access and interpret energy consumption predictions. | A user-friendly interface enhances user experience and encourages homeowners to actively engage in energy management. |
| Low | Data Privacy and Security: The system must prioritize data privacy and security to protect sensitive information related to energy consumption. | While important, this requirement is lower as it is a common consideration in smart home systems. |

## 4.3 Predictors and Outcomes

**Predictors**: Appliance Usage and Weather Conditions  
**Outcome**: Total Energy Consumption

- `Use [kW]`: Total energy used  
- `House Overall [kW]`: Aggregate of all appliance usage  
- `Gen [kW]`: Total generated energy
