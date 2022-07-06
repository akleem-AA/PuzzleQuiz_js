![](https://i.ibb.co/ph2mRw9/Whats-App-Image-2022-07-06-at-2-19-29-PM.jpg)
```js
function findMisChar(data){
    var arr = ["",'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','x','y','z']
 
    let code = 27-(data.charCodeAt(0)-64); //logic 
    arr[code]//index of char
    console.log(arr[code])
    return code;
}
var result = findMisChar("L")
console.log("distance input cha and result char =",result)

```
