Download Link: https://assignmentchef.com/product/solved-assignment-14-chapter-15-triggers-10-points-for-q1-and-30-points-for-q2
<br>
Q1. (10 points)A product in the Products_copy may or may not have a unit price. Create an AFTER trigger called ‘tgr_priceValidation’ to ensure  that, if a product has a unit price, it must not be at least $0.50  but no higher than $500.00. Any attempt that violates this rule will be aborted by this trigger and receive an error 51234 witha message “No product is allowed to have a unit price out of the range between $0.50 and $500.00.”

Note that any action query, i.e., INSERT, DELETE, and UPDATE, can affect more than one row of data. So, if multiple products are affected by an action query, your trigger must be able to examine all of them in order to satisfy the above business rule.

Several test cases are provided for your testing. If toyr trigger is implemented correctly, you should get the passed/failed results as shown in each test case.