# Myntra Fashion Clothing
 
![image](https://user-images.githubusercontent.com/69207326/193027671-960df91f-d727-40cf-952e-810b324acafd.png)

##### We have two different source of file of Myntra. One is Product details and Other in Product Category. Merge Both data to get final data and the columns of new daa are : 
        - ProductID	
        - ProductName	
        - ProductBrand	
        - Gender	
        - Price (INR)	
        - NumImages	
        - Description	
        - PrimaryColor

##### Next Step is to perform EDA, 
        - While performing we fount that there are null values in {Primary Color} which we replaced by other.
        - There was a columns that need striping so we used lambda to strip all the object columns.
        - Replace {Price (INR)} with {Price}.

##### While performing Analysis on Gender we found that:
        - The {Men} and {Women} have the Highest and 2nd Highest Price of total product present but both of there mean price of all the product is less than mean price for {Unisex} Product.
        - Even though {Women} have maximum number of product present in myntra its in 2nd position for total price.


