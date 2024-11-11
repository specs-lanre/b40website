//strings

let text1="welcome to js class"
let text2="apples are fun ,get me an apple"
let text3="apple\"s are fun ,get me an apple, itts fun fun to eat"

console.log(text1)
console.log(text2)
console.log(text3)

//total number of xters in a string
console.log("total xters",text1.length)
//index positio
console.log(text1[5]," at position 5")
console.log(text1[9]," at position 9")
console.log(text1[15]," at position 15")

let v = text1.charAt(10)
console.log(v," at position 10")

let res = text1.concat(text2)
console.log(res)
res = text1+" "+text2
console.log(res)

res = text2.search("apples")
console.log(res)

res = text2.search("fun")
console.log(res)
//Mutability - strings are immutable
text2[3] = "t"
console.log(text2)


res = text2.indexOf("fun")
console.log(res)

res = text2.indexOf("joy")
console.log(res)


res = text2.includes("fun")
console.log(res)

//REGULAR EXPRESSION
//case sensitive test
let ptrn = /fun/
//test method
res = ptrn.test(text2)
console.log(res)



//case INsensitive test
 ptrn = /FUN/
//test method
res = ptrn.test(text2)
console.log(res)



//case match
 ptrn = /FUN/
//match method
res = text2.match(ptrn)
console.log(res,"****")


//case match
 ptrn = /fun/
//match method
res = text2.match(ptrn)
console.log(res,"****")





//case INsensitive test using modifiers
 ptrn = /FUN/i
//test method
res = ptrn.test(text2)
console.log(res," ****using mod")


//case INsensitive test using modifiers//case match
 ptrn = /FUN/ig
//match method
res = text3.match(ptrn)
console.log(res,"****")



