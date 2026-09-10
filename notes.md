### API 
---
```Application programming interface that enables communication bw different applications```


### Webfundamentals
---

## client server architeture
    ```client sends an http request to server, server process the http request and send back http response ```

### http_methods
---
`GET` => fetch all resources  
`POST` => create an new resource  
`PUT` => update a resource  
`PATCH` => UPDATE a resource (partial update)  
`DELETE` => delete a resource  


### http_request_format
---

`url`  
`http_method`  
`Authorization`  
`body`  

### sample api end point
---

```
Employee

id  name    age   department  salary

1   haris    23          hr      25000
2   vipin    23          qa      25000
3   jithn    23          it      25000
4   rahul    23          hr      25000

```

```
http_request for adding employee

url: localhost:8000/employee/
method:POST
body:{
    "name":"vysak",
    "age":24,
    "department":"hr",
    "salary":45000
}



```
---
```
http_request for listing employee

url:localhost:8000/employee/
method:GET

```

---
```
http_request for fetching specific employee detail

url : localhost:8000/employee/4/
method:GET

```

```
http_request for updating an employee 

url:localhost:8000/employee/4/
method:PUT
body:{
    "name":"Rahul",
    "age":24,
    "department":"hr",
    "salary":30000
}

```

```
http_request for deleting  specific employee 

url:localhost:8000/employee/4/
method:DELETE
```

### Movie task

```
Movie

id      title      year     language        run_time


1          kgf1      2008      kannada           160
2          kgf2      2020      kannada           165
3          kgf3      2026      kannada           167
4          kgf4      2028      kannada           168
5          kgf5      2030      kannada           169
```

`http_request for adding new movie`
url: localhost:8000/movie/  
method:POST  
body:{title:"RRR",  
year:2025,  
language:"Telugu",  
run_time:180   
}  

`http_request for list all movie`
url: localhost:8000/movie/  
method:GET  
`http_request for fetching movie detail`  
url: localhost:8000/movie/3  
method:GET  

`http_request for update movie`  
url:localhost:8000/movie/4  
method:PUT  
body:{  
    title:"Kgf4",  
    year:2025,  
    language:"Telugu",  
run_time:180  
}  

`http_request for delete movie`

url:localhost:8000/movie/4  
method:DELETE  



patients

|id|patient_name|phone_number|assigned_doctor|department|    appointment_date|  consultation_fee| 
  
|1 |  Anu       |  9876542319|   Dr.Alice    |Dermatology|      2026-05-01   |     250.00       |

|2 |  Rahul     |  9976442319|  Dr.Smith     |Cardiology |      2026-06-01   |    350.00        |

|3 |  Meera     | 9207542334|   Dr.John      |Neurology  |    2026-05-10     |   300.00         |

`http_request for adding new patient`
url: localhost:8000/patients/  
method:POST  
body:{patient_name:"Teena", 
phone_number:"9207066221"
assigned_doctor:"Dr.Smith"
department:"Cardiology" 
appointment_date:"2026-06-15"
consultation_fee:350.00     
}  

`http_request for list all patients`
url: localhost:8000/patients/  
method:GET  
`http_request for fetching patient detail`  
url: localhost:8000/patients/2 
method:GET  

`http_request for update patient`  
url:localhost:8000/patients/2   
method:PUT  
body:{patient_name:"Rahul" 
phone_number:"9922562319"
assigned_doctor:"Dr.Smith"
department:"Cardiology"  
appointment_date:"2026-08-01"
consultation_fee:350.00 
}  

`http_request for delete patient`

url:localhost:8000/patients/2  
method:DELETE  