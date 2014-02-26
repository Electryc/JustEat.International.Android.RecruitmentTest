Senior Developer (Android) - Technical 

Test

Thank you for taking the time to do our technical test. Please don’t feel you need to spend more 

than 90 minutes on it in total. The test consists of two parts:

● A coding test - please don’t feel you need to spend more than an hour on this part

● A few technical questions - please don’t spend more than half an hour on this part

In order to avoid bounced emails (some ISP's appear to be blocking emails with candidates' test 

result attachments) we would like you to submit your results by uploading the relevant zip file 

to a shared Google Drive folder. In order to supply you with the URL for this folder please send 

an email to tech.recruitment@just-eat.com stating your Google email address. (Alternatively, 

you can let your agent know your Google address.) If you don't already have a Google email 

address, please obtain one so that you can be given access to the JUST EAT test results folder. 

Coding Test

Just Eat has a public API available at http://www.just-eat.co.uk/webservice/webservices.asmx 

that you can use to get restaurant information, including what restaurants delivery to what 

areas.

How to use the API

● getRestaurantList - returns a list of restaurants (as XML) that deliver to a postcode, 

including some basic restaurant information

Note that you should only submit the first part of a postcode. e.g. NW3 rather than NW3 1HT.

The API requires that you send a User-Agent header as part of the request. If you have 

problems connecting then please check that you’re including a User-Agent.

What you need to do

Please create an app using Java and the editor of your choice that locates the current postcode 

that the user is in. The app should then display the following information about each restaurant 

that delivers to that postcode:

● Name

● Average rating

● Restaurant logo

The restaurants should be ordered from highest average rating to lowest average rating.

You can build up the URL to the restaurant logo as http://www.just-eat.co.uk/images/

Restaurants/{restaurant_id}.gif

Please take the time to write code to the standards you would expect in a real application.

Questions

Please don’t spend more than 30 minutes on this section.

1. Did you have time to complete the coding test? What would you add if you had more 

time?

2. What was the most useful feature in your opinion that was added to Jelly Bean? Please 

include a snippet of code that shows how you've used it.

3. What's your favourite programming language? Why?

4. How would you track down a performance bottleneck in an app? Have you ever had to 

do this?

5. How would you make the Just Eat public API - http://www.just-eat.co.uk/ webservice/

webservices.asmx - easier to consume within a native app?

6. Which of your apps in marketplaces are you most proud of? Why?

7. Please describe yourself using either XML or JSON.
