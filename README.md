GO-CRUD

POST create-user :

localhost:8080/create-user

Body raw(json)
{

    "id" : 1750,
    
    "first_name" : "rupai",
    
    "last_name" : "last_name",
    
    "country" : "Afganistan",
    
    "profile_picture" : "www.rupai.org.com"
    
}


PATCH update-user :

localhost:8080/update-user?id={id}

Body raw(json)
{

    "country" : "India"
    
}


DELETE delete-user :

localhost:8080/delete-user?id={id}

