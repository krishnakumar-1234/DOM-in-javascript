console.log("Hello world This is my manipulation in javascript");

// This is id selector in javascript from DOM manipulation
let idSelector = document.getElementById("idSelector");
console.dir(idSelector);

// This is className selector in javscript from DOM manipulation
const ClassSelector = document.getElementsByClassName("ClassSelector");
console.log(ClassSelector);

// This is TagName seletor in javascript from DOM manipulation
const TagNameSelector = document.getElementsByTagName("p");
console.log(TagNameSelector);

// This is query selector in javascript from DOM munipulation by the IDNAE AND CLASSNAEM AND TAGNAEM
const querySelector = document.querySelector('p');
console.log(querySelector);

// This is query selector in javascrpt all selector elements
const querySelectorAll = document.querySelectorAll('p');
console.log(querySelectorAll);

// This is query selector from the idName 
const querySelectorIdName = document.querySelector("#idSelector");
console.log(querySelectorIdName);

// This is query selector from claaName 
const querySelectorClassName = document.querySelector(".ClassSelector");
const querySelectorClassNameAll = document.querySelectorAll(".ClassSelector");
console.log(querySelectorClassName);
console.log(querySelectorClassNameAll);

// This is properties in javascript and practicing 

// 1. TagName : return tag for elelment nodees
let TagName = idSelector.tagName;
console.log(TagName);

// 2.  innerText : return the text content of the element and all children
let innerText = idSelector.innerText = "This is inneText method to change this is line";
console.log(innerText)

// 3. innerHTML : return the plain text of HTML contents in the element 
let innerHTML = querySelector.innerHTML = "<div>This is innerHTML method, changed by js</div>";
console.log(innerHTML);

// 4. textContent retunr textual content even for hidden elements
let textContent = querySelectorAll.textContent;
// console.log(textContent);

// This is practce question 
const practice = document.getElementById("practice");
practice.innerText = practice.innerText +  "fomr Apna College students";
console.log(practice);


const boxs = document.querySelectorAll(".boxs");
boxs[0].innerText = "This is fisrt box for made by html and css js";
console.log(boxs[0]);
boxs[1].innerText = "This is seond box for made by html and css js";
console.log(boxs[1]);
boxs[2].innerText = "This is third box for made by html and css js";
console.log(boxs[2]);

// This is DOM manipulation part-2 in javaScript

// This getAttribute in javaScript
const div = document.querySelector('#attribut');
console.log(div);

const id = div.getAttribute('id');
console.log(id);

const name = div.getAttribute('name');
console.log(name);

// This SettAttribute in javaScript
const text = document.querySelector(".text");
const textto = text.setAttribute("class", "newClass");
console.log(text);

// This is insert elelment in javaScript 
const newButton = document.createElement('button');
const newButton2 = document.createElement('button');
const newButton3 = document.createElement('button');
const newButton4 = document.createElement('hr');
newButton.innerHTML = "<i>click me but this is is create by js</i>"
newButton2.innerText = "This is prpend method by set it"
newButton3.innerText = "This is befor method by set it"
console.log(newButton);

// This is append in javaScript // to adds the end f node (inside)
div.append(newButton);

// This is prepend in javaScript // to adds the start f node (inside)
idSelector.prepend(newButton2);

// This is befor in javaScript // to adds the start f node (outside)
boxs[0].before(newButton3)

// This is Delete in javaScript
let Delete = document.getElementById('delete');
Delete.remove();
console.log(Delete)# DOM-in-javascript
