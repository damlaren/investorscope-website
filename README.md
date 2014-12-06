INVESTORSCOPE README
====================

Installation Requirements
-------------------------

There are no installation requirements for the InvestorScope app. It is a mobile web application, and can be accessed on Heroku at:

https://ancient-peak-1097.herokuapp.com/

It is worth noting that the application is optimized for the iPhone on Chrome specifically, but it should work well on any modern mobile phone with an up-to-date browser.

Logging In
----------

The username and password for the site are both 'x' for testing purposes.

Brief Discussion of Tradeoffs Between Functionality and Completeness
--------------------------------------------------------------------

For the most part, we implemented this application in its entirety. The two areas that we "faked up" were the machine learning algorithms on the backend as well as some aspects of the data.

In the first category, the machine learning portion could easily be a CS229 project, and we simply didn't have the bandwidth or the knowledge to accomplish this within the scope of the class, so we return the same recommendations regardless of responses. However, we did begin the process of designing a scoring system informally though did not finish it for the aforementioned reasons.

In the second category, all of the financial data is real, scraped from Yahoo! Finance. However, it's not necessarily up-to-date. We scraped all of it a few weeks ago and have not updated it because we felt that a 24/7 auto-updating server wasn't core to this project's goals. Additionally, the quality of data that we would need to make this professional-grade costs about $30,000 / year at the base level, confirming our decision to pass on "perfect live data" as we could call it. The qualitative data, such as "Made in America," "Sustainability" etc. is algorithmically generated, and isn't drawn from real sources, since again that would take a lot of time and potentially distract from the goal of making a really good UI. 

These were the two largest tradeoffs we made, and essentially followed the pattern of "feature completeness vs. goal prioritization." We believe that we were able to strike a good balance by making the app function in a fully real way with the exception of the machine learning and live, highly-accurate data. In this way we were able to make the app look and feel "complete" without setting unrealistic goals for ourselves, allowing us to accomplish this project within the scope of the course.
