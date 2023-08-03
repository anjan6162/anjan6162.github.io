## Home Credit Default Risk Analysis

### Business Problem
Home Credit needs a homogenous strategy to compile alternative data to confirm prospective clients capable of loan repayments are not rejected. Home Credit uses telco and transactional data to predict the loan repayment abilities. Our analytics approach would be to use the full potential of the alternative data to see whether or not an applicant will be able to pay back a loan.

Home Credit wants to empower customers by enabling them to borrow easily and safely. With a solution, the business will have an increase in client’s and in turn provide more revenue for Home Credit. The scope of the project is to identify the potential defaulters based on exploratory data analysis with the data given about the applicants features. Success metrics will be defined by a larger circle of prospective clients being accepted that are capable of making loan repayments.

### Business Objective
To achieve greater loan application approval rates and enhance revenue while maintaining safe borrowing practices, our model will be designed to predict loan repayment capabilities and identify potential loan defaulters. By implementing robust risk assessment algorithms and leveraging comprehensive data analysis, our model will aid in reducing loan rejections and offer safer borrowing options to customers. This approach will empower financial institutions to make informed lending decisions, ensuring a more favorable outcome for both borrowers and lenders, ultimately fostering higher revenue generation and sustainable growth in the lending industry.

### Model suggestion to the business problem
We are suggesting "Combined Ensemble Model" as it achieved the highest accuracy of 93.0% and AUC (Area Under the Curve) of 0.715, indicating its superior predictive capability.This model, a powerful combination of logistic regression models and advanced feature engineering techniques, showcased remarkable performance by attaining the highest accuracy and AUC among all the models tested. This result underscores the effectiveness of integrating multiple predictive approaches, allowing for more robust and reliable predictions. 

Benefits of the model are

* Enhanced Accuracy: Significantly improved loan repayment predictions and reduced number of potential defaulters
* Increased Revenue: More reliable loan applicants approved. And also,there was reduction in defaulters, leading to improved financial performance
* Long-term Business Benefits: Improved customer retention and loyalty contribute to sustained growth.
* Efficient Risk Management: Precise identification of high-risk applicants and enhanced resource allocation and reduced financial risks.
* Customer Empowerment: Empowered customers with limited credit history to access loans easily. The model will Build trust and loyalty with customers, enhancing satisfaction.
* Competitive Advantage: Ability to process non-traditional data and make accurate predictions.

### My contribution to the project
Throughout the group project, I played a key role in both the exploratory data analysis (EDA) and modeling stages. In EDA, I utilized packages like skimr and janitor to explore and clean the data effectively. I also tackled missing data, addressed near-zero variance, and handled outliers in the dataset. For modeling, I focused on building an ensemble model, combining multiple models for better predictions. Additionally, I conducted feature engineering to improve the model's performance by selecting and transforming relevant features. These efforts were vital in achieving our project's success, ensuring a well-prepared and robust predictive model to meet our objectives.

### The business value
The proposed combined ensemble model for loan default prediction represents a significant opportunity for Homecredit. Currently, Homecredit experiences losses equivalent to approximately 7.52% of the total approved loan amount. However, with the implementation of our model, Homecredit can achieve an accurate identification of 72.35% of these defaulters, potentially resulting in savings of 5.5%, effectively reducing the loss to approximately 3%.

Furthermore, the integration of additional predictors into the model offers the potential for even greater savings, thereby enhancing the overall efficacy and sustainability of Homecredit's lending process. This elevated capability positions Homecredit to expand its services to a wider clientele while ensuring the maintenance of a robust and efficient lending approach.

### Difficulties faced in our project
Developing a model to predict loan defaults was a valuable learning experience, but it came with its fair share of challenges. Firstly, the dataset was quite large, which meant it took a lot of time to understand. Moreover, the data quality was not ideal due to many missing values and outliers. Secondly, we faced difficulties during exploratory data analysis because of the uneven distribution of the target variable. Additionally, feature engineering was tough as the fields had significant variations. We also had to spend considerable time trying out different models, each with its overfitting and underfitting issues. Despite these challenges, we successfully developed a high-performing model by carefully addressing these concerns.

### Project learnings
The loan default prediction model provided us with valuable lessons in handling complex datasets, dealing with class imbalances, and creating effective features. We also learned how to evaluate models using relevant metrics and prevent overfitting and underfitting issues through fine-tuning. Furthermore, when we applied the model in real-world scenarios, it significantly improved our risk management strategies and saved the company a substantial amount of money. These insights will guide us in future projects, helping us apply predictive analytics accurately and effectively to different business challenges across various industries.
