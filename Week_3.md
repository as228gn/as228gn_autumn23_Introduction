## Markdown Code Block

```
let age = 35
let name = 'Anna '
let occupation = ' Dental Hygienist'

console.log(typeof age)
console.log(typeof name)

console.log('Hello my name is ' + name + 'and I am ' + age + ' and I am an' + occupation)

if(typeof occupation === 'string'){
  occupation = 'Student'
  console.log(occupation)
}

if(age < 40){
  age = 40
  console.log(age)
}

console.log('Hello my name is ' + name + 'and I am ' + age + ' years old and I am a ' + occupation)
```