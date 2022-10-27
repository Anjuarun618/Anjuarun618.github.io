let today = new Date();
let date= parseInt(today.getMonth()+1) + "/" + today.getDate() + "/" + today.getFullYear();
let endDate = new Date('12/17/2022');
let days = parseInt(endDate - today) / 1000 / 60 / 60 / 24;
console.log(parseInt(days)+1);
