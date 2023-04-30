<div id="header" align="center">
    <h1>Credit scoring (determining the probability of default)</h1>
</div>

<div id="picture" align="center"
    <a href="https://github.com/dmitps/default-probability-home-credit/blob/main/images/Home%20Credit%20Default%20Risk.png">
        <img src="https://github.com/dmitps/default-probability-home-credit/blob/main/images/Home%20Credit%20Default%20Risk.png">
    </a>
</div>

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

____

This study was conducted on the basis of data from the Kaggle competition "Home Credit Default Risk", the purpose of which is to use historical data on loan applications and other information to predict whether the applicant will be able to repay the loan (to determine the risk of default of the borrower).

The competition looks like a standard classification task (1 in the TARGET field means any difficulties with payments, 0 — no difficulties). However, it is not 0/1 that should be predicted, but the probability of problems.

Metric: ROC AUC

____

### Dataset Description

