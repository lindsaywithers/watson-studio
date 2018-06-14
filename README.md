# Machine learning & AI in Watson Studio: Hands-On

Watson Studio provides you with the environment and tools to solve your business problems by collaboratively working with data. You can choose the tools you need to analyze and visualize data, to cleanse and shape data, to ingest streaming data, or to create, train, and deploy machine learning models.

This illustration shows how the architecture of Watson Studio is centered around the project. A project is where you organize your resources and work with data. 

![alt text](https://github.com/lindsaywithers/watson-studio/blob/master/WatsonStudioArch.png)


IBM Watson Studio is a collaborative environment with AI tools that you and your team can use to collect and prepare training data, and to design, train, and deploy machine learning models.

Ranging from graphical tools you can use to build a model in minutes, to tools that automate running thousands of experiment training runs and hyperparameter optimization, Watson Studio AI tools support popular frameworks, including: TensorFlow, Caffe, PyTorch, and Keras.

You can think of Watson Studio AI tools in three categories:

1. **Machine learning**
2. **Deep learning**
3. **Visual recognition**
    
    
These tutorials will be centered around the Machine Learning category & the tools for designing, training and managing models:
* **Model builder** guides you, step by step, through building a model that uses Spark ML algorithms.
* **Flow editor** presents a graphical view of your model while you build it by combining nodes representing objects or actions (including SPSS Modeler nodes, Spark ML algorithm nodes, and neural network nodes.)
* **Notebooks** provide a collaborative environment for working with data, and rapid prototyping and testing of models.

# Step One: Create an account

1. Go to https://dataplatform.ibm.com/
2. Click 'Sign Up' in the upper-right corner.
3. Enter your email to create an IBM Cloud account
    1. Check the box to accept Watson Studio and Knowledge Catalog terms and conditions.
    2. If you don't already have an IBMid, click 'Create an IBMid'.
    3. Fill out your information, and verify your account via email.
    4. Once your IBMid has been verified, and you are logged into IBM Cloud - you are ready to begin.
4. In a new tab, navigate to [Watson Studio](https://dataplatform.ibm.com/)
    1. Click 'Log in'.
    2. You will be prompted to Select Organization and Space. This is to connect your Watson Studio service to your IBM Cloud       account. Make sure you see your IBMid in the 'IBM Cloud Organization' box, and hit 'Continue'.
    3. You should see a window appear that says your account is registered - click to get started.

# Step Two: Create a project

1. From your Watson Studio dashboard, click 'New project'
    1. You will see a prompt to select a project tile. By default, the 'Complete' tile is selected for you. Let's keep the default - and click 'OK'.
2. Name your project 'Watson Studio Lab'.
3. Optional, uncheck 'Restrict who can be a collaborator'.
4. A Cloud Object Storage (COS) instance is required to create a project. This will be the underlying storage for all assets within the project (data, notebooks, models, etc.).
    1. Select the 'Lite' plan for COS
    2. Click 'Create' 
    3. Click 'Confirm'
    4. Click 'Refresh' - and now you have your COS service linked to the project.
5. Click 'Create'

The overview tab gives you a preview of your assets, bookmarks, collaborators and recent activity. 

# You're now ready to start building models in Watson Studio! 

[**Build with Model Builder**](https://github.com/lindsaywithers/watson-studio/blob/master/Lab1_Model_Builder.pdf)

[**Build with Jupyter Notebook**](https://github.com/lindsaywithers/watson-studio/blob/master/Lab2_Notebooks.pdf)

[**Build with Flow Editor**](https://github.com/lindsaywithers/watson-studio/blob/master/Lab3_ModelerFlows.pdf)
