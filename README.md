# Hengallery

Gallery of your sales (primary and secondary) of your Tezos NFT collection (minted on HEN or OBJKTCOM contract).

This code allow you to publish your gallery on netlify and hide my domain from your gallery.

# How to

1. You need a free github account and a free netlify account
2. Use the button below to clone and publish your own version of the gallery on netlify
3. Enter your wallet address when asked to by netlify

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/bikerworld/hengallery" target="_blank">
<img src="https://www.netlify.com/img/deploy/button.svg"/>
</a>


Once the site is published, you go to netlify control panel to change your site name in the "Site settings" section

# Embed in an existing site

If you just want to embed your gallery in an existing page of your  website, use the following HTML code:

```
<style>
  body {
    margin: 0;
    /* Reset default margin */
  }

  iframe {
    display: block;
    /* iframes are inline by default */
    background: #000;
    border: none;
    /* Reset default border */
    height: 550vh;
    /* Viewport-relative units */
    width: 100vw;
  }
</style>
<iframe src="https://nftbiker.xyz/onsale?wallet=YOUR_WALLET&hide=1&theme=COLOR"></iframe>
```

You must fill the ifram parameters :

- **YOUR_WALLET** must be replaced by your wallet address
- **COLOR** can be set to dark or white, if you want to force a specific color-scheme instead of using the default browser configured theme. If you don't want to force anything, leave this empty.
