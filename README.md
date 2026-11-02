To the Director,

The correct average revenue for West customers is 814.37 dollars, not [joined] dollars. The higher number came from joining customers to orders, which counted each customer once for every order they placed. Since customers with more orders also bring in more revenue, they were counted many times and pushed the average up by about [ratio] times. Revenue is a customer-level number, so it should be averaged with one row per customer.

On the programme, a simple comparison makes it look like it adds about 208.64 dollars per customer, but most of that is because the West already had larger accounts. After accounting for account size, the effect is about 21.93 dollars, close to the true 20 dollars. The programme helps, but only a little. Adding support tickets as a control made the estimate drop to −30.62 dollars, because the programme itself affects how many tickets customers file, so it should not be used as a control.

Before any number goes on a slide, I recommend the team check that the row count matches the number of customers after any join, check whether filters are dropping rows with missing values, and run queries through the review tool before they are shared.
