let today = new Date();
let date= parseInt(today.getMonth()+1) + "/" + today.getDate() + "/" + today.getFullYear();
let endDate = new Date('12/17/2022');
let days = parseInt(endDate - today) / 1000 / 60 / 60 / 24;
console.log(parseInt(days)+1);


let diffTime = Math.abs(new Date().valueOf() - new Date('2022-12-17T11:30:00').valueOf());
let days = diffTime / (24*60*60*1000);
let hours = (days % 1) * 24;
let minutes = (hours % 1) * 60;
let secs = (minutes % 1) * 60;
[days, hours, minutes, secs] = [Math.floor(days), Math.floor(hours), Math.floor(minutes), Math.floor(secs)]

console.log(days+'d', hours+'h', minutes+'m', secs+'s');
VM1691:8 50d 19h 0m 46s
