# Default Classification of customer

#### a word, need to find
- revolving
- Delinquencies
- collection
- tax_liens
- FICO
#### feature selection with background

- int_rate : Interest rate of the loan that applicant received 
- dti : Debt to income ratio
- delinq_2yrs : Delinquencies on lines of credit in the last 2 years
- pub_rec : Number of bankruptcies listed in the public record
- revol_bal : Total credit revolving balance
- collections_12_mths_ex_med : Numbers of collections in the last 12 months which excludes medical collections
- tot_cur_bal - ((funded_amnt+funded_amnt_inv) - (out_prncp+out_prncp_inv))
- > Funded amount which exceed total current balance of all accounts
- delinq_amnt/(funded_amnt+funded_amnt_inv) : ratio of delinquency amount over total fund
- emp_length1~12 : Number of years in the job
- initial_list_status : Initial listing status of the loan
- revol_util : Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit
- 
