# isye6740-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [ISYE6740 Homework 6 Solved](https://www.ankitcodinghub.com/product/isye6740-total-100-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121226&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYE6740 Homework 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
1. Conceptual questions. (20 points)

(a) (5 points) Explain how we control the data-fit complexity in the regression tree. Name at least one hyperparameter that we can turn to achieve this goal.

(b) (5 points) Explain how OOB errors are constructed and how to use them to understand a good choice for the number of trees in a random forest. Is OOB an error test or training error, and why?

(c) (5 points) What’s the main difference between boosting and bagging? The random forest belongs to which type?

(d) (5 points) Explain how to prevent overfit in CART?

t ϵt αt Zt Dt(1) Dt(2) Dt(3) Dt(4) Dt(5) Dt(6) Dt(7) Dt(8)

1

2

3

2. AdaBoost. (20 points)

Consider the following dataset, plotted in the following figure. The first two coordinates represent the value of two features, and the last coordinate is the binary label of the data.

X1 = (−1,0,+1),X2 = (−0.5,0.5,+1),X3 = (0,1,−1),X4 = (0.5,1,−1), X5 = (1,0,+1),X6 = (1,−1,+1),X7 = (0,−1,−1),X8 = (0,0,−1).

(a) (10 points) For each iteration t = 1,2,3, compute ϵt, αt, Zt, Dt by hand (i.e., show the calculation steps) and draw the decision stumps on the figure (you can draw this by hand).

(b) (10 points) What is the training error of this AdaBoost? Give a short explanation for why AdaBoost outperforms a single decision stump.

Table 1: Values of AdaBoost parameters at each timestep.

Figure 1: A small dataset for binary classification with AdaBoost.

3. Random forest and one-class SVM for email spam classifier (30 points)

(a) (5 points) Build a CART model and visualize the fitted classification tree.

(b) (5 points) Now, also build a random forest model. Randomly shuffle the data and partition to use 80% for training and the remaining 20% for testing. Compare and report the test error for your classification tree and random forest models on testing data. Plot the curve of test error (total misclassification error rate) versus the number of trees for the random forest, and plot the test error for the CART model (which should be a constant with respect to the number of trees).

(c) (10 points) Fit a series of random-forest classifiers to the data to explore the sensitivity to the parameter ν (the number of variables selected at random to split). Plot both the OOB error as well as the test error against a suitably chosen range of values for ν.

(d) (10 points) Now, we will use a one-class SVM approach for spam filtering. Randomly shuffle the data and partition to use 80% for training and the remaining 20% for testing. Extract all non-spam emails from the training block (80% of data you have selected) to build the one-class kernel SVM using RBF kernel (you can turn the kernel bandwidth to achieve good performance). Then apply it to the 20% of data reserved for testing (thus, this is a novelty detection situation), and report the total misclassification error rate on these testing data.

4. Locally weighted linear regression and bias-variance tradeoff. (30 points)

Consider a dataset with n data points (xi,yi), xi ∈Rp, following the following linear model

yi = β∗Txi + ϵi, i = 1,…,n,

where ϵi ∼N(0,σ2) are i.i.d. Gaussian noise with zero mean and variance σ2.

(a) (5 points) Show that the ridge regression, which introduces a squared ℓ2 norm penalty on the parameter in the maximum likelihood estimate of β can be written as follows

βˆ(λ) = argmin

for property defined matrix X and vector y.

(b) (5 points) Find the close-form solution for ) and its distribution conditioning on {xi}.

(c) (5 points) Derive the bias as a function of λ and some fixed test point x.

(d) (5 points) Derive the variance term as a function of λ.

(e) (5 points) Now assuming the data are one-dimensional, the training dataset consists of two samples x1 = 0.15 and x2 = 1.1, and the test sample x = 1. The true parameter = 1, the noise variance is given by σ2 = 0.5. Plot the MSE (Bias square plus variance) as a function of the regularization parameter λ.

(f) (5 points) Now change the test sample to be a x = 1.5, and keep everything else to be the same as in the previous question. Plot the MSE (Bias square plus variance) as a function of the regularization parameter λ, and comment on the difference from the previous result.
