

##TECHNICAL QUESTIONS

##What an API?

An API is simply an intermediate between systems to which enables them to interact with each other. For example, consider train booking, if you want to book a ticket you will use MakeMyTrip, Paytm and what not. In real they really don’t have provisions for booking the ticket [or] to show you the number of available tickets instead the use API i.e. a program provided by the real ticket provider on their server to show and block tickets.

# What is REST and which methods are there in REST?

REST API defines how a server responds to create, read, update, and delete request. REST suggests to treat all URL as access point for various resources on the server. REST uses get, post, put and delete methods to perform CRUD operations.

# Which REST method will be cached in browser unless otherwise explicitly mentioned by server?

POST METHOD.

# Which REST method is idempotent and which method is not idempotent? Explain with a small example.

1. POST is NOT idempotent.

2. GET, PUT, DELETE, HEAD, OPTIONS and TRAVE are idempotent.

# Which REST method should be used to deal with user sensitive data like credit card information etc.?

HTTPS METHOD

# What is the difference between http and https? Explain shortly how https work.

In http the information that is passed to browser is not encrypted, which results in theft of data. HTTPS remedy this by using SSL (Secure Socket Layer) certificate, which indeed provide secure connection between the server and the client browser. Here the SSL certificate encrypts the information that user supply to the site so that even if the data is stolen it can be used.

# What is caching? How does it help an application?

Caching is used to store some data from a website so that it can load faster. That is why when we visit a new website it loads slower than the website we visited before.

# What is the main difference between traditional relational databases and NoSQL databases?

In SQL data are stored in rows and column whereas in NoSQL data’s are stored in key value pairs. SQL follows ACID properties (Atomicity, Consistency, Isolation and Durability). NoSQL follows CAP theorem (Consistency, Availability and Partition tolerance).

# Explain shortly MVC pattern in developing backend applications/

MVC patterns separate the processing, input and output of an application. As the name suggest this model divided into three parts namely model, view, and controller. All of the three components are built to handle some specific development aspects of a web application development.

# What is event loop in JavaScript? Explain with an example

Event loop is a constantly running process , which checks whether the call stack is empty , if empty it checks for event queue and if there is something in event queue that is waiting it is moved to the call stack.

setTimeout(() => console.log('first'), 0)  
console.log('second')

In the above example you will see “second” printed out before “first”. JavaScript sees the setTimeout and says “Well, I should add this to my Event Table and continue executing”. It will then go through the Event Table, Event Queue and wait for the Event Loop to tick in order to run.

# Difference Between Git Fetch and Git Pull?

Git fetch is used to retrieve latest changes made in remote repository whereas and it does not change the local repository whereas Git pull changes local repository.
