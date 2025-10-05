# Exchange-Rate
Project build in C++.

1.Add a data member to the Product class to store an exchange rate for an alternate currency besides the default one used for the product.

2.Ensure the exchange rate is always initialized by the Product class such that the alternate currency is the same as the default currency (e.g., both U.S. dollars).

3.Add a mutator member function that allows setting the exchange rate for the alternate currency.

4.Add a 2nd instance of template class History to store the historic prices in the alternate currency.

5.Modify the existing setPrice() member function so that when a new price is set, it also stores the price of the product under the alternate currency using the current exchange rate. For example, if the price is set to 6.0 in the default currency and the current exchange rate is 3.0 then 2.0 should be stored for the alternate currency.

6.Change the output()function to also show the history in the alternate currency after its historic price in the default currency: (Price History: 5.50 6.00 => Alternate urrency History: 1.25 2.00) …

7.Add an accessor to the History class named size that returns the number of values currently stored in the object. Note: This can be implemented without adding data members.

8.Add an accessor to the Product class that returns the average exchange rate (computed from both of the price histories). For example, the average exchange rate based on the historic data shown in Step 6 above is 3.7.

9.Add sufficient code to the main program (main.cpp) to demonstrate that all the exchange rate code works correctly.

10.Document your changes/additions with comments.  
