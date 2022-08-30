# NASA API

This web application displays NASA's picture of the day for any date that the user inputs, as long as NASA had a picture of the day for that date. 

**Link to project:** https://gnarly-nasa-api.netlify.app/

![Website preview](https://i.imgur.com/aSWldhQ.png)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript

This web application features integration with a NASA API that can listen to a request containing a date, and respond with NASA's picture of the day matching that input date. This website will take that response and display the image to the user. If NASA uploaded a video instead of a picture, the app will display the video instead. 

## Optimizations

This project could be improved by refactoring it into a full-stack application, which would give me more control over how the requests are handled. Running this website as a full-stack app would allow me to more easily add support for form submission, as it currently only works on-click of the submission button. Additionally, I would like to add support for other features of NASA's API, such as retrieving pictures from Mars rovers like Curiosity and Perserverance. This is tricky to do because there are often hundreds of pictures per day, so they need to be collected randomly and narrowed down somehow. It's not very useful or ideal to be met with hundreds of pictures at once. 

## Lessons Learned:

This project was an early attempt at web API integration, with some interesting wrinkles such as the few dates that feature a video instead of a picture. I've experimented with other functions of NASA's API and it's been challenging to come up with "sellable" purposes for them, or more specifically, how to crunch NASA's massive amounts of data into something simple and digestible for a typical user to enjoy. 
