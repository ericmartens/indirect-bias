# Indirect Bias Detection with Watson OpenScale

Demo materials for indirect bias detection in IBM Watson OpenScale. This repo contains notebooks to train and deploy a hiring screening model in Watson Machine Learning, and then monitor that model for unfair bias. We will monitor the model for bias against females and minority ethnic groups, even though these are not features of the model.

Instructions and links for provisioning the necessary services are included in the notebooks. There will be two versions: **hiring_production.ipynb** for simulating a production model, and **hiring_preprod.ipynb** for simulating a pre-production candidate model. Finally, a feed notebook that can be scheduled to supply a continuous stream of data to the production model will be provided.
