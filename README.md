To the Director,

The correct average revenue for West customers is 806.04 dollars, not the 1,231.19 dollars from the query that joined customers to orders, which counted each customer once for every order they placed. Since customers with more orders also bring in more revenue, they were counted many more times than everyone else and pushed the average up by about 1.53 times, even though revenue is a customer-level number that should be averaged with one row per customer.

As for the program, a simple comparison makes it look like it adds about 208.45 dollars per customer, but most of that gap exists because the West already had larger accounts, and once account size is accounted for the effect drops to about 20.97 dollars, close to the true 20 dollars. The program does help, just much less than the first comparison suggested. Adding support tickets as a control pushed the estimate down to −32.64 dollars, because the program itself changes how many tickets customers file, so it should not be used as a control.

Before any number goes on a slide, I recommend the team check that the row count still matches the number of customers after every join, check whether a filter is quietly dropping rows with missing values, and run each query through the review tool before it is shared.
