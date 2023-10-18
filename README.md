GitHub Revert Style
---
GitHub Revert Style is a small stylesheet I designed after GitHub introduced a bunch of UI changes which made the site
look more roundish, and decentred most of the content displayed on the site. These styles revert some of these changes.

It currently does the following:
  * Centre repository headers.
  * Centre repository contents.
  * Centre user profile navigation.
  * Replace rounded shapes for smaller border radius (avatars, topic tags, label tags, etc.).
  * Align the status emoji's text.

### How to use
You may apply these styles by using a browser extension. For example, Stylus is a browser extension which allows users
to stylise any page they want using CSS that loads along with the page itself.

You may download Stylus here:
  1. [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en-GB)
  2. [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/styl-us/)

Once you install Stylus, simply follow these steps:

1. Add a new style to Stylus. Go to the extensions' manage tab and then write a new style.

![Step1](https://user-images.githubusercontent.com/26081543/202922103-96d29df9-312d-475a-98f2-537234c01eee.png)

2. Paste the content of `github-revert-style.css` into the new style. Click the '+' sign at the bottom and add a new
rule of the 'URLs on the domain' type. Then simply add `github.com` as the target domain. Click Save, and the snippet
should be ready to use!

![Step2](https://user-images.githubusercontent.com/26081543/202922115-0a91b667-0fae-4272-b7d2-27aca3988592.png)

### Notes
This is just meant to be a personal taste "rollback". I've used these styles ever since GitHub changed its looks and, to
be fair, they have survived the test of time quite well.

Feel free to report any issues on the [Issues](https://github.com/BGMP/github-revert-style/issues) tab. I'll likely get
to them sooner!
