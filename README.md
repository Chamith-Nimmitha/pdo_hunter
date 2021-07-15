PDOHunter => Less code. Save time. 

AUTHOR: Chamith Nimmitha

DESCRIPTION:

    This is a simple php tool can used to connect and query mysql databases and return result without writing queries.
    NOTE : This tool works only for simple queries. (simple query means without join or advanced query)
    
    
FUNCTIONALITIES : 

    Implemented:
      select( table_name: String, where: ass_array )  ==> write a SELECT query
      insert( table_name: String, fields: ass_array )  ==> write a INSERT query
      update( tableName, updated_fields: ass_array, where: ass_array )  ==> write a UPDATE query
      delete( table_name: String, where: ass_array )  ==> write a DELETE query
      order_by( fields: (String| ass_array), order(optional): String )  ==> add ORDER BY property
      group_by( fields: array )   ==> add GROUP BY property
      limit(start: number, count(optional): number)  ==> add LIMIT            
      get( fields: array )  ==> get only specific fileds in select query
      where( conditions: ass_array )  ==> set where option in query
      pure_query( query: String, params(optional): array )  ==> write any query. This method use for situation that above methods cant used.
      set_table( table_name: String )  ==> Change table name
      get_next_auto_increment( table_name: String )  ==> Get next value of auto increment field in given table.

      # useful for pagination
      count_and_select( table_name: String, where: ass_array )  ==> select data and calculate count without limit option
      get_count()  ==> get row count acording to previously execute query in count_and_select() method

      # for transaction management
      begin()     ==> begin tansaction
      commit()    ==> commit transaction
      rollback()  ==> rollback transaction
     
    Todo:
      Add complex join query functionality
      
  
  
 
  LICENSE:
  
    MIT LICENSE
