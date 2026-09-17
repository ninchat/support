---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/2uaSodGerm08OIAGW4lA/julkiset-ryhmakeskustelut/embedding-group-discussion
---

# Embedding a group discussion on a website

You can embed a public group discussion on a website, mobile site or application, blog, or Facebook page.

## Chat embed code

For embedding, we provide the embed code when the chat is ready. We configure the chat according to your requirements; you only need to place the embed code on your website.

The public group discussion is usually placed within the website content, for example inside a div element. Embedding requires 1) a container element with the correct ID and 2) an embed script tag. The embed code is a one-line JavaScript tag that we provide for your chat.&#x20;

The customer or the website developer must place these code snippets on the website.

The style, position, and size of the container element are entirely up to you. The example below shows a short style definition and example embed code.

```markup
<div id="ninchat-groupchat-container" style="width: 100%; height: 500px; border: solid 1px #000;"></div>
...
<script src="http://ninchat.com/[...]/ninchat-public-init.js" charset="UTF-8"></script>
```

### Placing the embed code

Place and style the container element as desired. We can help with styling if needed.\
We recommend placing the embed script tag at the end of the website's body element. For example:

```markup
        <section id="groupchat" class="page-section">
           <!-- Ninchat group discussion element -->
           <div id="ninchat-groupchat-container"></div>
        </section>
        ...
        <!-- Ninchat-upotus-script -->
        <script src="http://ninchat.com/[...]/ninchat-init.js" charset="UTF-8"></script>
    </body>
</html>
```

{% hint style="info" %}
If the website uses both a private customer service chat and a public group discussion, they must be initialized with the same embed script tag. A page cannot contain multiple embed codes, as this will interfere with the chats.
{% endhint %}

## What the customer should decide <a href="#what-the-customer-should-decide" id="what-the-customer-should-decide"></a>

* On which page(s) will the group discussion appear, and will the same page also use a private customer service chat?
* Should the group discussion be placed within the page content or in a floating window?
* What should happen when the group channel is closed: should conversation history be hidden or shown, should only a closed message be displayed, or should the entire window be hidden?
