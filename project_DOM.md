# Project related DOM
## PROJECT LINK
[click here] (https://stackblitz.com/edit/vitejs-vite-69wgmbrv?file=index.html,project1.js,index.css)
 
 #solution code 
 ##Project 1
 
```JAVA SCRIPT
console.log('mansi');

const greybox=document.getElementById('grey');
const whitebox=document.getElementById('white');
const bluebox=document.getElementById('blue');
const yellowbox=document.getElementById('yellow');
 
function changecolor(color){
 document.body.style.backgroundColor=color;
}

greybox.addEventListener('click',function(){

changecolor('grey');
});
whitebox.addEventListener('click',function(){

  changecolor('white');
  });
  bluebox.addEventListener('click',function(){

    changecolor('blue');
    });
    yellowbox.addEventListener('click',function(){

      changecolor('yellow');
      });




```