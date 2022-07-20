Put:

{
    "token": "90939173|-31949293760554447|90940253",
    "cmd": "PUT",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
        "id": "2",
        "name": "Rishi",
        "email": "Rishi@gmail.com",
        "mobileno": "9967827651"
      "marks":56
    }
}


{
    "token": "90939173|-31949293760554447|90940253",
    "dbName": "Student",
    "cmd": "GET_BY_KEY",
    "rel": "Student-Rel",
    "jsonStr": {
        "name": "Soniya"
    }

}  

{
    "token": "90939173|-31949293760554447|90940253",
    "cmd": "Update",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
       "3":{
         "id": "3"
        "name": "Raju",
        "email":"Raju@gmail.com",
        "mobileno": 7098162348

      },
       "2":{
         "marks":76,
         "name":"Rishi Kumar"
      },
       "1":{
         "marks":80
      }
   }
}
