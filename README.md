# GraphQL/REST API Documentation



--
# SDK Documentation (work in progress)
## Specifications
- Node version: 14
- npm link: -

## Installation

Use the package manager [npm]() to install foobar.

```bash
npm install trending-news-sdk // not yet added
```

## Usage

```javascript
/** eslint-ignore */
require('dotenv').config()
import * as ads from 'trending-news-sdk' //es6
const ads = require('trending-news-sdk') //es5

//iife for initialization
const {
USERNAME: string,
PASSWORD: string,
} = process.env

const config: {username: string, password: string} = {
username: USERNAME,
password: PASSWORD. 
}

(
async () => 
await ads.config(config)
)()
```


## Contributing
## License
[MIT](https://choosealicense.com/licenses/mit/)
