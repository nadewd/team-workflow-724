or threads whatever we end up calling it 

Attributes: 
    company_id: (can be nullified if its a general topic)
    timestamp: date 
    title/topic: charfield 
    
    optional: 
    if we end up using likes, we will can probably just have to add an integerfield property that will default to zero and be set by a button which can act as a form for a POST req CRUD-ing the "likes" data model 
    if we wanted to implement some sort of sorting logic when we display subforums we could add a property that is just a number incremented by get requests for a unique session 
        -just need to add a line of code in the view function 
        -remember to set the meta class ordering : [-'property-name']