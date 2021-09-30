**Description:**
I chose the second option for this project, which allows for users to input a country code and returns a list of countries that a driver would pass through from USA to the destination. I built the web application in Visual Studio Code using React and I hosted the project using GitHub Pages. I initialized a React project, and then I primarily edited two files for app functionality. The first was “src/countries.js”, which contains the JSON array to store destination and country list data. The second was “src/App.js”, which was contains everything for the input form and results. In order to host the website on Github, I edited “package.json” to include the homepage URL and deploy scripts. 

**Assumptions:** 

•	I assumed that the three-letter country code would always refer to one country no matter the capitalization, so I converted the input string to all uppercase letters to match the JSON destination formatting. 

•	I assumed all drivers would take the most direct route to a destination. For instance, a driver going to Guatemala would not need to go through Belize to reach the destination.  

•	Since the input form and list of results was relatively little information without a lot of formatting, I decided to include them within one React component. If this project was expanded to include more data or required better formatting such as a table, it would be beneficial to break them apart into separate components. 
