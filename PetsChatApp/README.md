# PetsChat

Modify app/common/config.js

```
qiniu: {
  video: 'http://video.iblack7.com/',
  thumb: 'http://video.iblack7.com/',
  avatar: 'http://o9spjqu1b.bkt.clouddn.com/',
  upload: 'http://upload.qiniu.com'
},
cloudinary: {
  cloud_name: 'gougou',  
  api_key: '852224485571877',  
  base: 'http://res.cloudinary.com/gougou',
  image: 'https://api.cloudinary.com/v1_1/gougou/image/upload',
  video: 'https://api.cloudinary.com/v1_1/gougou/video/upload',
  audio: 'https://api.cloudinary.com/v1_1/gougou/raw/upload',
}
```

change to my own path


Updata to RN 0.36.0

1. Edition

- `nvm use v6.10.0 && nvm alias default v6.10.0`
- `npm i react-native-cli@1.0.0 -g`

2. Dependency

```
rm -rf node_modules && npm i
```

3. Updata Model

react-native upgrade


4. Update Clock Model

修改 node_modules/react-native-sk-countdown/CountDownText.js

```
import React,{Component} from 'react'

import {
  StyleSheet,
  Text,
} from 'react-native';

var update = require('react-addons-update')
var countDown = require('./countDown')
```
