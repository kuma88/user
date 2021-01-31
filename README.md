# simpleCrud
install mongodb
npm run start in localhost port 8000

execute GET request in postman via URL http://localhost:8000/info

execute POST request in postman via URL http://localhost:8000/info
#Eg
{
"Title": "Rainy Day",
"Post": "Today was a really rainy day"
}

execute put request in postman via URL http://localhost:8000/info/edit
#
{
    "_id": "601595d572b72a164c7d755d",
    "Title": "Very Hot Day",
    "Post": "Today was a really hot day"
}

execute delete request in postman via URL http://localhost:8000/info/del/601595d572b72a164c7d755d
#
{
    "_id": "601595d572b72a164c7d755d",
    "Title": "Very Hot Day",
    "Post": "Today was a really hot day"
}
