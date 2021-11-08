# global-storage

- Its a package that helps you to store the data globally so that you can access from any file you want. It is made with javascript. If you are using it in the nodejs server the data will exist until you restart the server. If you are using in the APIs/MicroServices/Serverless kind of frameworks data will exists per the request.

## Installation
`npm i global-storage`


## Example
```
import storage from 'global-storage'
//or
//const storage = require('global-storage')

<!-- For storing/updating an item -->
storage.setItem('uniqueKey','Value')

<!-- For getting a stored item -->
storage.getItem('uniqueKey')

<!-- For removing a stored item -->
storage.removeItem('uniqueKey')

```