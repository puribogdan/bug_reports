# bug_reports
In this repository are some bug reports I wrote, imported from Jira
#
**Title:**
**The search functionality consistently returns an internal error**

**Description:**

The search functionality consistently returns an internal error when attempting to search for products using various keywords.

**Steps to Reproduce:**


1. Navigate to the OpenCart demo website: https://demo.opencart.com/
2. In the website's search bar, enter any keyword (e.g., "shoes").
3. Click the magnifying glass search button.


**Expected Behavior:**

The search results should display a list of relevant products matching the entered keyword(s).

**Actual Behavior:**

Instead of displaying search results, an error message is shown: 
"Internal Server Error!
There has been a problem loading the page you are looking for. We are working hard to resolve the issue and the page should return shortly.
If the problem persists please use the contact us form for help."

**Additional Information:**

This issue occurs consistently and is not dependent on the chosen keyword(s).

The error persists even after refreshing the page or attempting the search at different times.

**Reproducibility:** Consistently reproducible.

**Priority:** P1

**Severity:** Critical 
![500-INTERNAL-ERROR](https://github.com/puribogdan/bug_reports/assets/50368261/8bf9bdaa-7aef-4f93-9d02-526aee0352bc)

**Title: Add to Cart Button Issue**

**Description:**

When attempting to add an item to the cart from a product page, clicking the "Add to Cart" button does not result in the item being added to the cart. 

**Steps to Reproduce:**

1. Navigate to the OpenCart demo website: https://demo.opencart.com/
2. On the website's homepage, on the bottom left side, click on the product with the name “Macbook”
3. On the product page click the "Add to Cart" button.
 

**Expected Behavior:**

Upon clicking the "Add to Cart" button, the selected item should be added to the shopping cart, and the cart icon or count should update to reflect the addition.

**Actual Behavior:**

A message pops up saying “Success: You have added MacBook to your shopping cart!” but
the "Add to Cart" button does not add the item to the cart. The cart icon or count remains unchanged.

**Additional Information:**

This issue occurs consistently on multiple product pages.

**Reproducibility:** Consistently reproducible.

**Priority:** P2

**Severity:** Critical

![MacBook](https://github.com/puribogdan/bug_reports/assets/50368261/6e5abfe8-1525-4a75-b131-3fead082e7ae)

**Title:**
**Registration Failure**

**Description:**

When attempting to create a new user account on the e-commerce app, the registration process fails to complete successfully. After entering all the required information and clicking the "Register" button, nothing happens, and the account is not created.

**Steps to Reproduce:**


1. Navigate to the OpenCart demo website: https://demo.opencart.com/
2. Click on “my account” and then “register”
3. Fill in the registration form with valid information, including: First name, Last name, Email Address, Password
4. Tick the “I have read and agree to the Privacy Policy” box
5. Click the "Continue" button to submit the registration form.**


**Expected Behavior:**

Upon clicking the "Register" button, the e-commerce app should:

Validate the entered data, checking for any errors or incomplete fields.

If the data is valid, it should create a new user account and redirect the user to a confirmation page or automatically log them in.

**Actual Behavior:**

After clicking the "Register" button, nothing happens. There is no error message displayed, and the user is not redirected to a confirmation page. The account is not created, and no confirmation email is received.

**Reproducibility:** Consistently reproducible.

**Priority:** P2

**Severity:** Critical 

![Register-Account](https://github.com/puribogdan/bug_reports/assets/50368261/7d01f133-193e-4096-8021-7dbd76bc14fb)

**Title:**
**Currency Conversion Issue**

**Description:**

When attempting to change the currency in the e-commerce app mystore-testlab.coderslab.pl , the website switches the currency symbol (e.g., from dollar ($) to euro (€)) but does not perform the actual currency conversion, resulting in incorrect pricing.

**Steps to Reproduce:**


1. Navigate to  https://mystore-testlab.coderslab.pl/
2. Click on the “USD$” text link located on top-right part of the page
3. Change the currency from the default currency (e.g., USD) to another currency (e.g., EUR).
4. Observe the product prices displayed on the website.


**Expected Behavior:**

When changing the currency setting, the e-commerce app should:

Update the currency symbol throughout the website to reflect the chosen currency (e.g., change from "$" to "€").

Convert all product prices to the real value of the selected currency, based on current exchange rates.

Display product prices in the selected currency, with accurate conversions.

**Actual Behavior:**

After changing the currency setting, the e-commerce app successfully changes the currency symbol (e.g., from "$" to "€") but does not convert the product prices to the real value of the selected currency. All product prices remain the same as in the default currency, resulting in incorrect pricing for users who select a different currency.

**Reproducibility:** Consistently reproducible.

**Priority:** P3

**Severity:** High

![euro](https://github.com/puribogdan/bug_reports/assets/50368261/eb70d6f9-bc61-4762-ab3e-54fa6323c9f7)
![usd](https://github.com/puribogdan/bug_reports/assets/50368261/79feb1bf-b734-4af1-bda0-381d4d214fc5)


**Title:**
**Sorting Function Issue**

**Description:**

While browsing the product catalogue on the e-commerce website, I encountered an issue when attempting to use the sorting function to arrange products by price. Specifically, when I selected the "Sort by Price: High to Low" or "Sort by Price: Low to High" option, the products did not get sorted as expected. Instead, all products disappeared from the product catalogue, leaving an empty page.

**Steps to Reproduce:**


1. Navigate to  https://mystore-testlab.coderslab.pl/
2. Click on “Clothes” text link or any other catalogue
3. Locate and select the dropdown menu sorting function.
4. Choose the "Sort by Price: High to Low" or "Sort by Price: Low to High" option.
5. Observe the product catalogue.


**Expected Behavior:**

When using the sorting function to arrange products by price, the e-commerce website should:

Display all products sorted in the selected order (high to low or low to high).

Maintain all products visible in the catalogue.

**Actual Behavior:**

After selecting the "Sort by Price: High to Low" or "Sort by Price: Low to High" option, all products within the product catalogue disappear from the page, leaving an empty product list.

**Reproducibility:** Consistently reproducible.

**Priority:** P2

**Severity:** Major

![sort by 1](https://github.com/puribogdan/bug_reports/assets/50368261/bfdf416b-5aa4-4372-bb5d-ff332a55d1f8)
![sort by 2](https://github.com/puribogdan/bug_reports/assets/50368261/ada02fb5-646b-41ce-b88c-7bd355e136bd)
