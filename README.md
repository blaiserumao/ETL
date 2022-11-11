# ETL
Task One: Building an ETL pipeline to support our Applied Data Scientists\
Transforming the raw data into the features.\
Data files:\
•	accounts.csv: Contains account information for our customers.\
•	skus.csv: Contains the details about our product lines.\
•	invoices.csv: Contains the invoices issued to each account.\
•	invoice_line_items.csv: Contains the details of the SKUs sold on each invoice.\

Required features in the output file:\
•	inv_id: the ID of the invoice to be passed into the model.\
•	acct_id: the ID of the account for that invoice.\
•	inv_total: Total value (in dollars) for the invoice.\
•	inv_items: Total number of items in the invoice.\
•	acct_age: The age of the account (in days) at the time the invoice was issued (i.e. the number of days between when the account was set up, and the invoice date).\
•	num_inv_120d: the number of invoices for the account in the 120 days prior to the invoice's issuing date.\
•	cum_tot_inv_acct: The cumulative number of invoices for the account up to date that the invoice was issued.\
•	is_late: A flag to indicate if the invoice was paid late (i.e. more than 30 days after issuing). Contains 1 if invoice was paid late, 0 otherwise.\

Task Two: Creating a dashboard to visualize features at different times.\
