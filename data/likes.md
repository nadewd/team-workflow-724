also something we'd only use if we want to implement it 

Attributes: 
    subforum_id(fk)
    user_id(fk)

Notes: 
    just query objects that have the FK for that given subforum and return the "len()" of the querylist of user_ids 
