# Week 5 Journal 3

- In simple terms what is a sub-document?

A sub-document is a document nested within another doucment. We can spot these by looking and seeing if a schema is nested within another schema. 

- When might you use a sub-document?

We might use a sub-document when something may have multiple things attached to it. In our reading example they used sub-documents for nesting a video game characters moves, each move is a sub-document that can be accessed on the character. Since it has no relation to anything else we would nest it in our character model. 

- How do you add to a collection of sub-documents? What about editing them?

We would create a nested object with the character and all its moves and then add that to the collection of sub documents. When we go to edit these documents we will want to find the document, retrieve the array within that document, change it and then save it. 