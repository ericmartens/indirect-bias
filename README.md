# Indirect Bias Detection and auto-debias with Watson OpenScale

Demo materials for indirect bias detection in IBM Watson OpenScale. This repo contains notebooks to train and deploy a hiring screening model in Watson Machine Learning, and then monitor that model for unfair bias. OpenScale can monitor the model for bias against females and minority ethnic groups, even though these are not features of the model, or it can use the auto-debias functionality to remove bias at runtime without changing the underlying model.

Instructions and links for provisioning the necessary services are included in the notebooks. There are four versions:
* **hiring_production.ipynb** for simulating a production model
* **hiring_preprod.ipynb** for simulating a pre-production candidate model
* **auto_debias_preprod.ipynb** for using direct bias detection and showing off the capabilities of the automated debiasing endpoint
* **indirect_debias.ipynb** for demonstrating how indirect bias detection and automated debiasing can be combined
* **indirect_bias_auto_debias_cp4d** for demonstrating the combination of indirect bias and automated debias running on IBM Cloud Pak for Data
