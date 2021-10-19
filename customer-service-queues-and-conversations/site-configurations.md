---
description: Customer chat configurations
---

# Site configurations

## Overview <a href="yleista" id="yleista"></a>

The Organization settings, _Sites_ tab, is where the settings, texts, translations, and styles, for the customer service chats and public group chats, are defined. To access the configuration, go to your organization settings and select the _Sites_ tab.

{% hint style="info" %}
Site configuration is an advanced user feature. Ask Ninchat staff to help or make changes for you if you find it difficult.
{% endhint %}

![](<../.gitbook/assets/Organization - sites.png>)

## Edit chat texts

Click the pencil icon on the right to open the configuration.

In the edit view, you will see the chat settings, texts, and translations. You can change them as you like. HTML elements such as _\<p>\</p> _(paragraph) and _\<br>_ (line break) may appear in the texts. In multilingual implementation, different languages have their own text elements.

#### The most common texts to edit

| Element                   | Description                                                                  |
| ------------------------- | ---------------------------------------------------------------------------- |
| welcome                   | Content at the top of the chat initial view.                                 |
| motd                      | Content at the bottom of the chat initial view                               |
| noQueuesText              | <p>Content when chat is closed. <br>(Unless e.g. contact form is in use)</p> |
| inQueueText               | Queuing view text.                                                           |
| userName                  | Customer's username in the conversation.                                     |
| translations              | Common text definitions, i.e. translated into the language used.             |
| preAudienceQuestionnaire  | Initial chat request. (Or offline contact form)                              |
| postAudienceQuestionnaire | End chat request.                                                            |



#### Yleisiä käytettyjä HTML-elementtejä

| HTML-tag                                                                            | Description              |
| ----------------------------------------------------------------------------------- | ------------------------ |
| \<br>                                                                               | Line break               |
| \<p>text\</p>                                                                       | Paragraph                |
| \<h2>text\</h2>                                                                     | Title ( h1, h2, h3, h4 ) |
|  \<a href="https://address.com" target="\_blank" title="description">Link text\</a> | Hyperlink                |

Example: a Paragraph with text, line break and a link

```markup
<p>Here you'll find support docs<br><a href="https://address.com" target="_blank" title="Open Support site">Support site</a></p>
```

{% hint style="info" %}
Remember to save the changes
{% endhint %}

![](<../.gitbook/assets/Organization - sites – 1.png>)

## Disable chat <a href="chatin-ottaminen-pois-kaeytosta" id="chatin-ottaminen-pois-kaeytosta"></a>

You can disable the customer service chat completely by disabling the site configuration. In the edit view, click the "Disable" button. The configuration will then appear in the list with the status - Disabled. You can enable the chat again by clicking the "Enable" button in the edit view.

{% hint style="warning" %}
Do not disable configurations if you're unsure what you are doing.
{% endhint %}
