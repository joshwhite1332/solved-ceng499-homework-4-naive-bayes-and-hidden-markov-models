Download Link: https://assignmentchef.com/product/solved-ceng499-homework-4-naive-bayes-and-hidden-markov-models
<br>
<h1>1           Introduction</h1>

In this assignment, you will have the chance to get hands-on experience with the naive Bayes model and hidden Markov models (HMM). Python is the programming language choice for this homework. Only Python ≥ 3.0 is allowed.

<h1>2           Naive Bayes (60 pts)</h1>

In this section, you are going to implement a naive Bayes classifier. You will write your code in the function <strong>naive bayes </strong>in <strong>task1.py</strong>. When grading, we will call the function with different parameters.

<ul>

 <li>The dataset is a CSV file where each line is an instance. And, the last column is the label of an instance.</li>

 <li>No external library is allowed for this task.</li>

 <li>For the provided dataset, the accuracy value you should achieve is 88,15.</li>

 <li>Since you need to know the number of features and the possible values of a feature to compute the probabilities, you will iterate over the dataset for those values. Because a value of the feature may be present in one set but not present in the other set, you need to iterate over both training and test sets to get the values right.</li>

 <li>The time limit for this task is 1 minute.</li>

</ul>

1

<h1>3           Hidden Markov Models (40 pts)</h1>

In this section, you are going to implement the forward and Viterbi algorithms to solve evaluation and decoding tasks of HMMs. You will write your code in the functions <strong>forward </strong>and <strong>viterbi </strong>in <strong>task2.py</strong>. To test your implementation, you can use <strong>task2 </strong><strong>runner.py</strong>.

<ul>

 <li>As an external library, only NumPy is allowed.</li>

 <li>The provided data consists of NumPy arrays having np.float64 items. In your implementations, do continue to use np.float64 precision.</li>

 <li>The limit is for this task is 1 minute (running task2 runner with all provided data).</li>

 <li>As a reference for HMMs, you can check this <a href="https://web.stanford.edu/~jurafsky/slp3/A.pdf"><strong>link</strong></a><a href="https://web.stanford.edu/~jurafsky/slp3/A.pdf">.</a></li>

</ul>

<h1>4           Specifications</h1>

<ul>

 <li>If you exceed the time limit, you will get no points from that task.</li>

 <li>Falsifying results, changing the composition of training and test data are strictly forbidden, and you will receive 0 if this is the case. Your programs will be examined to see if you have actually reached the results and if they are working correctly.</li>

 <li>Using any piece of code that is not your own is strictly forbidden and constitutes as cheating. This includes friends, previous homeworks, or the internet. The violators will be punished according to the department regulations.</li>

 <li>Follow the course page on ODTUClass for any updates and clarifications. Please ask your questions on the discussion forum of ODTUClass instead of e-mailing.</li>

 <li>You have total of 3 late days for <strong>all </strong>your homeworks. For each day you have submitted late, you will lose 10 points. The homeworks you submit late after your total late days have exceeded 3 will not be graded.</li>

</ul>

<h1>5           Submission</h1>

Submission will be done via ODTUClass. You will submit a zip file called <strong>hw4.zip </strong>that contains <strong>task1.py </strong>and <strong>task2.py</strong>.

2