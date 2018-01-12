# steem-share
Add a 'share to steem' button to your website! Check the [example here](https://code-with-sam.github.io/steem-share/dist/example.html)

![Share To Steem](https://i.imgsafe.org/7f/7f9ecb420b.png)

Steem-share is a small javascript plugin that allows users to post content from your site onto their steem feed. It helps you as an author get more exposure and it helps the steemian share their favourite content for more rewards.

## Setup
Include the css & html files within your website. You can download them in this repo or link to them directly. 

```
<link rel="stylesheet" href="https://raw.githubusercontent.com/code-with-sam/steem-share/master/dist/steem-share.min.css">
<script src="https://raw.githubusercontent.com/code-with-sam/steem-share/master/dist/steem-share.min.js"></script>
```

Place the html button anywhere in your code and fill in the required information. 

```
<button class="ss-steem-share ss-steem-share-style"
data-title="This is a test from steem share"
data-category="testing-testing"
data-image="https://i.imgsafe.org/a7/a751d45421.jpeg"
data-content="Well would you look at that, I think this will be a pretty cool addition to the eco-system"
data-credit="<center>This post by @sambillingham was shared from [SteemShare](http://websitelink) Using Steem Share</center>"
>Share To Steem</button>
```

Don't want to use the default styling? No problem. Remove the class ```ss-steem-share-style``` from the button and you can style the button however you would like.

## How
When a user clicks on the steemshare button a modal will open for the user to enter their steem username. After entering a username the user clicks 'post with steemconnect' where they are prompted to login and sign the transaction. 

![modal](https://i.imgsafe.org/7f/7f9ecb3764.png)


