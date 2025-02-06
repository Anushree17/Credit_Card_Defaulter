<h1>Credit Card Defaulter</h1>
<img src='https://img-cdn.thepublive.com/fit-in/640x430/filters:format(webp)/newsdrum-in/media/media_files/gTS3fBxzQCAtpXTHo8eT.jpg' width='1000' height='500'>
<h2>Problem</h2>
<p>Financial institutions face significant risks due to credit card defaults. Accurately predicting whether a customer will default helps banks and lenders mitigate financial losses, optimize credit policies, and offer better financial products. This project aims to predict credit card defaulters based on customer data from Taiwan, emphasizing risk management by estimating the probability of default rather than just classifying clients as credible or not.</p>
<h2>Use Cases</h2>
<ul>
  <li>Risk Assessment for Loan & Credit Approvals – Helps banks evaluate an applicant’s likelihood of defaulting before issuing a credit card or loan.</li>
<li>Early Warning Systems – Identifies customers at high risk of default, enabling proactive measures like restructuring payment plans or offering financial counseling.</li>
<li>Fraud Detection & Prevention – Enhances fraud detection models by identifying unusual spending or repayment behaviors linked to potential defaults.</li>
<li>Automated Credit Risk Scoring – Integrates with credit scoring systems to refine risk evaluation using behavioral and financial patterns.</li>
<li>Dynamic Credit Limit Adjustments – Adjusts credit limits dynamically based on real-time spending behavior and payment history.</li>
</ul>
<h2>Dataset Information</h2>
<ul>
  <li>Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.</li>
  <li>Sex (1 = male; 2 = female)</li>
  <li>Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).</li>
  <li>Marital status (1 = married; 2 = single; 3 = others).</li>
  <li>Age (year)</li>
  <li>PAY_0,PAY_2,PAY_3,PAY_4,PAY_5,PAY_6:These Features Denote the repayment status:The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above</li>
  <li>BILL_AMT1,BILL_AMT2,BILL_AMT3,BILL_AMT4,BILL_AMT5,BILL_AMT6:Amount of bill statement </li>
  <li>PAY_AMT1,PAY_AMT2,PAY_AMT3,PAY_AMT4,PAY_AMT5,PAY_AMT6:Amount of previous payment (NT dollar)</li>
  </ul>

  <h2>Approach Used</h2>
  <ul>
    <li>Loaded and cleaned the dataset, handling missing values and outliers.Conducted exploratory data analysis (EDA) to understand key trends and correlations.</li>
    <li>Identified important predictors affecting default probability.
Scaled numerical variables to improve model performance.</li>
    <li>Tested multiple machine learning models, including Logistic Regression, Decision Tree, Random Forest, and XGBoost.Tuned hyperparameters for optimal performance.</li>
    <li>Used accuracy, precision, recall, F1-score, and AUC-ROC to assess model effectiveness.Focused on reducing false negatives, as missing a potential defaulter is more costly than misclassifying a non-defaulter.</li>
  </ul>

  <h2>Impact</h2>
  <ul>
    <li>Improved Risk Assessment: Enables financial institutions to make data-driven lending decisions, reducing potential losses.</li>
    <li>Better Credit Policy Optimization: Helps banks adjust interest rates and credit limits based on a customer’s predicted risk level.</li>
    <li>Enhanced Customer Segmentation: Allows financial institutions to provide personalized offers and financial advice to at-risk customers.</li>
  </ul>


  
  

