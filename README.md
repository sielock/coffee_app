As a coffee enthusiast, having a way to keep track of the different varieties of coffee beans, preparation methods, and other coffee-related information would very useful. So I wanted to make a webapp that can fulill these use cases, and hopefully many more down the road. Initially, this will be a fairly simple project, a website built using HTML5, CSS3, and vanilla JavaScript. I am modeling functionality off of Untappd, as I like how they have build their app for craft beer and I think a similar app for coffee would be a welcome addition.

Initially this will be a just a website, responsive for device. Hopefully, once I have it up and running, I would like to turn it into a progressive web app (PWA) in order to bridge the gap between desktop and mobile more effectively.

TODO:

-my list:
    will host the logged coffee that has been made/purchased/drank/enjoyed/etc. The main journal aspect of the app.

-recipes: 
    will host the custom recipes to be used with the coffee logs. Functionality should allow user to create a recipe specifying the brewer used, the ratio of coffee to water, bloom and brew times, as well as any additional notes. These recipes will be stored and will be able to be retrieved when creating a new log entry.

-beans: 
    will be where the user houses information regarding coffee beans they have/have used specifically. Will allow users to store information regarding coffee beans they have purchased, including information on variety, process, region, tasting notes, and the company that roasted the beans. Will have search functionality which will use API calls and web scaping to acquire data of coffee roasters, who can be linked to the bean entries. Can be used as a browse option to see what beans are available at roasters and what people think of them. May be turned into primary aspect of app, similar to how Untappd works.