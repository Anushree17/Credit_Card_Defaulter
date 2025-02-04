<h1>Credit Card Defaulter</h1>
<img src='https://img-cdn.thepublive.com/fit-in/640x430/filters:format(webp)/newsdrum-in/media/media_files/gTS3fBxzQCAtpXTHo8eT.jpg' width='1000' height='500'>
<h2>Project Description</h2>
<p>This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.</p>
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

  <h2>Libraries Used</h2>
  <ul>
    <li>Numpy</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
  </ul>

  <h2>Models Used</h2>
  <ul>
    <li>Logistic Regression</li>
    <li>Decision Tree Classifier</li>
    <li>Random Forest Classifier</li>
    <li>Support Vector Machine</li>
    <li>Gradient Boosting</li>
    <li>Extreme Gradient Boosting</li>
    <li></li>
  </ul>


  <h2>Evaluation Metrics</h2>
  <ul>
    <li>Accuracy</li>
    <li>Precision</li>
    <li>Recall</li>
    <li>F1 Score</li>
  </ul>


  <h2>Conclusion</h2>
  <p>From all baseline model, Random forest classifier shows highest test accuracy and F1 score and AUC.
Baseline model of Random forest and decision tree shows huge difference in train and test accuracy which shows overfitting.
After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87.10% and AUC is 0.874.
Cross validation and hyperparameter tunning certainly reduces chances of overfitting and also increases performance of model.</p>
  
  

