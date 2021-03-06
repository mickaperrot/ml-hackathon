# ml-hackathon
Sample Google Cloud AI Platform notebook for ML Hackathon

This notebook is a sample [Google Cloud AI Platform Notebook](https://cloud.google.com/ai-platform-notebooks) for running a ML Hackathon.  

## Prerequisites: enable Google Cloud APIs
### Step 1:
Make sure your are using the correct Google Cloud project.  
You can check which project you are currently using from the top left of the Google Cloud console:
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-CheckProject.png)
### Step 2:
Enable the Notebooks API.  
Click [this link](https://console.cloud.google.com/apis/library/notebooks.googleapis.com) or use the search bar to access the **Notebooks API** page.  
On the API page, click **Enable** to enable the API.  
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-EnableNotebooksAPI.png)
### Step 3:
Enable the AI Platform Training & Prediction API.  
Click [this link](https://console.cloud.google.com/marketplace/product/google/ml.googleapis.com) or use the search bar to access the **AI Platform Training & Prediction API** page.  
On the API page, click **Enable** to enable the API.  
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-Enable%20CAIPAIP.png)

## Create your AI Platform Notebook
### Step 1:
Go to the AI Platform Notebook page.  
Click [this link](https://console.cloud.google.com/ai-platform/notebooks/) or use the search bar to access the **AI Platform Notebook** page.
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-AccessNotebook.png)
### Step 2:
Create a new AI Platform Notebook instance.  
From the Notebook page, click **New Instance** to create your AI Platform Notebook instance.  
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-CreateNotebook.png)
### Step 3:
Select the instance template you want to use.
This notebook has been designed with the template **TensorFlow Enterprise 2.3** as the instance type and **Without GPUs**.  
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-SelectInstanceType.png)
### Step 4:
Customize your instance if needed.
For example, you can change your instance region to **europe-west1 (Belgium)** to reduce latency, when ready click **Create**.  
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-CreateInstance.png)
### Step 5:
Connect to your Notebook.
Once your instance is created, click **Open JupyterLab** to access your Notebook.
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-OpenNotebook.png)

## Import this notebook
![](https://storage.googleapis.com/mickael_public_bucket/inetum-ml-hackathon/Screenshot-CloneNotebook.png)
### Step 1:
From your notebook, go to the **Git** menu.  
### Step 2:
Select **Clone a Repository**.  
### Step 3:
Enter the notebook URL:  ``https://github.com/mickaperrot/ml-hackathon.git``  
Click **Clone**.  