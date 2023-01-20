#NoSQL #Databases #Design 
Document-oriented Model can be classified as [[Aggregate-oriented Model]], so it inherits all its properties like consistency how-to.

# Document
A document is what stored in Document-oriented database, [[MongoDB]] for example.

# Usage
As documents are schema-less aggregates, they are good for flexible models
## Marketplace
We have a marketplace where sellers sell items to customers, and items can have own properties, like TV has a resolution, a book has its author, a shoes have size etc. So, you as a seller can set these properties and application will display them at the screen.
## Rich-text Editor
Let's assume we have a rich-text editor, and we want to implement a feature of export to different formats like HTML, Markdown etc. So our text model should be format-agnostic to make it easy to export to different formats, and rich text can have a deep structure like this file, or even more deeper than it. So, it's naturally fits to document-oriented model, because documents can contain a really deep structure.