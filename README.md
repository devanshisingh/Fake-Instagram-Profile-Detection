# Fake-Instagram-Profile-Detection

This is a mini-project I completed under Coursera Project Network. 

In this hands-on project, I have built a deep neural network model to detect spam (fake) Instagram accounts.

<ul>
  <li><b>Dataset Used</b> - Uploaded as insta_train.csv and instra_test.csv
    <h5>Parameters Used</h5>
    <table>
      <tr><th>Feature</th><th>Values</th><th>Type of value</th></tr>
      <tr><td>Profile Pic</td><td>Yes or No</td><td>0 or 1</td></tr>
      <tr><td>Full Name</td><td>No. of words</td><td>Integer</td></tr>
      <tr><td>Description Length</td><td>No. of words</td><td>Integer</td></tr>
      <tr><td>Private</td><td>Yes or No</td><td>0 or 1</td></tr>
      <tr><td>Posts</td><td>No. of posts</td><td>Integer</td></tr>
      <tr><td>Followers</td><td>No. of followers</td><td>Integer</td></tr>
    </table>     
  </li>
  <li><b>Exploratory Data Analysis</b> - Checked for null values and analysed the statistical summary of the data</i>.</li>
  <li><b>Data Visualisation</b> - Using Seaborn and Matplotlib libraries in Python
  <li><b>Data Preprocessing</b> - Data Normalisation using Scikit Learn and transformed 'Fake' column data to categorical using Keras
  <li><b>Creating model</b> - Sequential Model. Used ReLU activation function for the input and the hidden layers and Softmax activation function for the output layer.</li>
  <li><b>Training the model</b> - Used 20 epochs for training the model.</li>
  <li><b>Evaluation</b> - Getting an accuracy of 91%.</li>

