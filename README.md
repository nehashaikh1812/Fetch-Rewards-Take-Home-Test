# Fetch-Rewards-Take-Home-Test
Solutions of the Fetch Rewards Take Home Test



First: Review Existing Unstructured Data and Diagram a New Structured Relational Data Model

Refer to the file: Final ER Diagram.png

For the sake of simplicity and exclusivity, I have changed the names of '_id' field for Receipts, Users, and Brands schema to 'receipt_id', 'user_id' and 'brand_id' respectively.




Second: Write a query that directly answers a predetermined question from a business stakeholder

Refer to the file: SQL Queries.pdf




Third: Evaluate Data Quality Issues in the Data Provided (please refer individual PDFs for detailed explanantion of the issues)

I have conducted Exploratory Data Analysis on Reciepts, Users and Brands data using Python, via JupterLab.
Refer to files: Data Quality Issues Receipts.pdf, Data Quality Issues Users.pdf, and Data Quality Issues Brands.pdf (PDF versions of Jupyter NoteBooks)

Major data quality issues found:
1. 'Receipts' data(Data Quality Issues Receipts.pdf): 

        a) Considerate amount of values missing in 'finishedDate', 'pointsEarned', 'purchasedItemCount', 'totalSpent', 'rewardsReceiptItemList' columns.
        
        b) Large number of outliers in values of 'pointsEarned', 'purchasedItemCount', 'totalSpent' columns. The distribution curves for values of these features is skewed. We do not know at this point whether these outliers are legit values or a result of some errors/inconsistency in processes that produce these values.
      
2. 'Users' data(Data Quality Issues Users.pdf): More than half of the records are duplicate.

3. 'Brands' data(Data Quality Issues Brands.pdf): Considerate fraction of values missing for 'topBrand' and 'categoryCode' columns.




Fourth: Communicate with Stakeholders

Refer file: email.pdf
