# Lab8-Starter

Name: Evan Wu

Deployed GH Pages URL: https://twintersww.github.io/Lab8_Starter/
- There might be a colliding recipes entry in localStorage already from Lab 6. I had to clear the localStorage before reloading the page to fetch the Thanksgiving recipes.




How are graceful degradation and service workesr related?

Graceful degradation is the concept of having a web application be robust to the point that even if the browser, runtime, or external variables (like a network connection) are not up to par, the web application will still have some level of resiliency and do the best it can to function as intended, or at least work with reduced functionality -- rather than breaking completely and leaving the user frustrated and confused. Service workers make our web applications more robust such that even when network conditions are weak, we are able to at least serve cached data through intercepted web requests, rather than fail them instantly because of network failure.
