GitHub Revert Style
---
Reverts GitHub to before its latest major UI update.

Around a year ago GitHub introduced a bunch of style changes which made it look more roundish and decentred most of the
content displayed on the site. This style tries to revert some of these changes and make GitHub look similar to its old
style.

It currently does the following:
  * Centres repositories and their headers.
  * Gets rid of some rounded shapes which didn't exist before.
  * Aligns the status emoji's text a bit better.

### How to use
I took advantage of the Stylus browser extension which allows users to stylise any page they want using CSS which loads
along with the page itself. Here are downloads for the extension on Chrome or Firefox:
  1. [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en-GB)
  2. [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/styl-us/)

Once you install Stylus, simply follow these steps:

1. Add a new style to Stylus. Go to the extensions' manage tab and then write a new style.

![Step1](https://user-images.githubusercontent.com/26081543/202922103-96d29df9-312d-475a-98f2-537234c01eee.png)

2. Paste the content of `github-revert-style.css` into the new style. Click the '+' sign at the bottom and add a new
rule of the 'URLs on the domain' type. Then simply add `github.com` as the target domain. Click Save, and the snippet
should be ready to use!

![Step2](https://user-images.githubusercontent.com/26081543/202922115-0a91b667-0fae-4272-b7d2-27aca3988592.png)

### General Preview
How raw GitHub looks like:

![1](https://user-images.githubusercontent.com/26081543/202923012-ef01490d-7c81-4295-b607-d8b5e4cb3b66.png)

How it looks with this style:

![2](https://user-images.githubusercontent.com/26081543/202923016-b0c5caa3-0304-40b5-9ea2-2f43fd55df09.png)

### Notes
This is just meant to be a personal taste "rollback". I've had this style ever since GitHub changed its looks, and it
has survived quite well!

There are a few known issues I may address when I have time, but feel free to report them on the
[Issues](https://github.com/BGMP/github-revert-style/issues) tab and I'll likely get to them sooner!
