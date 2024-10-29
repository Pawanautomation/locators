Exercises on Amazon
Exercise 1: Product Search Results
Task: Search for “laptop” and locate the title of the second product in the search results.
Complexity: Medium
Hint: Use position-based XPaths, like locating a parent container for search results and navigating to the second item.
Exercise 2: Filter by Customer Ratings
Task: Select the 4-star and up filter in the left sidebar.
Complexity: Medium
Hint: Find this filter by text with partial matching or CSS selectors. Amazon uses lots of classes that may change, so relative paths are beneficial here.
Exercise 3: Product Price in Search Results
Task: Retrieve the price of the third item in the search results for “smartphones.”
Complexity: High
Hint: Price elements might be within multiple divs, so use parent-child and sibling relationships.
Exercise 4: Add to Cart Button on Product Page
Task: After clicking a specific product, locate and interact with the "Add to Cart" button.
Complexity: High
Hint: The "Add to Cart" button might change position depending on stock or offers, so create a locator that accounts for variations in structure.
Exercise 5: Deal of the Day Section
Task: Identify the main title and price of any “Deal of the Day” item on the homepage.
Complexity: High
Hint: This section might only appear at certain times, and its structure varies. Look for consistent identifiers or create locators based on position if unique attributes are missing.

Middle-Level Exercises:

Identify the Search Bar:

Find the input element with the id attribute.
Use a CSS selector targeting the input element within the search bar's container.
Create an XPath expression to locate the search bar by its position or unique attributes.
Locate the "Sign In" Button:

Find the a element with the appropriate href attribute.
Use a CSS selector to target the button based on its class name or other attributes.
Create an XPath expression to locate the button by its text content or surrounding elements.
Select a Specific Product:

Identify the product's unique identifier (e.g., product ID or ASIN).
Use a CSS selector to target the product's container and extract the necessary information.
Create an XPath expression to locate the product based on its position or specific attributes.
Complex Exercises:

Handle Dynamic Content:

Use relative XPath expressions to locate elements based on their position relative to other elements.
Employ JavaScript execution to interact with elements that are dynamically loaded or hidden.
Consider using a waiting mechanism (e.g., explicit or implicit waits) to ensure elements are loaded before attempting to interact with them.
Simulate User Behavior:

Add products to the cart.
Proceed to checkout.
Apply a coupon code.
Select a shipping address.
Choose a payment method.
Complete the purchase.
Handle Pop-ups and Alerts:

Switch to the appropriate window or frame.
Identify and interact with elements within the pop-up or alert.
Handle different types of alerts (e.g., JavaScript alerts, browser alerts).