# cse643-ai-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CSE643 AI ASSIGNMENT 4 Solved](https://www.ankitcodinghub.com/product/cse643-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127115&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE643  AI ASSIGNMENT 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Instructions:

1. Assignments are to be attempted individually.

2. Submit the assignment in a zipped file with name AI4 ⟨StudentName⟩ and contents including AI4 StudentName Result.pdf and ⟨StudentName⟩ gradient.py and the computational question as ⟨StudentName⟩ linear regression.py, and

⟨StudentName⟩ logistic regression.py depending on which question you solve.

3. STDOUT / python print outputs will be considered for evaluation.

5. Programming Language : Python

6. Use classes, functions etc. in your code in ways that make sense.

7. Extension and Penalty clause:

• A penalty will be incurred if the submissions are late.

Expanded equation form:

y = w1 ∗ x1 + w2 ∗ x2 + w3 ∗ x3 + w4 ∗ x4 + w5 ∗ x5 + b

Vector form:

w y = w⊤x + b

Here, w are the weights and b is the offset. Mean Squared Error:

Here {(x(i),y(i));i = 1,2,…,N} are the labeled data samples available for the optimization. are the predictions from the linear regression model.

Submit the derivation of the gradients for the above 5-dimensional example, both in the expanded equation form as well as the vector form.

X = np. arange(−20, 20 , 0.1) np. random . shuffle (X)

eps = np. random . rand (400) ∗ 10 y = 23∗X + 43 + eps

EXAMPLE OUTPUT STDOUT: w = 23, b = 47

Please use the same notation in your python code’s print statement. Evaluation will take running time into account.

Environment Setup: pip install ucimlrepo pandas scikit-learn

By popular demand, it has been decided that only one of the following questions needs to be answered to complete the assignment. Please choose either Linear regression or Logistic regression and submit the filenames accordingly. Thanks.

(a) Reference: Regression using continuous variables can be applied directly. Categorical variables, on the other hand, need some processing before they are used in regression. Look into the different approaches used here and implement your choice(s) by analyzing the data: https://stats.oarc.ucla.edu/spss/faq/coding-systems-for-categoricalvariables-in-regression-analysis-2/. Typically, one-hot encoding gives independence between the regression weights for the categories and assumes an independence between the categories that might not be useful and hence there are other ways people have come up with.

(b) Dataset: Abalone (https://archive.ics.uci.edu/dataset/1/abalone) – use python to download the data instead of the web interface.

(c) Accuracy: R2 score

(d) Target variable: Rings (integer)

Look into this for some context on the r2 metric:

scikit-learn documentation:https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2s Examples: https://www.ncl.ac.uk/webtemplate/ask-assets/external/maths-resources/statistics/r and-correlation/coefficient-of-determination-r-squared.html.

(g) Submission Format: ⟨StudentName⟩ linear regression.py

• R2 score over entire dataset: R2 =0.537 minimum; R2 =0.56+

• R2 score over 15% test dataset: mean R2 score and standard deviation over 15% test dataset

• The assessment will be automatic. Please use the EXACT STRINGS as shown in the example output

• The only outputs needed are the performance metric numbers changed according to your results.

(h) Example Output STDOUT:

Full dataset train and eval R2 score: 0.54

70-15-15 Cross validation boxplot: mean=0.51, std=0.04

(j) HINT: You can try to use non-linear transformations of the data for performance ablations.

(a) Reference: This question contains data with missing values. Here is a reference you can use for common strategies employed in regression datasets with missing values: http://www.stat.columbia.edu/ gelman/arm/missing.pdf. Consider using matching, mean value + random noise or more feature-specific random imputations of a single variable in your free time. For now, you can assign an UNKNOWN label to all missing values and try to approximate the results anyway. Note: Logistic regression uses LBFGS in the backend.

(b) Dataset: Adult (https://archive.ics.uci.edu/dataset/2/adult) – use python to download the data instead of the web interface.

(c) Accuracy: Classification score

(d) Target variable: income (binary)

(g) Submission Format: ⟨StudentName⟩ logistic regression.py

• accuracy score over entire dataset: full accuracy: 0.80 ; train accuracy=0.79 ; test accuracy=0.78

• accuracy score over 15% test dataset: mean accuracy score and standard deviation over 15% test dataset

• The assessment will be automatic. Please use the EXACT STRINGS as shown in the example output • The only outputs needed are the performance metric numbers changed according to your results.

(h) Example Output STDOUT:

Full dataset accuracy: full: 0.80, train: 0.79, test: 0.78

70-15-15 Cross validation boxplot: mean=0.74, std=0.08

END
