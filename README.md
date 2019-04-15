# icu-test

## Solution
1. Install ```full-icu``` module
2. Use path to ```full-icu``` module:
    * **option A:** use parameter when running  ```node``` executable: 
    
    ```bash
    node --icu-data-dir=./node_modules/full-icu index.js
    ```
    * **option B:** use environment variable 
       
    ```bash
    env NODE_ICU_DATA=/some/directory/node_modules/full-icu node
    ```

## PoC

1. Clone this repo
```
https://github.com/mzezin/icu-test.git
```
2. Install dependencies (```full-icu```)
```
npm run i
```
3. Run ```node``` w/o icu support
```
npm run no-icu
```
3. Run ```node``` with icu support
```
npm run full-icu

```


## Source
https://nodejs.org/dist/latest-v8.x/docs/api/intl.html    