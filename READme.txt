HTML- hyper text markup language

<!DOCTYPE html>- This declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.
<html></html>- It represents the root of an HTML document.The <html> tag is the container for all other HTML elements,parent tag of head and body tag.

<head></head>- container tag containing metadata of webpages, child tag of html.
        elements:
        <title>- (required in every HTML document)
        <style>- tag is used to define style information (CSS) for a document.
        <base>- It specifies the base URL and/or target for all relative URLs in a document.The <base> tag must have either an href or a target attribute present, or both.
        <link>- defines the relationship between the current document and an external resource, mainly a stylesheet.
        <meta>- Metadata is data about the HTML document. Metadata is not displayed.Metadata typically define the document title, character set, styles, scripts, and other meta information
                <meta charset="UTF-8">
                <meta name="description" content="Free Web tutorials">
        <script>- used to embed a client-side script (JavaScript).
        <noscript>- It defines an alternate content to be displayed to users that have disabled scripts in their browser or have a browser that doesn't support script. 

<body></body>- It defines the document's body.It contains all the contents of an HTML document.
        The tags written inside body tag will display in the order in which they are written.
        elements:
        
        BASIC TAGS
            <H1></H1>- heading tag which is a container tag, size varies from H1 to H6.
            <hr>- Horizondal line
            <p></P>- paragraph
            <b></b>- bold
            <i></i>- italics
            <br>- break
            <big></big>- make text size bigger
            <small></small>- make text size smaller
            <sub></sub>- for subscript
            <sup></sup>- for superscript
           
        PAGE FORMATTING TAGS
            every html page can be devided into 3 parts
            <header></header>- it represents a container for introductory content or a set of navigational links.
                 <nav></nav>-  it defines a set of navigation links.
            <main></main>-  main session of a website,it contains certain elements and articles.
                <sessio></session>- it is used to make different sessions in a webpage, and different sessions can also have diffferent headings
                <aside></aside>- it used to include any content that are not a part of the webpage like ads 
                <article></article>- used for adding a blog or an article.
            <footer></footer>- end session of a website, it may contain authorship information,copyright information,contact information,sitemap,back to top links,related documents.
       
        COLOR AND STYLE TAGS
            <H1 style="background-color:red">
            <H2 style="color:blue">
       
        LINK TAGS
            <a></a>- defines a hyperlink, which is used to link from one page to another.
                     href- indicates the link's destination.
                     target="_blank"- for opening in new tab.
        IMAGE TAGS
            can use <a> tag for inserting an img.
            width- used for giving a specific w for the img.
            height- used for giving a specific h for the img.
            (if only one of these values are given the img will automatically adjust athe not given value in accodence with the given value)
            src- for giving the location of img.
            alt- for giving an alternative text for the img if it is not displayed.
        
        VIDEO TAGS
            <video src="video.mp4"> - for giving video location
            <video src="video.mp4" poster="img.jpg"> - for giving the video thumpnails
            <video src="video.mp4" loop autoplay controls> - loop for looping the video, autoplay for automatically playing the video, controls for giving the basic control cmds.
            for including a video from youtube click the share option and click on embed and then copy paste the code into your webpage.
        
        LIST TAGS
            lists are mainly of three types
            <ol></ol>- just orders things in types like a,A,1 etc.
            <ul></ul>- never orders lists just put list items in bullets
            <dl></dl>- will have a data and a title part <dt>and<dl> respectively.
            embeded lists- ordinary list with another list inside.
        
        TABLE TAGS
            <table></table>- these tags are used to create tables.
            <thead></thead>,<tbody></tbody>- these tags are used to seperate a table into 2 manageable sessions head and body for better organizing the table session.
            <tr></tr>- these tags are used to make horizontal rows in a webpage.
            <th></th>- these tags are used to give table headings to column.
            <td></td>- these tags are used to enter data into a column.
                <td colspan="4">- it is used to give additional column spaces to a column. 

        DIV AND SPAN TAGS
            html has mainly two ways to represent an element (display types) they are BLOCK AND INLINE.
            BLOCK elements always takes the whole width of the screen. even if it doesnt use the space it cannot be used for another element.
            INLINE elements only takes the space they truley need, so if there is spacce left in after an element that can be used for another element.
            so some html tags are block tags(p tags) and some are inline tags(links).
            SPAN AND DIV tags are container tags that are used for wrapping other elements of same display type.
            SPAN are inline containers.
            DIV are block containers.
            so we can display many span tags in a single row and only one div tag can be displayed in a line.