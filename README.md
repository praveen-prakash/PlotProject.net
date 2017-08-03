Welcome to the PlotProject.net wiki!

https://www.plotprojects.com/

Plot projects goal is to to provide an easy to use, but sophisticated solution that works for any kind of geofencing scenario and campaign. Targeting of customers in marketing has traditionally been very poor, but with Plot Projects, we have the opportunity to change that.

It's a wrapper of Plot projects Dashboard API hook https://admin.plotprojects.com/docs/api/v1/

Dashboard API Plot projects offer an API to add and modify geofences (locations) and notifications (campaigns) for the Plot plugin. When you want to manage the notifications using a visual interface then you can use our Dashboard.

Documentation about the API and the specific calls can be found at the full API documentation.

The API is located at the following URL: https://admin.plotprojects.com

All requests have a Basic Authentication header with the appId as username and the private key as password. You can find these under "Integrate Plugin" in our Dashboard.

All requests return content of type application/json in UTF-8 encoding. All PATCH and POST requests consume a body of type application/json in UTF-8 encoding.

Currently Plot projects API has a limit to the amount of request you can do of 10 per second. Exceeding this limit will result in an unsuccessful API call and an 429 Too Many Requests response.
