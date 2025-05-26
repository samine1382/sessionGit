سوال 1

let number1=(arrays)=>{
    for(let num of arrays){
        if(typeof num!=='number'){
            console.log("not number")
        
        }else {
            console.log("is number")
        }
    }
} number1([2,3])   جدا فراخوانی شود
---------------------------------------
سوال2

function obj(array) {

    for(let key in student){
        if(student[key].grade>17)
        {
            console.log(student[key].name)
        }

    
}
}
const student =[{name:"ali",grade:16},{name:"sara",grade:18},{name:"reza",grade:19}]
obj(student)
-----------------------------------------
سوال 3







------------------------------------
سوال4

function sum(n) {
    if(n===0){return 0}
    return n+sum (n-1)
}
sum(5)