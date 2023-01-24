### Structure web pages with HTML

## Wireframes and Design

We create wireframes and designs before coding for a web page, as it allows us to plan ahead. Additionally, having a solid reference of your ideas/vision allows you to work quicker as well as to illustrate your ideas better to other people.

_Things to keep in mind:_

- Wireframes can be created by hand (sketching) or digitally (through websites such as [figma](https://www.figma.com/))

- It's best to keep initial designs simple, I want to master the core concepts without overwhelming myself.

- Try to think about how you would like the user to navigate your page

## HTML

HTML(.html) is a markup language like Markdown(.md). It is considered the backbone of a website, containing all the core information.

You build your page using elements called <tags>

**The basic structure of a HTML file would consist of:**

- **<head></head>:** Head tags contain the 'background' information for the website.
- **<body></body>:** Body tags contain all the text and information of the web page that is visible.
- **<header></header>:** The first sub-section of the body. For banners for example.
- **<main></main>:** The second sub-section of the body.
- **<footer></footer>:** Last sub-section of the body. Footer tags contain the sub text of the website, such as copyright info.

![htmlStructure](https://zellwk.com/images/2014/03/3-2.jpg)

**Common HTML element tags**

- **_<li>_** List Item Element
  The **_<li>_** list item element create list items inside:

  - Ordered lists <ol>
  - Unordered lists <ul>

- **_<video>_** Video Element
  The **_<video>_** element embeds a media player for video playback. The src attribute will contain the URL to the video. Adding the controls attribute will display video controls in the media player.

  Note: The content inside the opening and closing tag is shown as a fallback in browsers that don’t support the element.

        <video src="test-video.mp4" controls>
        Video not supported
        </video>

- **_<em>_** Emphasis Element
  The **_<em>_** emphasis element emphasizes text and browsers will usually italicize the emphasized text by default.

- **_Attribute Name and Values_**
  HTML attributes consist of a name and a value using the following syntax: name="value" and can be added to the opening tag of an HTML element to configure or change the behavior of the element.
  <elementName name="value"></elementName>
