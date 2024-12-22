# <ins>Lessons learned</ins>

float: left on the CSS made the site formatting a bit iffy. Changed to center.

.htaccess file created and killed website. Used a different ftp client to access and delete (because net2ftp would not allow me).

Adding in semantic html (nav, main, sections, etc) allows more fine-grained usage of CSS whilst also making html more readable (and thus more likely to interpret accurately) for browsers.

## **SEMANTIC HTML**

- header, nav , main and footer create the basic structure of the webpage.
- section defines elements in a document, such as chapters, headings, or any other area of the document with the same theme.
- article holds content that makes sense on its own such as articles, blogs, comments, etc.
- aside contains information that is related to the main content, but not required in order to understand the dominant information.
- figure encapsulates all types of media.
- figcaption is used to describe the media in figure.
- video, embed, and audio elements are used for media files

## <ins>Editing in real time</ins>
Using Dev tools on the browser, we can adjust the source code for a given element by right clicking and choosing inspect (diff sheets can be found on source tab). The changes are shown in the browser but the seesion is local and temp so changes are not perpetual.
This means changes can be made but any screw ups aren't permanent. Copy what you like to add to the proper docs later 🙌
