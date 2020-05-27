# Markdown versus word processors

Markdown is a plain text format for writing structured documents for the web.

Word processors are rich text editors that typically target printed output. Common word processors in use within the Department for Education are Google Docs, Microsoft Word, Atlassian Confluence and LibreOffice Writer.

They allow documents to be independently-styled and support many advanced features like:

* tables of contents
* macros
* full control of fonts and colours
* control of margins, columns, gutters, headers and footers
* typography options like [kerning](https://en.wikipedia.org/wiki/Kerning), [leading](https://en.wikipedia.org/wiki/Leading) and [tracking](https://en.wikipedia.org/wiki/Letter-spacing)
* comments and highlighting

_Note that all of these will be stripped when publishing via a CMS._

## The separation of content and style

When documents are published on the web their content and style are usually created and stored separately. This approach has many benefits including:

* simpler documents, no need for editors to worry about formatting
* an easier publishing process - no need to strip the styles from a word processing document and reapply formatting used by the CMS
* the look and feel of websites can be modified without affecting the content
* it's the approach already taken by GDS. The [Whitehale publishing platform](https://www.gov.uk/guidance/how-to-publish-on-gov-uk/introduction-and-access-to-whitehall-publisher) uses a variant of Markdown called [GovSpeak](https://github.com/alphagov/govspeak) throughout
* no ties to a particular set of tools, any text editor can be used

### When to favour markdown and version control

Favour markdown and version control whenever:

* you're targetting a web audience
* the document is [long-lived](https://en.wikipedia.org/wiki/Living_document)
* collaboration with other editors is important
* a full audit trail might be advantageous
* sign-off is needed
* your team is already using git

### When to favour a word processor

Favour a word processor when:

* the document is intended to be short-lived and you're working alone
* the target is print or PDF
* more advanced typesetting options are needed
* you _need to_ collaborate with people already using office suites
