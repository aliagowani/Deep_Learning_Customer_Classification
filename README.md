#  Description and Overview
## Evaluating Output & Performance of a Neural Network for Small-Sized Insurance Company

This is a Proof of Concept (POC) project evaluating the output & performance of a Neural Network (NN) for a small-sized insurance company. We want to prove that applying Data Science principles and deep learning models can provide value to all types of businesses, even with limited dataset.

We leverage a real-case data from Texas Giant Insurance (TGI). TGI focuses on providing commercial and personal insurance programs to its clients. TGI is an independent insurance company with an in-depth knowledge of multiple insurance products and carriers. They proactively provide many services to their policyholders.

<p align="left">
  <img src="images/1.svg" width="100%" title="KDE of Customer and their duration" alt="KDE of Customer and their duration">
</p>

<p align="left">
  <img src="images/4.png" width="50%" title="Supervised Learning Models Evaluation" alt="Supervised Learning Models Evaluation">
</p>

We evaluated three models and showed that the deep learning model is the most accurate, even with the limited features and a small dataset. We will look at accuracy though, it may be argued that F1 Score may be more relevant:
<ol>
<li>Supervised Learning (Logistic Regression) Model: 73.9% (F1 Score: 78.7%)</li>
<li>Baseline Single-Layered NN: 69.4%</li>
<li>Bayesian Optimized Deep Learning NN: 77.8% (F1 Score: 84.6%)</li>
</ol>

<p align="left">
  <img src="images/2.svg" width="50%" title="Bayesian Optimization Search" alt="Bayesian Optimization Search">
</p>

<p align="left">
  <img src="images/3.svg" width="50%" title="Confusion Matrix of the Bayesian Optimized Model" alt="Confusion Matrix of the Bayesian Optimized Model">
</p>

We are pleased to report the following findings from phone calls with customers:
<ul>
<li>Two customers who are no longer TGI customers said they would be interested in coming back but are price sensitive. </li>
<li>Two customers who are no longer TGI customers are interested in return; though, TGI may prefer not for them to come back.</li>
<li>One customer who is still a customer asked for a quote to another line of insurance products (automobile). This was a pleasant surprise and may provide future up-selling opportunities.</li>
<li>The client confirmed the robustness of the model that they suggested using this model monthly to identify and prioritize existing customers and potential customers that would return to the company.</li>
</ul>

<i>Note: The Customer IDs have been modified to preserve customer privacy.</i>
