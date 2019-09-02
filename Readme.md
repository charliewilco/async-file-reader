# async-file-reader

Simple function to use [FileReader API](https://developer.mozilla.org/en-US/docs/Web/API/FileReader) as async.


```sh
yarn add @charliewilco/async-file-reader
```

Usage:

```ts
import asyncFileReader from "@charliewilco/async-file-reader"

const contents: string | ArrayBuffer  = await asyncFileReader(file)  
```

