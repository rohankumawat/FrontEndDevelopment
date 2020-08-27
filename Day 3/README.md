## HTML Head

The head's content is not displayed on the page. it's job is to contain the metadata about the document.

## Title

This is used to add a title to the document. **h1** element and title are different.

The **h1** element appears on the page when loaded in the browser — generally this should be used once per page, to mark up the title of your page content (the story title, or news headline, or whatever is appropriate to your usage.)

The <title> element is metadata that represents the title of the overall HTML document (not the document's content.)

## Metadata (<meta> element)

Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the <meta> element.

```
<meta charset="utf-8">
```

This element simply specifies the document's character encoding — the character set that the document is permitted to use. utf-8 is a universal character set that includes pretty much any character from any human language. This means that your web page will be able to handle displaying any language; it's therefore a good idea to set this on every web page you create!

Many <meta> elements include name and content attributes:

* name specifies the type of meta element it is; what type of information it contains.
* content specifies the actual meta content.

Example:

```
<meta name="author" content="Chris Mills">
<meta name="description" content="The MDN Web Docs Learning Area aims to provide
complete beginners to the Web with all they need to know to get
started with developing web sites and applications.">
```

Specifying an author is beneficial in many ways: it is useful to be able to understand who wrote the page, if you have any questions about the content and you would like to contact them. Some content management systems have facilities to automatically extract page author information and make it available for such purposes.

**The Open Graph protocol**

The Open Graph protocol enables any web page to become a rich object in a social graph. For instance, this is used on Facebook to allow any web page to have the same functionality as any other object on Facebook.

## Custom Icons to your site

A favicon can be added to your page by:

1. Saving it in the same directory as the site's index page, saved in .ico format (most browsers will support favicons in more common formats like .gif or .png, but using the ICO format will ensure it works as far back as Internet Explorer 6.)
2. Adding the following line into your HTML's <head> block to reference it:

```
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

## Setting the primary language of the document

```
<html lang="en-US">
```

## Why do we need symantics?

Semantics are relied on everywhere around us—we rely on previous experience to tell us what the function of an everyday object is; when we see something, we know what its function will be. So, for example, we expect a red traffic light to mean "stop," and a green traffic light to mean "go." Things can get tricky very quickly if the wrong semantics are applied. (Do any countries use red to mean "go"? I hope not.)

## What is a hyperlink?

Hyperlinks are one of the most exciting innovations the Web has to offer. They've been a feature of the Web since the beginning, and are what makes the Web a web. Hyperlinks allow us to link documents to other documents or resources, link to specific parts of documents, or make apps available at a web address. Almost any web content can be converted to a link so that when clicked or otherwise activated the web browser goes to another web address

