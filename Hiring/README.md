# Instructions
Fork this repository and add your code in a subfolder under the "Hiring" folder. 

Submit a pull request. 

## Your Task

Create a web application that has the following component
1. Server side component written in Java that expose 2 REST API's
    1. A GET API that will fetch gold price data from AirTable base named [Bank Info](https://airtable.com/shrLW24i9g40XV9Ab) and return any one row of the data as a JSON. If you do not have Airtable account then please use this [invite link to sign in and get access to Bank  Info Base](https://airtable.com/invite/l?inviteId=invdd9vtsjikYkFym&inviteToken=f352ba8e45be5663a75f76d4e51ef3da6cb7407d5cb3a6a98cf849b09a422ad5). For the GET API and API Token needed to make the call refer to [AirTable Documentation](https://airtable.com/api)
    2. A POST API that will insert the JSON data argument into a MySQL database

2. Client side component
    1. An HTML page that use Angular to fetch data and display it by calling a the above mentioned GET API. The API should be invoked when a button on the page is clicked. The data should be displayed in tabular form.
    2. There should be a submit button below the data table which when clicked should call the POST API mentioned above to save the data.



You can also shoot us an email to hr@finahub.com to inform us 
