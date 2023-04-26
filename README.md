# smart-contract-for-Retail
Mini-projcet about building a smart contract for Retail
Based on IERC_20 standard.


# This contract has the following functions,
1. Buyer Registration: A user can register by generating the profile with their name, email, and shipping
address. Only one profile can be registered per address. Once registered, the buyer can view their own
profile information.
2. Seller Registration: Only one address can register as the seller by depositing a certain amount of
cryptocurrency (Ethereum coins), and the seller address is not allowed to be a buyer. Once registered,
the seller can add products for sale with a name, price, and inventory. Only the seller address is allowed
to add product information.
3. Product Information: Anyone can input the product id and view the corresponding product information,
including the name, price, and inventory.
4. Transaction Initiation: A user can initiate a new transaction by specifying the product ID and quantity.
The total cost of the transaction is calculated based on the selected product price. The buyer should hold
enough money and transfer it to the smart contract to proceed with the transaction.
5. Transaction Information: A user can only view his/her own transactions, while the seller can view all.
(Note that you need to think about what attributes are needed to achieve the requirements, as they are
not explicitly specified here.)
6. Return Request: A buyer can request a return before completing the transaction. The seller can get the
transaction information to see the transaction status and approve a return upon request. Once a return
is approved, the money contained in the transaction should be transferred back to the buyer.
7. Transaction Completion: The buyer can mark a transaction as completed. Once a transaction is completed,
the total cost of the transaction should be transferred to the seller’s account. Also, no other modifications
or actions can be done except viewing the transaction information.
8. Profile Update: Provide a way that enables a buyer to update/edit their own profile information.
9. Product Review: Provide a way that enables the buyer to rate the purchased product by a numeric scale
of 0-5 (5/0 means very satisfied/not satisfied at all).
10. Multi-Product Purchase: Provide a way that enables a buyer to buy a list of products in one transaction.


# This is the flow chart of the contract,
![image](https://user-images.githubusercontent.com/117359375/234561396-984f8b60-1220-4ae8-9b4e-bf9564c3a7e9.png)

