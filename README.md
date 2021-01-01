pdo_hunter => Less code. Save time. 

AUTHOR: Chamith Nimmitha

DESCRIPTION:
  This is a simple php tool can used to connect and query mysql databases and return result without writing queries.
    NOTE : This tool works only for simple queries. (simple query means without join or advanced query)
    
    
FUNCTIONALITIES : 
  select()      ==> write a SELECT query
  insert()      ==> write a INSERT query
  update()      ==> write a UPDATE query
  delete()      ==> write a DELETE query
  order_by()    ==> add ORDER BY property
  group_by()    ==> add GROUP BY property
  limit()       ==> add LIMIT            
  get()         ==> get only specific fileds in select query
  where()       ==> set where option in query
  pure_query()  ==> write any query. This method use for situation that above methods cant used. 
  
  // useful for pagination
  count_and_select()  ==> select data and calculate count without limit option
  get_count()         ==> get row count acording to previously execute query in count_and_select() method
   
  // for transaction management
  begin()     ==> begin tansaction
  commit()    ==> commit transaction
  rollback()  ==> rollback transaction
  
  
 
  LICENSE:
    MIT LICENSE
  
  
