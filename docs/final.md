# **Polling Location Map of Prince George's County**
## **William Zabet, Tyler Behr, Joshua Parks, Michael Stripling, Jose Aguirre-Mori**
### Link to App

### Information Problem
The information problem is that the residents of College Park/Prince George’s County may not know about polling places where they can practice their civic right to vote. This could be due to the information not being readily available or difficulty when navigating through the information. One key information problem that we noticed was that there were no images of the physical polling stations contained in the map. This is an information problem as visual representations may be of value to certain users in Prince George's County. In summary, our end goal was to create a map of Prince George's County Polling Stations that included images so that users may quickly gather information about Polling Stations.
### Our Stakeholders
Any Prince George's County resident that is of voting age or will be of voting age by the Maryland Primary Election or the United States General Election is a stakeholder for our project. The government of Prince George's County will also be a stakeholder as we hope they see our project will be an improvement on their current map. 

### Our data
[PG Open Data](https://data.princegeorgescountymd.gov/Government/Polling-Places/e2wd-vu2n)
### Chosen Strategies and Solutions
Because of our goal of creating an efficient application by minimizing clicks, we needed to create flow that would present our user with relevant information immediately. This is why we tried to create as close to a one one-page system that we could. One solution to this was incorporating our map right on our homepage. This saved a considerable amount of time as users would no longer have to navigate to a start button to access our map. To address our information problem of the lack of images, we created a pass-through to Google Maps. This pass-through not only takes users to images, but it can also allow users to take advantage of Google Maps' capabilities and receive directions on how to get to a polling station from their location.
### Techincal System Decision Rational

### Did We Address Our Problem?

### Challenges Faced and Their Impact
The main challenge and failure that we have experienced was failing to develop a proper backend and host our application on Heroku. This has a substantial impact on our application as it discredits our application for potential real-world use. Another failure is the potential shift in our information problem. Due to the COVID-19 outbreak, mail-in voting is being discussed as a potential option for voting in future elections. If this shift occcurs, we will find our application may not be in use until the current outbreak is over. Lastly, there are potential issues within certain web browsers regarding the loading speed of our application. There have been instances of slow loading times within Google Chrome that noticeably affect our applications efficiency. This may discourage Google Chrome users from using our application on that platform. There have been no reported slowdowns in other popular web browsers, such as Mozilla Firefox and Apple Safari. 
### Future Plans
There are a couple of features we would like in the future. The first would be to incorporate facets to filter the results for each user. This feature would allow the uses to eliminate certain polling stations that do not fit their criteria. The second feature is to add a form where users can enter their address and the website will show them all polling locations within a specified mileage radius to their address. By eliminating non-feasible polling stations we minimize how much information the user sees and avoid the risk of information overload. Finally, we would like to create a plugin that adds information about a selected marker or location from the list to the sidebar of the website. this would the user to compare the information of different polling places and make the most informed decision they can.
