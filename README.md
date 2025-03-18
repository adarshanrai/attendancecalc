This is my first package so there is no read me file 
the function relies on prompt-sync so you first need to install prompt-sync
(npm install prompt-sync)

how to install and use attendancecalc:

npm install attendancecalc

how to use attendancecalc:

const { calculateAttendance } = require('attendancecalc');
const prompt = require('prompt-sync')(); 
calculateAttendance(prompt);


how to make your own nmp package>
https://adarshanrai.github.io/attendancecalc/
