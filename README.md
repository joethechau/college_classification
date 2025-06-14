# U.S. College Application Classification | Logistic Regression, R

<p><strong>Classified U.S. colleges by application volume using logistic regression in R, achieving 95% accuracy and identifying key predictors like top 10% enrollment and room &amp; board costs.</strong></p>

<ul>
  <li>Built logistic regression model to classify colleges receiving ≥10,000 applications based on features like Top10perc, Grad Rate, and Room &amp; Board</li>
  <li>Created binary target variable and converted categorical predictor (Private) to factor with proper reference level</li>
  <li>Interpreted model coefficients and odds ratios; found private status significantly decreases odds of high application volume (p &lt; 0.001)</li>
  <li>Predicted probabilities and classified outcomes using 0.35 threshold; evaluated performance with confusion matrix</li>
  <li>Achieved 95% overall accuracy with high specificity (98%) but moderate sensitivity (38%) due to class imbalance</li>
  <li>Highlighted false negative impact and suggested model refinement for improved positive class recall</li>
</ul>

