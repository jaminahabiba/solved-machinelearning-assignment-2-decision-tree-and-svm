Download Link: https://assignmentchef.com/product/solved-machinelearning-assignment-2-decision-tree-and-svm
<br>
The data set available for this assignment is based on the U.S. congress voting record from 1984. The data set consists of the votes (yes or no) on sixteen issues for each of the 435 members of congress. from the voting record. You will use this data to learn a decision tree that predicts the political party of the representative based on his /her vote.

<ol>

 <li>Use the voting data to train a decision tree to predict political party (Democrat or Republican) based on the voting record. Use 25% of the members of congress for training and the rest for testing. Rerun this experiment five times and notice the impact of different random splits of the data into training and test sets. Report the sizes and accuracies of these trees in each experiment.</li>

 <li>Measure the impact of training set size on the accuracy and the size of the learned tree. Consider training set sizes in the range (30-70%). Because of the high variance due to random splits repeat the experiment with five different random seeds for each training set size then report the mean, maximum and minimum accuracies at each training set size. Also measure the mean, max and min tree size.

  <ul>

   <li>Start with training data size 30%, 40% … Until you reach 70%.</li>

   <li>The data set contained many missing values , i.e., votes in which a member of congress failed to participate. To solve those issue insert—for each absent vote—the voting decision of the majority.</li>

  </ul></li>

</ol>

<strong><u>Part B – SVM:</u></strong><strong>  </strong>

The attached dataset <strong>“heart.csv”</strong> contain 303 records of patients have heart disease or not according to features in it. You are required to build <strong>SVM</strong> model to predict whether patient have heart disease or not <strong>(target). </strong>

<strong>Cost Function: </strong>

<strong>Update Weights Equations: </strong>

<ul>

 <li><strong>If Point is correctly classified. </strong></li>

</ul>

<strong> </strong>

<ul>

 <li><strong>If Point is not correctly classified. </strong></li>

</ul>




<ol>

 <li>Split dataset into training and testing sets.</li>

 <li>Try different set of features and choose the best features.</li>

 <li>Try different values of learning rate and see how this changes the accuracy of the model.</li>

 <li>Implement accuracy function (correctly predicted values / test set size).</li>

</ol>

<strong><u>Note: The final grade is proportional to the accuracy of your results</u></strong><strong><u>.</u></strong>




<strong><u>Important Notes:</u></strong>

<ul>

 <li>You can only use “pandas”, “numpy” and “matplotlib” libraries. <strong><em>(Don’t use “sklearn”)</em></strong>  The maximum number of students in a team is 4 and minimum 3.</li>

 <li>No late submission is allowed.</li>

 <li>Cheating students will take negative grades and no excuses will be accepted.</li>

</ul>


