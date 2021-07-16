# Introduction to Active Record Associations

Previously, we worked through object-relational mapping and building Ruby
classes that can represent SQL records. We also saw how Active Record is an
interface that gives you the tools to link a database to your application. It
lets you query and manipulate your data models in a logical and nearly
plain-English way.

So far, we've worked with applications that only have a single model. However,
as we saw in the SQL section, it's possible for data to be stored in multiple
related (associated) tables. How can we use Active Record to access that data
across multiple tables?

We'll cover topics that will include answers to these questions:

- What are common methods accessible through Active Record associations?
- How do you use association macros?

Having a solid understanding of Active Record will make working with data much
easier. This will replace the need for a lot of the custom code we wrote in when
creating ORMs. We’ll cover working with models, setting them up, and building
associations between them.
