# Cherry Leaf Health Detection

## Brief Introduction

Cherry Leaf Health Detection project, uses the power of machine learning to transform the way we inspect cherry trees. Our goal is to visually differentiate healthy cherry leaves from those affected by powdery mildew and predict the health of cherry leaves. This project is driven by the critical needs of the cherry plantation industry to ensure the supply of high-quality cherries to the market efficiently and cost-effectively.

## Dataset Content

* The dataset is sourced from [Kaggle](https://www.kaggle.com/codeinstitute/cherry-leaves). We then created a fictitious user story where predictive analytics can be applied in a real project in the workplace.
* The dataset contains +4 thousand images taken from the client's crop fields. The images show healthy cherry leaves and cherry leaves that have powdery mildew, a fungal disease that affects many plant species. The cherry plantation crop is one of the finest products in their portfolio, and the company is concerned about supplying the market with a compromised quality product.

## Business Requirements

The cherry plantation crop from Farmy & Foods is facing a challenge where their cherry plantations have been presenting powdery mildew. Currently, the process is manual verification if a given cherry tree contains powdery mildew. An employee spends around 30 minutes in each tree, taking a few samples of tree leaves and verifying visually if the leaf tree is healthy or has powdery mildew. If there is powdery mildew, the employee applies a specific compound to kill the fungus. The time spent applying this compound is 1 minute.  The company has thousands of cherry trees, located on multiple farms across the country. As a result, this manual process is not scalable due to the time spent in the manual process inspection.

To save time in this process, the IT team suggested an ML system that detects instantly, using a leaf tree image, if it is healthy or has powdery mildew. A similar manual process is in place for other crops for detecting pests, and if this initiative is successful, there is a realistic chance to replicate this project for all other crops. The dataset is a collection of cherry leaf images provided by Farmy & Foods, taken from their crops.

1. The client is interested in conducting a study to visually differentiate a healthy cherry leaf from one with powdery mildew.

2. The client is interested in predicting if a cherry leaf is healthy or contains powdery mildew.

## Hypothesis and how to validate?

1. **Machine Learning -** We suspect that a machine learning model can be trained to accurately distinguish healthy cherry leaves form those with powdery mildew.
    * **Validation:** To validate this hypothesis, we will train an image classification model based ond the cherry leaf images provided in the dataset. We will assess the model's performance using classification metrics such as accuracy, recall, and F1-score on a test set. The sucess of the validation will be demostrated by te model's performance on thes metrics.

2. **Automation -** We suspect that automating the detection of powdery mildew on cherry will significantly save time compared to the current manual process
   * **Validation:** We will conduct a comparative study of the time required for manual powdery mildew detection on cherry leaves versus automated detection by the developed ML model. We will collect data on the time spent with each method and demonstrate the time savings achieved through automation.

3. **Model Scalability -** We suspect that the ML model developed for powdery mildew detection on cherry leaves can be successfully replicated for other crops and pest detections.
    * **Validation:** If the hypothesis holds true, following the success of the project for cherry leaves, we plan to replicate the same model for other crops and pest detections. Validation of this hypothesis will be the ability to deploy the model in other scenarios and obtain accurate results.

## The rationale to map the business requirements to the Data Visualisations and ML tasks

The client's interest in conducting a study to visually differentiate healthy cherry leaves from those affected by powdery mildew steam from a critical need within the cherry plantation industry. The ability to rapidy identify leaves with powdery mildew is essential to ensure the supply of high-quality cherries to the market.

The process of manually inspecting each cherry tree, collecting leaf samples, and visually detecting powdery mildew is time-consuming and not scalable due to the large number of cherry tree across multiple farms. To address this challenge, the IT team proposed the implementation of a machine learning (ML) system, which aligns with the client's second requirement, oo predict the health of cherry leaves.

The rationale behind mapping these business requirements to Data Visualizations and ML tasks is twofold:

#### 1- **Visual Differentiation of Healthy and Powdery Mildew Leaves**

* By leveraging data visualization and ML, we aim to provide a solution that visually distinguishes health leaves form those with powdery mildew. This task aligns with the client's first requirement and will involve the development of a classification model that can accurately classify individual leaves based on image analysis.

#### 2- Prediction of Leaf Health

* The second business requirement, which involves predicting the health of cherry leaves, will be addressed through machine learning tasks. This will involve the creation of a predictive model that, when provided with an image of a cherry leaf, can determine whether it is healthy or affected by powdery mildew. Data visualizations will also play a role in illustrating the model's performance and its ability to make accurate predictions.

The successful completion of these Data Visualizations and ML tasks will not only fulfill the client's requirements but also revolutionize the way cherry plantation crops are managed. Automation of leaf inspections through ML will lead to increased efficiency, reduced manual labor, and a more reliable supply of high-quality cherries to the market.

## ML Business Case

* **Objective:** The primary objective of this project is to develop a robust and scalable machine learning solution for the automated detection of powdery mildew in cherry leaves. This solution will address the client's critical needs by providing the ability to visually differentiate healthy cherry leaves from those affected by powdery mildew and predict the health of cherry leaves. The ultimate goal is to revolutionize the inspection process for cherry trees and improve the quality of the cherry crop.

* **Method:** The ML business case involves the implementation of a machine learning model for image classification and prediction. The model will be trained on a dataset containing thousands of images of cherry leaves, both healthy and affected by powdery mildew. The classification task aims to visually distinguish healthy leaves from those with powdery mildew, while the prediction task aims to determine the health of cherry leaves based on input images.

* **Outcome:** The successful implementation of the ML model will result in several significant outcomes:

  1. **Time Efficiency:** By automating the detection and prediction process, the time required for inspecting cherry trees will be substantially reduced. This will lead to a more efficient and scalable approach to tree inspection.

  2. **Quality Assurance:** The model's ability to accurately identify leaves with powdery mildew will improve the quality of the cherry crop. Early detection of diseased leaves allows for timely intervention, reducing the risk of fungal spread and crop damage.

  3. **Cost Savings:** The reduction in manual labor and improved crop quality will lead to cost savings for the client. The efficient allocation of resources and the elimination of time-consuming manual inspections will result in financial benefits.

  4. **Scalability:** Once successfully implemented for cherry leaves, this ML solution can be replicated for other crops and pest detections, providing a scalable and adaptable framework for future agricultural projects.

* **Metrics for Success:** The success of the ML business case will be evaluated based on the following key metrics:

  1. **Model Accuracy:** The classification and prediction model should achieve high accuracy in distinguishing healthy leaves from those with powdery mildew.

  2. **Efficiency Gains:** The time saved through automation should be measurable and demonstrate significant efficiency gains compared to manual inspection.

  3. **Improved Crop Quality:** The quality of the cherry crop should improve, with a reduction in the presence of powdery mildew, as evidenced by field observations and crop quality assessments.

  4. **Replicability:** The ability to replicate the model for other crops and pest detections is a crucial success factor, indicating scalability and adaptability.

The ML business case outlines the strategic objectives, methods, expected outcomes, and success metrics for this project, demonstrating the potential for transformative impact within the cherry plantation industry.

## Dashboard Design

* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other items, that your dashboard library supports.
* Finally, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project, you were confident you would use a given plot to display an insight, but later, you chose another plot type).

## Unfixed Bugs

* You will need to mention unfixed bugs and why they were unfixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable for consideration, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment

### Heroku

* The App live link is: <https://YOUR_APP_NAME.herokuapp.com/>
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. At the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.

## Main Data Analysis and Machine Learning Libraries

* Here you should list the libraries used in the project and provide an example(s) of how you used these libraries.

## Credits

* In this section, you need to reference where you got your content, media and from where you got extra help. It is common practice to use code from other repositories and tutorials. However, it is necessary to be very specific about these sources to avoid plagiarism.
* You can break the credits section up into Content and Media, depending on what you have included in your project.

### Content

* The text for the Home page was taken from Wikipedia Article A.
* Instructions on how to implement form validation on the Sign-Up page were taken from [Specific YouTube Tutorial](https://www.youtube.com/).
* The icons in the footer were taken from [Font Awesome](https://fontawesome.com/).

### Media

* The photos used on the home and sign-up page are from This Open-Source site.
* The images used for the gallery page were taken from this other open-source site.

## Acknowledgements (optional)

* Thank the people that provided support throughout this project.
