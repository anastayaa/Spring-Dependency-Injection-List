# Spring-Dependency-Injection-List
Spring Setter Injection with Dependent Object

Setter Injection with List

If we have dependent object in the collection, we can inject these information by using the ref element inside the list, set or map. Here, we will use list, set or map element inside the property element.

In this project, we are using list that can have duplicate elements, you may use set that have only unique elements. But, you need to change list to set in the applicationContext.xml file and List to Set in the Question.java file.

One question can have multiple answers. But Answer has its own information such as answerId, answer and postedBy.
