"Domain Modeling"
    -Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An object oriented model is the entity that stores data in properties and encapsulates behaviors in methods.
    -A domian model that's articulated well can verify and validate the understanding of a specific problem amoung various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technival and business terms.
    -Define a constructor and intialize properties, to define the same properties between many objects, you'll want to use a constructor function. Constructor functions are defined using a function expression. In other words, the variable is declared and then assigned a function with parameters.
    -When the function is called, the data inside these parameters are stored inside the properties respectively. Storing data within properties ensures any newly created object can access that data later.
    -After the constructor function two objects are instanitated with the new keyword and their properties are initialized by calling the constructor function. After being instantiated and initialized, these objects are stored inside the variables.
    -When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
    -Model its attributes with a constructor function that defines and intitializes properties.
    -Model its behaviors with small methods that focus on doing one job well.
    -Create instances using the new keyword followed by a call to a contructor function.
    -Store the newly created object in a variable so you can access its properties and methods from outside. 
    -Use a variable within methods so you can access the object's properties and methods from inside.
Html Chapter 6 - "Tables"
    -The <table> element is used to add tables to a web page.
    -A table is drawn out row by row. Each row is created with the <tr> element.
    -Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header )
    -You can make cells of  atable span more than one row or column using the rowspan and colspan attributes.
    -For long tables you can split the table into a <thead>, <tbody>, and <tfoot>.
    -Table headings, the <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row.
    -Even if a cell has no content you should still use a <td> or <th> element to represent the presence of an empty cell, otherwise the table will not render properly
    -Spanning colums, sometimes you may need the entries in a table to stretch across more than one column. The colspan attribute can be used on a <th> or <td> element and indicates how many columns that cell should run across.
    -Spanning rows, You may also need entries in a table to stretch down across more than one row. The rowspan attribute can be used on a <th> or <td> element to indicate how many rows a cell should span down the table.
    -Long tables, there are three elements that help distinguish between the main content of the table and the first and last rows: <thead>, <tbody>, and <tfoot>.
JavaScript Chapter 3 - "Functions, Methods, and Objects" (cont)
    -Creating an object: constructor notation, The new keyword and the object constructor create a blank object. You can then add properties and methods to the object.
    -Updating the object, to update the calue of properties, use dot notation or square brackets. They work on objects created using literal or constructor notation. To delete a property, use the delete keyword. 
    -Creating many objects: constructor notation. Sometimes you will want several objects to represent similiar things. Object constructors can use a function as a template for creating objects. First create the template with the object's properties and methods. You create instances of the object using the constructor function. The new keyword followed by a call to the function creates a new object. The properties of each object are given as arguments to the function.
    -This(it is a keyword) the keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.
    -Storing Data, In javascript data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a key.
    -Arrays are objects, arrays are actually a special type of object. They hold a related set of key/value pairs(like all objects), but the key for each value is in the index.
    