# MDN
 A wrapper for MDN
Example

```js

let client = new Base();
(async () => {
    let mdn = await client.mdn.fetch("String", { limit: 4, page: 3, locale: "fr"})
    console.log(mdn) //expected output is a meta and documents
    console.log(mdn.cache) //To access the cache of documents
})

```