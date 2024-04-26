# Catalog
 Welcome to your first project.  Develop a catalog for a company. Assume that this company sells three different Items. The seller can sell individual items or a combination of any two items. A gift pack is a special combination that contains all three items. Here are some special considerations:  

A. If a customer purchases individual items, he does not receive any discount.  
B. If a customer purchases a combo pack with two unique items, he gets a 10% discount.  
C. If the customer purchases a gift pack, he gets a 25% discount. 

Write a function for the above scenario. Perform the calculations in code wherever applicable.  The function should be your own creation,  The final output should look like
![image](https://github.com/Rndongala/Catalog/assets/68242091/10446a0f-aec9-47d0-b8fa-c5842e4357ea)

Instruction
* The code for the function that created
* The out of the code
* A description of what features the function illustrates
* The code and its output.
  
Input:

def catalog():
# Prices of individual items

     Item1_price = 200.0
     Item2_price = 400.0
     Item3_price = 600.0
     
# Calculate the combo prices with (two unique items with 10% discount)

     Combo1_price = item1_price + item2_price - 0.1 * (item1_price + item2_price)
     Combo2_price = item2_price + item2_price - 0.1 * (item1_price +  item2_price)
     Combo3_price = item1_price + item2_price - 0.1 * (item1_price + item2_price)
     
# Calculate the price for the gift pack of (all the three items with 25% discount)

Gift_pack_price = item1_price + item2_price + item3_price - 0.25 * (item1_price +             item2_price + item3_price)
     print(“Online Store”)
     print(“------------------------------“)
     print(“Product(s)				Price”)
     print(f” Item 1				{item_price}”)
     print(f” Item 2				{item_price}”)
     print(f” Item 3				{item_price}”)
     print(f”combo 1 (Item 1 + 2)		{combo1_price}”)
     print(f”combo 2 (Item 1 + 2)		{combo2_price}”)
     print(f”combo 3 (Item 1 + 2)		{combo3_price}”)
     print(f”combo 4 (Item 1 + 2 + 3)		{gift_pack_price}”)
     print(“------------------------------“)
     print(“For delivery contact : 98764678899”)
catalog()

Output:
-----------------------------
Product(s)				Price
Item 1					200.0
Item 2					400.0
Item 3					600.0
Combo 1 (Item 1 + 2)			540.0
Combo 1 (Item 2 + 3)			900.0
Combo 1 (Item 1 + 3)			720.0
Combo 1 (Item 1 + 2+ 3)		900.0
-----------------------------
For delivery contact : 98764678899
The function illustrates the feature of creating a catalog for a company that sells multiple items. It demonstrates how to implement pricing logic based on different purchasing scenarios, such as discounts and gifts packs. Additionally, the function showcases the flexibility to calculate prices based on specific discount percentages provided for each type of purchase. 
The catalog function takes a list of items as an input.
The item1_price, item2_price, item3_price as a variable that holds the 200.0, 400.0, 600.0 as value.
Prices for individual prices items are printed first.
Prices for combo packs are calculated using ‘catalog’ function with 10% discount and printed.
The price of the gift pack is calculated similarly with 25% discount and printed.


