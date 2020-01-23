# Embed group chat on website

You can place a public group chat on a website, mobile site and application, blog, or Facebook page.

## Chat embed code

For embedding, we provide you with a so called embed code when the chat is ready. We will customize and prepare the chat as you wish, all you have to do is to place the embed code on your desired website.

A public group discussion is usually placed as a part of contents of a web page, including div element. For embedding, you will need: 1\) a container element with the right identifier ID; 2\) an embed script tag. The embed code is a one-line Javascript tag \(we will provide you with your own code\).

You or your site developer should place these snippets on your site.

The style, location, and size of the container element are entirely up to you. In the example below, you can see a short example of style and embed code.

```markup
<div id="ninchat-groupchat-container" style="width: 100%; height: 500px; border: solid 1px #000;"></div>
...
<script src="http://ninchat.com/[...]/ninchat-public-init.js" charset="UTF-8"></script>
```

### Place the embed code

The container element is placed at the desired position and styled as you wish. We will assist with styling as needed. We recommend placing the embed script tag at the end of the body element of the web page. For example:

```markup
        <section id="groupchat" class="page-section">
           <!-- Ninchat-ryhmäkeskusteluelementti -->
           <div id="ninchat-groupchat-container"></div>
        </section>
        ...
        <!-- Ninchat-upotus-script -->
        <script src="http://ninchat.com/[...]/ninchat-init.js" charset="UTF-8"></script>
    </body>
</html>
```

{% hint style="info" %}
If a web page operates both a private customer service chat and a public group chat, they should be triggered with the same embed script tag. There should not be multiple embed codes on the same page, otherwise, the chat activities will be confused.
{% endhint %}

## What you should know <a id="mita-asiakkaan-tulee-selvittaa"></a>

* Which page\(s\) does the group chat come from and does the same page has private chat?
* Is the group discussion placed in the content of the page or as a floating window?
* What happens when the group channel is closed: hide chat history or leave it visible, show a closed status only, or hide the entire window?

### 

