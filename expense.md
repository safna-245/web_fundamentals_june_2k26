Expenses

id  title       amount  category    owner     payment_method
1   Bus ticket   70      Travel     Manu       Cash


`http_request for adding new expense`
url: localhost:8000/expenses/  
method:POST  
body:{  
title:"Shirt",
amount:350,
category:"Shopping",
owner:"Anu",
payment_method:"UPI"  
}  

`http_request for list all expense`
url: localhost:8000/expenses/  
method:GET  
`http_request for fetching expense detail`  
url: localhost:8000/expenses/2
method:GET  

`http_request for update expense`  
url:localhost:8000/expenses/2  
method:PUT  
body:{  
title:"Pant",
amount:450,
category:"Shopping",
owner:"Anu",
payment_method:"UPI"   
}  

`http_request for delete expenses`

url:localhost:8000/expense/2 
method:DELETE  