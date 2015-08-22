# FEC-Data-Visualization
A D3-powered visualization of the data collected by the Federal Election Commission from 2013-2014. This was built for my database class in Spring 2015.

Behavior
--------
As the user is hovering across the states and sees a total contribution amount that is worthy of inspection, the user should see the transaction histogram display the distribution of contributions that belong to the state highlighted under the cursor. The height of the bars should be with respect to all of the contribution amounts (regardless of state). This will give the user a sense of what fraction of the total contributions came from a particular state.

As the user clicks a particular state, the user should see the transaction histogram display the distribution of contributions that belong to the clicked state. The height of the histogram bars should be with respect to just the state's contribution amounts, rather than all of the contribution amounts.

Result
----
![lolno](https://camo.githubusercontent.com/e5decb5265e12ca80d94b163c5305527ac372a1d/687474703a2f2f692e696d6775722e636f6d2f463852517a7a412e676966)

Where tha data at?
------------------
For this project I used about ~250 MB of [public campaign donation records](http://www.fec.gov/data/DataCatalog.do).

Tools used
----------
- JavaScript + D3.js for the client-side web visualization
- Flask for the python server backend. Makes it super easy for us to query and repackage the data for client-side use. 
- Postgresql for storing our data.

![lol](https://camo.githubusercontent.com/9549268617035b7e102af10daa21fa28505dc11d/687474703a2f2f692e696d6775722e636f6d2f364841753250772e706e67)

