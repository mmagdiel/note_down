# Note ⬇️
A blogging headless platform has based on git persistence 

It has been inspired by the blog system the [Ghost](https://ghost.org/) but providing greater flexibility to be used by static page generators such as  [Next.js](https://nextjs.org/), [Hugo](https://gohugo.io/), [Gatsby](https://www.gatsbyjs.com/), among others.

## *For the minimum viable product it is expected to control a local repository*

### Esencial Domain Definitions:
- Message: Text to communicate an action, definition or status to the user. It should be parameterizable
- Note: Yaml document file 
- Page: Markdown document file 
- Frontmatter: metadata for page or notes
- Book: A collection of pages
- Block: A collection of page or notes
- Blotter: A collection of notes

### Feature list for MVP
- [ ] It create a components library.
- [ ] It update the original design for new feature.
- [ ] It create a folder or file by demand.
- [ ] It commit a file with a default message of file type by demand.
- [ ] It create folder config with files: tags, frontmatters, templates by demand.

- [ ] It save default tag template pair fields-message: name, description and color. 
- [ ] It save default frontmatter template pair fields-message: name, description, type, creation date, update date and a list of tags. 
- [ ] It save default template pair fields-message: name, description and list of tags. 

- [ ] User can create a book with a title unique that he only can create pages
- [ ] User can create a block with a title unique that he can create pages or notes
- [ ] User can create a blotter with a title unique that he only can create notes
- [ ] User can delete a book if there aren't pages on that collection 
- [ ] User can delete a block if there aren't pages or notes on that collection 
- [ ] User can delete a blotter if there aren't pages on that collection 

- [ ] User can create a template tag. The field name and color are requerired and unique
- [ ] User can create a template frontmatter. The field name and type are requerired and unique
- [ ] User can create a template. The field name is requerired and unique
- [ ] User can delete a template tag
- [ ] User can delete a template frontmatter
- [ ] User can delete a template

- [ ] User can save a tag. The name field must be unique at list of tags.
- [ ] User can update a tag. The name field cannot be used in any frontmatter or templates.
- [ ] User can delete a tag. The name field cannot be used in any frontmatter or templates.
- [ ] User it's about updating or deleting a tag then the user should be notified that the tag is being used and by which entities they are used.
- [ ] User can list tags allowing a tag to be viewed, updated and deleted.
- [ ] User can show a tag together a frontmatters and templates that used it.

- [ ] User can save a frontmatter. The name field must be unique at list of tags.
- [ ] User can update a frontmatter. The name field cannot be used in any notes or pages.
- [ ] User can delete a frontmatter. The name field cannot be used in any notes or pages.
- [ ] User it's about updating or deleting a frontmatter then the user should be notified that the tag is being used and by which entities they are used.
- [ ] User can list frontmatters allowing a template to be viewed, updated and deleted.
- [ ] User can show a frontmatter together a note and pages that used it.

- [ ] User can save a template. The name field must be unique at list of tags.
- [ ] User can update a template. The name field cannot be used in any note o page.
- [ ] User can delete a template. The name field cannot be used in any note o page.
- [ ] User it's about updating or deleting a template then the user should be notified that the tag is being used and by which entities they are used.
- [ ] User can list templates allowing a template to be viewed, updated and deleted.
- [ ] User can show a template together a note and pages that used it.

- [ ] User can save page together its frontmatter
- [ ] User can list pages by theirs frontmatter
- [ ] User can view a page together its frontmatter
- [ ] User can update a page or its frontmatter
- [ ] User can delete a page

- [ ] User can save note together its frontmatter
- [ ] User can list note by theirs frontmatter
- [ ] User can view a note together its frontmatter
- [ ] User can update a note or its frontmatter
- [ ] User can delete a note