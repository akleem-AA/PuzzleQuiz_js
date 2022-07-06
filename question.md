![](https://i.ibb.co/ph2mRw9/Whats-App-Image-2022-07-06-at-2-19-29-PM.jpg)

algorithm = :(D=4 || W=24) ==27
            
             
```js
....js......
1st method........
function findMisChar(data){
    var arr = ["",'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','x','y','z']
 
    let code = 27-(data.charCodeAt(0)-64); //logic 
    arr[code]//index of char
    console.log(arr[code])
    return code;
}
var result = findMisChar("L")//output = o
console.log("distance input cha and result char =",result)//output = 15 (it's work like a index number of array also retun o becouse o index is equal to 15

```
```js
//2 example -without any custom array
function findMisChar(data){
    let code = 27-(data.charCodeAt(0)-64); //logic 
    console.log(code)//index of char
    let text = String.fromCharCode(64+code);
    return text;
}
var result = findMisChar("W")
console.log(result) //char
```

python
```py
    
```
