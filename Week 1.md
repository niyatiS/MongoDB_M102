Homework 1.1
----
Answer: 
- 16777216

Homework 1.2
----
Answer: 
- 3

Homework 1.3
----
Answer: 
- db.products.find({brand:'ACME'})

Homework 1.4
----
Answer:
- var c = db.products.find({},{name:1,_id:0}).sort({name:1}); while( c.hasNext() ) print( c.next().name); 
- var c = db.products.find({}).sort({name:1}); c.forEach( function(doc){ print(doc.name) } ); 