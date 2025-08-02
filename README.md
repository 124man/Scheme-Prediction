Project Overview:
This project predicts the most suitable National Social Assistance Programme (NSAP) scheme — IGNOAPS, IGNWPS, or IGNDPS — based on applicant demographic and socio-economic data.
Built using IBM watsonx.ai AutoAI, deployed as a REST API for real-time predictions.

Technologies Used:
IBM watsonx.ai Studio (AutoAI)
IBM watsonx.ai Runtime
IBM Cloud Pak for Data
IBM Cloud Object Storage
Random Forest Classifier

Dataset:
File: nsapallschemes.csv
Contains demographic and socio-economic attributes with scheme codes as labels.

Workflow:
Upload Dataset → IBM Cloud Object Storage
AutoAI Pipeline → Preprocessing + Model Selection
Deploy Model → watsonx.ai Runtime as REST API
Consume API → Get predicted scheme with confidence scores

Future Scope
Add more welfare schemes
Real-time data updates
Explainable AI for prediction transparency
Mobile and web integration
