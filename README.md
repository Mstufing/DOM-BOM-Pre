
## LECTURE 6
## TABLE OF CONTENTS

 1. DOM
 2. BOM
 3. EVENTS
 4. DOM METHODS



## What is **DOM** in **JavaScript**?
#### The **DOM** stands for (Document Object Method).

The **document object** represents the whole html document.

When html document is loaded in the browser, it becomes a document object. It is the **root element** that represents the html document. It has properties and methods. By the help of document object, we can add dynamic content to our web page.

#### Properties of document object

Let's see the properties of document object that can be accessed and modified by the document object.


![](/img/propertiesDom.png)


#### Methods of document object

We can access and change the contents of document by its methods.
The important methods of document object are as follows:

![](/img/methods.png)

#### Accessing field value by document object

In this example, we are going to get the value of input text by user. Here, we are using **document.form1.name.value** to get the value of name field.

Here, 
_**document**_ - is the root element that represents the html document.

_**form1**_ - is the name of the form.

_**name**_ - is the attribute name of the input text.

_**value**_ - is the property, that returns the value of the input text.

Let's see the simple example of document object that prints name with welcome message.

![](/img/exampleDOM.png)
