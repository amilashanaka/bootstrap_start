# bootstrap_start



# Install bootsrap

1. Install npm packege

```cil
npm init -y
```

2. install parcel
   
   ```shell
   npm install --save-dev parcel
   ```

3. install bootstrap using npm

```url
https://www.npmjs.com/package/bootstrap/v/5.3.3
```

```shell
npm install bootstrap
```

3. create folder

4. add 2 link to index.html
   
   ```html
    <link rel="stylesheet" href="./assets/scss/main.scss" >
   ```

<script type="module" src="./assets/js/main.js" ></script>

```
5. edit package.json

```json
{
  "name": "admin",
  "version": "1.0.0",
  "description": "",
  "source": "./src/index.html",
  "scripts": {
 "dev": "parcel",
 "build": "parcel build"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
 "@parcel/transformer-sass": "^2.12.0",
 "parcel": "^2.12.0"
  },
  "dependencies": {
 "bootstrap": "^5.3.3"
  }
}
```
