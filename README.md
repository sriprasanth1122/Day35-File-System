# Day35 Node JS File System Task 

const fs = require('fs')

const currentDate = new Date();

fs.writeFile('./date-time.txt',${currentDate},(err) => { if(err) { console.log(err) } console.log("Completed Writing!!!!") } )

fs.appendFile('./date-time.txt','\n' + ${currentDate},(err) => { if(err) { console.log(err) } console.log("Completed Writing!!!!") } )

// to retrive all text

fs.readFile('./date-time.txt','utf-8', (err,data) => { if(err) { console.log(err) } console.log(data) })
