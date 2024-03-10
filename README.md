Risk Analyst test - Cloudwalk
Candidate: Vinícius S. Brandão
2. Tasks

2.1. Understand the Industry
Explain briefly the money flow, the information flow and the role of the main players in
the payment industry.

Initial considerations:
 It is important to state the kind of payment being analyzed. There are multiple possible payment methods, ranging from cash and crypto to contactless and  SWIFT payments, and each of these methods have different players and work differently, so the card payment methods were chosen to be studied, since they allow for chargebacks, the main focus of this test.

The information Flow and main players:
	The money flows from one actor to the other, so we have to identify the actors and have their roles explained. The actors are listed in the information flow order, and the explanation will be done following the steps a transaction would normally take, assuming that the card holders start from the point at which they already have the card at their disposal.  
(note: the issuing bank is the buyer/cardholder’s and the acquiring bank is the seller/merchant’s)

Cardholder and Merchant:
 The cardholder in conjunction with the merchant initiate the transaction that intends to  ask the bank for a payment from the cardholder to the merchant. The merchant's payment processing system or software communicates the transaction details to the payment gateway.

Payment Gateway
The payment gateway securely transmits this information to the payment processor or acquiring bank.


Payment Processor (the acquiring bank can also be the payment processor):
	The processor captures the transaction information and sends it to the cardholder's card network so the issuing bank can approve the transaction.

Payment network

Transaction information for credit cards is routed between issuing and acquiring banks through the respective payment networks. Each major payment network (e.g. visa and mastercard), operates its own network to facilitate this process. The transaction details are handed to the issuing bank to await for its approval.

Issuing Bank

The issuer approves or declines the transaction after verifying the cardholder's available balance and if the transaction is valid. Handling back to the approval status to the payment network.

Payment Processors
The payment processor will handle back the approval status to the acquiring bank or directly to the merchant.

Acquiring Bank:
Upon receiving transaction details from the payment processor, the acquiring bank verifies the information before forwarding it to the payment network for authorization. Upon authorization, the bank settles  funds with the merchant.

Merchant
	The merchant receives the approval status, the cardholder and merchant now have finished their transaction. 

Moneyflow

In the transaction process, the money flows from the cardholder to the merchant via a series of intermediaries. Thus fees are incurred at various points: merchants pay interchange (fees paid by a merchant's bank to a cardholder's bank) and the payment network fees, while cardholders may face interest or annual fees from the issuing bank, and the payment processor may charge a processing fee.



Explain the main differences between acquirer, sub-acquirer and payment gateway, and how the flow explained in the previous question changes for these players.

Acquirer is an institution that has the network that can handle the transaction  processing for the merchant, i.e. the network that receives the transaction requisitions from the card machines to then communicate with the card networks(e.g. visa and mastercard). So the acquirer is responsible to get the information to and from the merchant, getting the request and returning the response. Acquirers are also responsible for managing the risk associated with transactions, including fraud prevention and chargeback management.

An illustration of who an acquirer could be, is an organization that issues card payment machines (but not necessarily) and handles the processing of the requested transactions generated by it.

Sub-Acquirer
The sub-acquirers are platforms that provide a service that intermediates the transactions between the merchant and the other parties, being a payment aggregator, offering a complete experience to the buyers and merchants. It often comes to provide more convenience to the buyers and sellers, that might bring an easier payment experience, and generally provides more flexibility and services than a regular acquirer, such as an independent anti-fraud, payment insurance, etc, but this usually comes at the cost of a higher transaction fee to the merchants.

Payment gateway
	Payment gateways serve as intermediaries between merchants (sellers) and acquirers, facilitating online transactions by securely transmitting payment information between the merchant's website and the payment processor (acquirer). They often provide additional services such as fraud prevention, currency conversion, and recurring billing. While payment gateways simplify the process of accepting payments for sellers, they typically charge transaction fees for their services.

offer many services on top of interfacing the payment with the necessary parties with the 

 Explain what chargebacks are, how they differ from a cancellation and what is their
connection with fraud in the acquiring world.
	
A chargeback aims to retrieve money from fraudulent or unauthorized transactions and receiving faulty or undelivered goods or services from the bad actor back to the person who paid for said goods or services but they themselves can be the vector for fraud in the form of false claims on chargeback disputes.

The chargeback flows in the following order:
Cardholder disputes the transaction with the issuing bank, which decides on chargeback eligibility.
If the chargeback is granted, the issuing bank notifies the acquiring bank, and the acquiring bank issues the merchant and withholds the merchant's disputed amount.
The merchant can accept the chargeback or initiate representment by disputing the charge with evidence.
Issuing bank reviews evidence; if it favors the merchant, the funds are no longer withheld.
Parties can initiate pre-arbitration if unhappy with the decision, typically due to new evidence.
If there is no resolution in pre-arbitration, chargeback proceeds to arbitration.
Card network examines evidence, takes a final decision that has no further appeal.
The losing party in arbitration pays the arbitration fees.

A cancellation happens when a transaction is voided or nullified before it’s completion or fulfillment, not warranting any disputes, and the chargeback happens after the transaction is complete, thus warranting the whole process described above.
2.2. Solve the problem
A client sends you an email asking for a chargeback status. You check the system, and see that
we have received his defense documents and sent them to the issuer, but the issuer has not
accepted our defense. They claim that the cardholder continued to affirm that she did not
receive the product, and our documents were not sufficient to prove otherwise.
You respond to our client informing that the issuer denied the defense, and the next day he
emails you back, extremely angry and disappointed, claiming the product was delivered and that this chargeback is not right.

Considering that the chargeback reason is “Product/Service not provided”, what would you do in
this situation?

The first considerations I would have to make are with regards to the context. It lets us know that this product had to be shipped, the responsibility of delivering the product to the cardholder was our client’s.

The documents already present in the dispute are the necessary following  considerations, since the defense was not accepted, at this point (if it had not been done earlier) the sent documentation has to be analyzed to understand what is the actual situation and if there is something that was not noticed during the process.

Shipping documentation and our client’s product registry or inventory are the first documents that come to mind.They alone could be enough to prove our client right or wrong. If the product registry and shipping documentation indicate that the product was sent but is still in transit, this could prove the client's claim. However, if the product was sent but the shipping documentation shows that it was lost in transit, this would disprove the client's claim. Since the client is responsible for delivering the product, in this scenario his claim on the chargeback would be disproved and accepting the chargeback and proceeding to resolve the issue with the shipping carrier would be advisable.
(There could be other documentation or arguments such as “the product is in production” or “supply issues”, but I will not go beyond mentioning that these are plausible situations because this kind of situation would be far too complex to be explored here.)


Wrapping up:
After asking if the client has talked to his customer about this issue, and if not, advise him to try explaining why the cardholder’s claim might be wrong or unfounded, and orient him to offer a solution or settlement. If this fails, proceed to examine the available documentation and verify our client’s claim. At this point, three paths could be followed:


Advising the client to accept the chargeback if the evidence suggests they are responsible for the issue. communicating with the client empathetically, acknowledging their frustration, but emphasizing the importance of accepting responsibility if warranted. Offering support in resolving any pending issues related to the chargeback and providing guidance on preventing similar incidents in the future.

Asking for more clear evidence if the client's claims are not adequately supported. Communicating with the client to explain the deficiencies in their current documentation and provide clear instructions on what additional evidence is needed. Offering assistance to help him gather the required information and emphasize the importance of presenting a strong case in the dispute process.

Encouraging the client to proceed with the dispute if their documentation sufficiently supports his case. If the evidence strongly supports his position, reassure him on the strength of his case and provide guidance on next steps in the dispute process. Show him support throughout the process and offer assistance in any further documentation or communication with the issuer if necessary.





The next part is extracted from the conclusion section present in the python notebook used for developing the anti-faud system for question 3.4. It contains  a deep analysis on the data provided for study and an extensive explanation on the process and rationale used for the development of the neural network and rules put in place for fraud detection.

The notebook can be found here: https://github.com/TeuPremium/Fraud_test
It is named as “index.ipny” in the repository

3. Get your hands dirty
1. Analyze the data provided and present your conclusions. What suspicious behaviors did you find? What led you to this conclusion? What actions would you take?

    	The data analysis leads us to believe that transactions happening between 4pm and 6 am are the most likely to be fraudulent when combined with a large transaction amount (larger than 2000), as well as multiple (surpassing 10) transactions on the same device or by the same user. This was explored in the Data section by studying the graphs and tables that presented a larger frequency of fraud when these factors were present. The actions that could be taken were tackled in the Realistic Use section where these factors were used as parameters to approve or reject a transaction.

2.  In addition to the spreadsheet data, what other data would you consider to find patterns of possible fraudulent behavior?

   	 Location data holds significant value in fraud detection, as it can be cross-referenced with historical location data to identify suspicious activities. Establishing a comprehensive historical context for each user, particularly when users are identified by card or device ID, is also useful. Without sufficient transactional context attributed to each user, there may be limitations in gathering transactional data, hindering our ability to establish a comparative framework for identifying normal transactions associated with each card.

3. Considering your conclusions, what would you further suggest in order to prevent frauds and/or chargebacks?

   	 Considering this, it would be prudent to establish some rules to limit the ability that bad actor have to practice fraud, such as the ones established in the real Realistic Use section in the detect_spam and detect_large_amount_scam functions, so limit transactions that surpass a certain threshold and limit the amount of transactions one can make in a certain period of time. (read commented code to understand the reasoning behind the parameters chosen) 

4. Create a simple anti-fraud.

    This notebook was mostly dedicated to solve this, more details can be found on Detection Models and Realistic Use sections, where you find most of the explanation of how the anti-fraud was developed. And a comprehensive example of the anti-fraud system working can be found at the Testing Implementation section. 
Sources: 
Cardfellow - How Credit Card Processing Works: Understanding Payment Processing
VTEX - What is the role of financial agents in the payment flow of an application in Brazil? | VTEX Help Center
Chargeback Gurus - What is a Chargeback?
Text revision:
Chat GPT - https://chat.openai.com/
