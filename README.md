# Bank-Marketing-using-ML

# Problem Statement 

The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

 In this project, you need to build a model for deciding whether a campaign will be successful in getting a client to sign up for the term deposits.
 
# Dataset Description:

**Bank client data**

**1**. age (numeric)

**2**.job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self

**3**.employed','services','student','technician','unemployed','unknown')

**4**.marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

**5**.education: (categorical "unknown","secondary","primary","tertiary")

**6**.default: has credit in default? (binary: "yes","no")

**7**.balance: average yearly balance, in euros (numeric) 

**8**.housing: has housing loan? (binary: "yes","no")

**9**.loan: has personal loan? (binary: "yes","no")
 

# Data related to the last contact of the current campaign

**1**.contact: contact communication type (categorical: "unknown","telephone","cellular") 
**2**.day: last contact day of the month (numeric)
**3**.month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
**4**.duration: last contact duration, in seconds (numeric)
 

# Other attributes:

**1**.campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

**2**.pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)

**3**.previous: number of contacts performed before this campaign and for this client (numeric)

**4**.poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
 

# Output variable (desired target):

**y: has the client subscribed a term deposit? (binary: "yes","no")**
 

Objectives:

You are required to prepare a well-commented an interactive python notebook as your solution to this problem statement. The notebook must meet the following objectives:

Clean the data and drop useless columns.

Make an EDA report, i.e., perform a univariate and bivariate analysis. Also, derive new features based on the given features, remove outliers and correlated variables if necessary.

Visualize the distributions of various features and correlations between them.

Perform feature engineering to extract the correct features for the model.

Build a logistic regression model

Evaluate the model used.
