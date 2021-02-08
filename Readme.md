            
            .  .     .               .   .                                   .
            |\ |     |               |   |                                   |             o  ,- o
            | \| ,-: |-  . . ;-. ,-: |   | ,-: ;-. ,-: . . ,-: ,-: ,-.   ,-. | ,-: ,-. ,-. .  |  . ,-. ;-.
            |  | | | |   | | |   | | |   | | | | | | | | | | | | | |-'   |   | | | `-. `-. |  |- | |-' |
            '  ' `-` `-' `-` '   `-` '   ' `-` ' ' `-| `-` `-` `-| `-'   `-' ' `-` `-' `-' '  |  ' `-' '
                                                   `-'         `-'                           -'
# Introduction
This package is to classify the sentenses into two categories.

![](./db/header.png)

# API example
```python
import requests
import json
url = 'https://freewebservices.herokuapp.com/Request'
headers = {'content-type': 'application/json'}
query=json.dumps({"_id":"1","textBody":"Could you give details of device"})
output = requests.post(url, data = query,verify=True,headers=headers)
```
 
# Author
Ashish Kumar

# License
MIT License
Copyright (c) 2020 Ashish Kumar

# Credit
Data science open source community

# Contributors
<a href="https://github.com/ashishkrb7/Natural-Language-classifier/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ashishkrb7/Natural-Language-classifier" />
</a>
