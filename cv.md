# Shumski Piotr
Beginner Front-end Developer

## Contacts:
**Phone:** +48 793-736-708

**Address:** 53-442 Spiżowa 10/18
Wrocław, Poland

[**Telegram**](https://t.me/petr1k27)

## Skills
1. HTML
2. CSS
3. JS
4. Git
5. React
6. Java

## Code example
**Make the Deadfish Swim**
Write a simple parser that will parse and run Deadfish. Deadfish has 4 commands, each 1 character long:
+ **i** increments the value (initially 0)
+ **d** decrements the value
+ **s** squares the value
+ **o** outputs the value into the return array


``` 
function parse( data )
{ let result = [],
      value = 0;  
 
   for(let i=0; i < data.length; i++) {
      switch(data[i]) {
      case 'i' : value++; break;
      case 'd' : value--; break;
      case 's' : value *= value; break;
      case 'o' : result.push(value); break;
  }
}  
 return result;  
} 
```
