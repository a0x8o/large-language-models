## Large Language Models

This repo contains the notebooks for the [Large Language Models: Application through Production](https://www.edx.org/course/large-language-models-application-through-production) course on [edX](https://www.edx.org/professional-certificate/databricks-large-language-models) & Databricks Academy. 

## How to Import the Repo into Databricks?

1. You first need to add Git credentials to Databricks. Refer to [documentation here](https://docs.databricks.com/repos/repos-setup.html#add-git-credentials-to-databricks).  

2. Click `Repos` in the sidebar. Click `Add Repo` on the top right.
    
    <img width="400" alt="repo_1" src="https://files.training.databricks.com/images/llm/repo_1.png">

    

3. Clone the "HTTPS" URL from GitHub, or copy `https://github.com/databricks-academy/large-language-models.git` and paste into the box `Git repository URL`. The rest of the fields, i.e. `Git provider` and `Repository name`, will be automatically populated. Click `Create Repo` on the bottom right. 

    <img width="700" alt="add_repo" src="https://files.training.databricks.com/images/llm/add_repo.png">
    
    
## Which Databricks cluster should I use? 

1. First, select `Single Node` 

    <img width="500" alt="single_node" src="https://files.training.databricks.com/images/llm/single_node.png">


2. This courseware has been tested on [Databricks Runtime 13.1 for Machine Learning]([url](https://docs.databricks.com/release-notes/runtime/13.1ml.html)). If you do not have access to a 13.1 ML Runtime cluster, you will need to install many additional libraries (as the ML Runtime pre-installs many commonly used machine learning packages), and this courseware is not guaranteed to run. 
    
    <img width="400" alt="cluster" src="https://files.training.databricks.com/images/llm/cluster.png">

    
    For all of the notebooks except `LLM 04a - Fine-tuning LLMs` and `LLM04L - Fine-tuning LLMs Lab`, you can run them on a CPU just fine. We recommend either `i3.xlarge` or `i3.2xlarge` (i3.2xlarge will have slightly faster performance).  

    <img width="400" alt="cpu_settings" src="https://files.training.databricks.com/images/llm/cpu_settings.png">
    
    For these notebooks: `LLM 04a - Fine-tuning LLMs` and `LLM04L - Fine-tuning LLMs Lab`, you will need the Databricks Runtime 13.1 for Machine Learning **with GPU**. 

    <img width="400" alt="gpu" src="https://files.training.databricks.com/images/llm/gpu.png">

    
    Select GPU instance type of `g5.2xlarge`.

    <img width="400" alt="gpu_settings" src="https://files.training.databricks.com/images/llm/gpu_settings.png">