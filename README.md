# Bank-Marketing-Dataset


Find the best strategies to improve for the next marketing campaign. How can the financial institution have greater effectiveness for future marketing campaigns? To answer this, we have to analyse the bank's last marketing campaign and identify the patterns that will help us find conclusions to develop future strategies.


Feature/column description

1. Bank client data:
* age (numeric)
* job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
* marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
* education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
* default: has credit in default? (categorical: 'no','yes','unknown')
* balance: bank balance
* housing: has housing loan? (categorical: 'no','yes','unknown')
* loan: has personal loan? (categorical: 'no','yes','unknown')

2. Related with the last contact of the current campaign:
* contact: contact communication type (categorical: 'cellular','telephone')
* month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
* day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
* duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

3. Other attributes:
* campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
* pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
* previous: number of contacts performed before this campaign and for this client (numeric)
* poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

4. Output variable (desired target):
* deposit - has the client subscribed a term deposit? (binary: 'yes','no')



RESULTS

[](https://github.com/TheAnuska/Bank-Marketing-Dataset/blob/master/Figures/corr_matrix.png)

Figure 1 Correlation matrix. I took the all data set, where I changed the categorical features into numerical to see specific correlations that should be included or excluded.  

[](https://github.com/TheAnuska/Bank-Marketing-Dataset/blob/master/Figures/ML_models.png)

Figure 2 The results of using different machine learning techniques.  



