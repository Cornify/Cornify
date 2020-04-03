# Cornify is the worlds #1 unicorn and rainbow service provider.

The Cornify script gives you the magical power to put unicorns and rainbows on any website on the Internet. Since 2009, it has served over 400 million unicorns and rainbows. How wonderful indeed.

# Installing the Cornify script

To add the Cornify script to your website, include this script tag in your HTML:

~~~html
<script type="text/javascript" src="https://www.cornify.com/js/cornify.js"></script>
~~~

# Using it

Then you can cornify at will with the following Javascript code:

`cornify_add();`

For example, if there's a link and you want to pop a unicorn or rainbow when people click it, you can set it up like this:

~~~html
<a href="#" onclick="cornify_add();return false;">Click for happiness!</a>
~~~

You can also use a colorful rainbow Cornify button like this:

~~~html
<a href="https://www.cornify.com" onclick="cornify_add();return false;">
  <img src="https://www.cornify.com/assets/cornifycorn.gif" width="52" height="51" border="0" alt="Cornify" />
</a>
~~~

# Summing Younicorns

These days, you can create your own personal unicorns on Cornify. They are called Younicorns. If you want the Cornify script to show your Younicorns, you can provide a list of Younicorn IDs to the script, like this:

~~~javascript
cornify_add({ younicorns: "12,957,826,716,386" });
~~~

To find the IDs, navigate your browser to a Younicorn page and look at the URL. It will include a number - that's the ID.
