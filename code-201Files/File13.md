# Persistence with Local Storage
## Local Storage and How To Use It On Websites
### Why would a developer use local storage for a web application?
The HTTP layer on the web is stateless but if its on the users desktop the most recent state is stored.
### What information should not be stored in local storage?
Sensitive personal information such as passwords, SSNs, or credit cards! 
### Local storage can store what type of data? How would you convert it to that type before storing?
Only strings can be stored. These methods JSON.stringify() and JSON.parse() can help convert it. 