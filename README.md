# Performance_testing_NB_SVM through SPAM EMAIL DETECTION
Performance testing of different classifiers and methodologies
<h1>Results of Naive Bayes Classifier</h1>
<p>Training accuracy: 0.9971466198419666 or 99.71%</p>
<p>Testing accuracy: 0.9920983318700615 or 99.21%</p>
      <table border = "1">
         <tr>
            <th>\</th>
            <th>Predicted Positive</th>
            <th>Predicted Negative</th>
         </tr>
         <tr>
           <td>Actual Positive</td>
            <td>862</td>
            <td>8</td>
         </tr>
        <tr>
           <td>Actual Negative</td>
            <td>1</td>
            <td>268</td>
         </tr>
  </table>
<p>Here 1 spam were misclassified as non-spam and 8 non-spam were missclassified as spam</p>
<h1>Results of Support Vector Machine Classifier</h1>
<p>Training accuracy: 1.000000 or 100%</p>
<p>Testing accuracy: 0.974539 or 97.45%</p>
<table border = "1">
         <tr>
            <th>\</th>
            <th>Predicted Positive</th>
            <th>Predicted Negative</th>
         </tr>
         <tr>
           <td>Actual Positive</td>
            <td>864</td>
            <td>6</td>
         </tr>
        <tr>
           <td>Actual Negative</td>
            <td>23</td>
            <td>246</td>
         </tr>
  </table>
<p>Here 23 spam were misclassified as non-spam and 6 non-spam were missclassified as spam</p>
<h1>Results of RNN-long short term memory(LSTM)</h1>
<p>works to be done</p>
