#----------------------------------------------------------------#
#  Student Name : Haysam Elamin                                  #
#  Student ID   : 8953681                                        #
#----------------------------------------------------------------#

#-----------------Project Technical Breakdown--------------------#

In this project, an e-commerce dataset of 1000 records was read, and only
 the first 501 records were selected. After exploring the data, a rename 
feature function was developed to rename the features. Two data structures 
were used to reorganize the data. The first was a dictionary, as it is possible
to read each record as a dictionary. Then, a class was created to store both the 
features as properties and the functionality and behavior as methods. After that, 
a set of operations was performed on the data, including adding additional features 
(coupon_code, coupon_discount) and transforming it by adding the days_since_purchase 
using the property method. Finally, the environment was frozen to store the best 
working version.


#-----------------Environment preparation--------------------#


1- python -m venv .venv
2-.venv\Scripts\activate
3- pip install pandas matplotlib