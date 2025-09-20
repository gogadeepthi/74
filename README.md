let person= { name:"deepu", age:20, country:'India'};
let result="";
for(let key in person){
    result += "<li>" +key + ":" + person[key]+ "</li>";
}
document.getElementById("person").innerHTML= result;
