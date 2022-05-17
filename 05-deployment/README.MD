# Deployment

You can see the deployment in the hosting Heroku. the url is [churn-service-jhcs.herokuapp.com](https://churn-service-jhcs.herokuapp.com)`.

To make a request you can run this code:


```

import request

url = 'https://churn-service-jhcs.herokuapp.com/predict'

customer = {"contract": "two_year", "tenure": 12, "monthlycharges": 10}

requests.post(url, json=customer).json()
```
