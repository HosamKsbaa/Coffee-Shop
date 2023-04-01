# Coffee-Shop
Write a **class** called **CoffeeShop**, which has **three instance variables**:

1.  **name** : a string (basically, of the shop)
2.  **menu** : an array of items (of type MenuItem), with each item containing the **item** (name of the item), **type** (whether a *food* or a *drink*) and **price**.
3.  **orders** : an empty array

and **seven methods**:

1.  **addOrder**: adds the **name** of the item to the end of the **orders** array if it exists on the **menu**. Otherwise, return `"This item is currently unavailable!"`
2.  **fulfillOrder**: if the **orders** array is **not empty**, return `"The {item} is ready!"`. If the **orders** array is empty, return `"All orders have been fulfilled!"`
3.  **listOrders**: returns the list of **orders** taken, otherwise, an **empty** array.
4.  **dueAmount**: returns the total amount due for the **orders** taken.
5.  **cheapestItem**: returns the **name** of the cheapest item on the menu.
6.  **drinksOnly**: returns only the *item* **names** of *type* **drink** from the menu.
7.  **foodOnly**: returns only the *item* **names** of *type* **food** from the menu.

**IMPORTANT**: Orders are fulfilled in a **FIFO** (first-in, first-out) order.
