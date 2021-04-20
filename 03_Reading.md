## 401 Reading Notes
1. Name 3 real world use cases where you’d want to change the request with custom middleware.
 - In one scenario you can identify the currently logged in user, so using the custom middleware fetches the user through a set of authentication steps.
 - A second example is changing the functionality on your response object, such as creating a new header. I could foresee a company doing that to advertise a sale of a product.
- Building on the fact that a user logs in, the custom middleware can be uses to also validate a users data. The users information and credentials could be stored in a database to verify the information is correct.

[https://www.digitalocean.com/community/tutorials/nodejs-creating-your-own-express-middleware]


2. True or false: The route handler is middleware?
- True, route handling is a part of middleware functionality. The exception is route handling may invoke the next function parameter to pass control onto the middleware function within the stack. [https://stackoverflow.com/questions/58925276/what-is-the-difference-between-a-route-handler-and-middleware-function-in-expres]

3. In what ways can a middleware function end the process and send data to the browser?
- Middleware could be built as so when a set of parameters are requested within a webpage it bypasses a response cycle and overlay's a set of data. 

4. At what point in the request lifecycle can you “inject” middleware?
- Middleware is usually injected during a req and before a response cycle, this means that middleware is a dependency and the req and res cycle depend on the middleware to take place.

5. What can cause express to error with “Request headers sent twice, cannot start a second response”
- If a return statement is used in a function body, the execution of the function is stopped. "What happens in the function, stays in the function". [https://www.codementor.io/@oparaprosper79/understanding-node-error-err_http_headers_sent-117mpk82z8]

**Define**
- Middleware: Middleware is a computer software that provides services to software applications beyond those available from the operating system. [https://en.wikipedia.org/wiki/Middleware]

- Request Object: A request object allows you to submit a POST or GET request to a URL. [https://www.branchcms.com/learn/docs/developer/twig/request-object]

- Response Object: It is an object that communicates between the server and the output which is sent to the client. [https://www.4guysfromrolla.com/webtech/faq/Beginner/faq3.shtml]

- Application Middleware: Application middleware is a messaging like service so that different application can communicate using messaging frameworks like simple object access protocol (SOAP). [https://azure.microsoft.com/en-in/overview/what-is-middleware/
]
- Test Driven Development: TDD is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing software again all test cases. [https://en.wikipedia.org/wiki/Test-driven_development]

- Behavioral Testing: A type of testing using the external behavior of the program, which is also known as black box testing
[https://www.tutorialspoint.com/software_testing_dictionary/behaviour_testing.htm#:~:text=Behavioural%20Testing%20is%20a%20testing,is%20usually%20a%20functional%20testing.]

1. Which 3 things had you heard about previously and now have better clarity on?
- SOAP, TDD, Request Object
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- SOAP and TDD
3. What are you most excited about trying to implement or see how it works?
- I think in general I’m excited just to manipulate code and to make it so I can refactor to a point of clarity that is easy to read and easy to repeat. (DRY: Do not repeat yourself)


### Table of Contents
- [Read Express 01](01_Reading.md)
- [Read Express 02](02_Reading.md)
- [Read Data Modeling](04_Reading.md)
- [Read Linked Lists](05_Reading.md)
- [Read Authentication](06_Reading.md)
- [Read Bearer Authorization](07_Reading.md)
- [Read Access Control (ACL)](08_Reading.md)
- [Read Express 01](09_Reading.md)
- [Read Stacks and Queues](10_Reading.md)
- [Read Event Driven Applications](11_Reading.md)
- [Read Socket.io](12_Reading.md)
- [Read Message Queues](13_Reading.md)
- [Read Event Driven Architecture](14_Reading.md)
- [Read Trees](15_Reading.md)
- [Read AWS: Cloud Servers](16_Reading.md)
- [Read AWS: S3 and Lambda](17_Reading.md)
- [Read AWS: API, Dynamo and Lambda](18_Reading.md)
- [Read AWS: Events](19_Reading.md)
- [Read Component Based UI](26_Reading.md)
- [Read Props and State](27_Reading.md)
- [Read Component Composition](28_Reading.md)
- [Read Routing](29_Reading.md)
- [Read Hash Tables](30_Reading.md)
- [Read Hooks API](31_Reading.md)
- [Read Custom Hooks](32_Reading.md)
- [Read Context API](33_Reading.md)
- [Read Reading: <Login /> and <Auth />](34_Reading.md)
- [Read Retrospective](35_Reading.md)
- [Read Application State with Redux](36_Reading.md)
- [Read Redux - Combined Reducers](37_Reading.md)
- [Read Redux - Asynchronous Actions](38_Reading.md)
- [Read Redux - Additional Topics](39_Reading.md)
- [Read React Native](41_Reading.md)
- [Read Ethics](42_Reading.md)

## Link to Code 102
- [Code 102 Reading Notes](https://jtaisey389.github.io/reading-notes/)

## Link to Code 201
- [Reading Notes 201](https://jtaisey389.github.io/reading-notes201.md/)

## Link to Code 301
- [Reading Notes 301](jtaisey389.github.io/reading-notes301.md/)

[<== Back_to_reading_notes](jtaisey389.github.io/401_readingnotes.md/)