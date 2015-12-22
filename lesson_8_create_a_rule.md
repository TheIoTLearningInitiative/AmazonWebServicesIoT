# Lesson 8: Create a Rule to Store our Data.

Return to the AWS IoT dashboard and click on the **Create a resource** button.

![](40.jpg)

Select the option **Create a rule**

![](39.jpg)

Now you just need to complete the following information:

* Name, its the Name of the rule, in our case we called RuleInsertDynamoDB
* Description, is optional you can type a description of the rule.
* Rule query statement cant be modified.
* Attribute, its the attribute that we can catch from the device in our case we will catch all the information we will use an asterisk to indicate that we need all the information. 
* Topic Filter: 
* Condition, for this test we will leave it, blank we will catch and store all the messages.
* 

![](41.jpg)