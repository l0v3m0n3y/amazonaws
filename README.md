# amazonaws
JavaScript library for checkip.amazonaws.com
# main
```js
async function main(){
    const {amazonaws} = require('./amazonaws');
    const amazon= new amazonaws();
    let req=await amazon.my_ip()
    console.log(req)
}
main()
```
