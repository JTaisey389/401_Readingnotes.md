## 401 Reading Notes

### Class 01 
**1. Describe (in plain English) what Array.map()does**
- Array.map is a method that creates a new array which is populated with the results of calling a provided function on each element in the calling array. 

**2. Describe (in plain English) what Array.reduce()does**
- Array.reduce is a method that performs a reducer function which is provided by you on each element of the array, and the results produce a single output value.

**3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result. Use normal Promise.then() syntax***

`app.post('/searches/new', (req, res) => {`
  `let bookSearch = req.body.bookSearch;`
  `let search = req.body.search;`
  `let url = `https://www.googleapis.com/books/v1/volumes?q=in${search}:$`{bookSearch}`;
  `superagent.get(url)`
    `.then(returnData => {`
      `const bookArr = returnData.body.items.map(bookSearch => new Books(bookSearch)``);`
      `console.log(bookArr);`
      `res.render('pages/searches/show.ejs', {bookArr:bookArr});`
    `})`
    `.catch(error => {`
      `console.log(error);`
      `res.status(500).send('Sorry something went wrong with bringing your books` `back, please pay the fee');`
    `});`
`});`

***Example from my book app*** https://github.com/JTaisey389/book_app/blob/main/server.js

**Again with async / await syntax**
- const getCityData = (name) => {
  superagent.get(`https://geocode.xyz/${name}?json=1`)
  .then((data) => {
    const parsedData = JSON.parse(data.res.text)
    if(parsedData.error){
      console.log(parsedData.error.description)
    } else {
      console.log(`latitude: ${parsedData.latt}, longitude: ${parsedData.lognt}`)
    }
  }).catch(error => {
    console.error('Well, somthing is wrong', error)
  })
}

async function cityData(city) {
  try{
    await getCityData(city)
  } catch(error){
    console.error('Ehhhh somthing went wrong', error)
  }
}

cityData('Seattle')
cityData('ihroewbr33492')

***Example from my Async/Await code challenge*** https://replit.com/@JTaisey389/AsyncAwait#index.js

**4. Explain promises as though you were mentoring a Code 301 Level student
- A promise could be thought of as an event that will eventually take place, and what the user will get back is either a resolved or rejected. Think of it as a match game with cards and you’re trying to match those cards. If you get the wrong card that is a rejection, well if you match it would be resolved. 

**5. Are all callback functions considered to be Asynchronous? Why or Why not?**
- Callbacks invoke other functions so it's like your gathering them all together to complete a task. On the other hand an Asynchronous function waits for a promise and really it will depend on the use of the code. You could have a promise within a callback function waiting for a part of the code to be resolved or rejected. 


### Table of Contents
- [Read Express 02](02_Reading.md)
- [Read Express REST API](03_Reading.md)
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