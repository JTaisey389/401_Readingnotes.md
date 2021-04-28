## 401 Reading Notes

### Access Control

### Review
1. When is Basic Authorisation used vs. Bearer Authorisation?: Basic auth allows you to access the API directly with your credentials like a username and password. With bearer token you access an API you have to make two calls. One that gets the bearer token and the second which gets the data.

2. What does the JSON Web Token package do?: JSON Web Token is a compact URL-Safe means of representing claims to be transferred between two parties. The claims in JWT are encoded as JavaScript Object Notation(JSON). [Link](https://www.npmjs.com/package/json-web-token)

3. What considerations should we make when creating and storing a SECRET?
    * Don't store them in .git repositories
    * Add sensitive files in .gitignore
    * Never rely on code reviews to discover secrets
    * Encryptions should be used to store those secretes within .git repositories

### Define
- encryption: Encryption is the method by which information is converted into secret code that hides the informations true meaning. [Link](https://searchsecurity.techtarget.com/definition/encryption#:~:text=Encryption%20is%20the%20method%20by,encrypted%20data%20is%20called%20ciphertext.
)
- token: In programming a token is a single element of a programming language. There are five categories of tokens: 
    1. Constants 
    2. Identifiers
    3. Operators
    4. Separators
    5. Reserved words
[Link](https://techterms.com/definition/token#:~:text=In%20programming%2C%20a%20token%20is,%2C%20and%205%20reserved%20words.&text=Operators%2C%20such%20as%20%2B%2C%20%2D,of%20nearly%20all%20programming%20languages.)


- bearer: Bearer token are the predominant type of access token used with OAuth, bearer is an opaque string, not intended to have any meaning to clients using it. [Link](https://oauth.net/2/bearer-tokens/#:~:text=Bearer%20Tokens%20are%20the%20predominant,such%20as%20JSON%20Web%20Tokens.)

- secret: Secret refers to a secret key or passcode that is used by a user to login, or create a login. A secret should be safeguarded by the user and additionally it should be encrypted
- JSON Web Token: JSON web token is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON  object. [Link](https://jwt.io/introduction)

### Preview
1. Which 3 things had you heard about previously and now have better clarity on?
- Learning how Oauth place a key role with software development
- How JSON files are like a vault of information for packages or values
- Encryption is extremely important for any sort of secrets the user wants to protect

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- Learning about the involvement of JSON packages
- What are the best ways to encrypt a file, or is there a general practice
- How a programer can best set up code to optimise for efficiency 

3. What are you most excited about trying to implement or see how it works?
- It will be exciting to implement login capabilities, at that point user data can be store locally to a database. 

### Table of Contents
- [Read Express 01](01_Reading.md)
- [Read Express 02](02_Reading.md)
- [Read Express REST API](03_Reading.md)
- [Read Data Modeling](04_Reading.md)
- [Read Linked Lists](05_Reading.md)
- [Read Authentication](06_Reading.md)
- [Read Bearer Authorization](07_Reading.md)
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