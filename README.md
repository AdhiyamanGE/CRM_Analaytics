
1.Customer Identification & Segmentation:
->Dataset taken from kaggle is used.

attributes : InvoiceNO,StockCode,Description,Quantity,InvoiceDate,UnitPrice,CustomerID,Country.

![data](https://github.com/AdhiyamanGE/CRM_Analaytics/assets/54020582/c989b0a7-6ce9-491b-9490-56b07360e2a2)

->RFM metric is calculated.
RECENCY : How recently a customer has made a transaction.
FREQUENCY : How frequently a customer had transactions.
MONETARY : Total amount spent by the customer

![RFM](https://github.com/AdhiyamanGE/CRM_Analaytics/assets/54020582/e10759c1-1f58-499f-b6c1-77d802c2d9bc)

->Using K-means algorithm,Clusters are formed based on the rfm metric computed above.
->These clusters can be interpreted by analysts to segment the customers in different categories and allocate different buisness strategies for each segment.

![Recency V Frequency](https://github.com/AdhiyamanGE/CRM_Analaytics/assets/54020582/80a46fb5-88cc-4b53-aec9-90bbbbd559b1)


2.Customer Retention:

->RFM values are given as input to the BG/NBD Model to predict the number of transactions a customer will make in N period of time.
![Expected_no of_Transactions](https://github.com/AdhiyamanGE/CRM_Analaytics/assets/54020582/db0c4ba5-9d78-473d-98ef-8609391b7b3e)

->Probability of being alive (i.e) make transactions over time for each customer is computed from BG/NBD MODEL.
![Probability_of_being_alive](https://github.com/AdhiyamanGE/CRM_Analaytics/assets/54020582/9e204c1e-128d-401d-b4ad-d050800d7cb3)
