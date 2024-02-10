---
title: 'It is very easy to develop a website'
description: 'This blog post explains how to get started with web development'
pubDate: 'Aug 4 2019'
heroImage: '/post-images/post-1/blog-post-1-hero-image.png'
---

Trust me, I moved on from filling excel sheets for a living to developing websites for MNCs. It’s a desirable skill and a handy one at that to make a living. But it’s also (maybe) cathartic? I love designing. Be that posters, typography, characters, UI designs or websites. If you’re passionate about design, or just want to create a website, then let me tell you that two months from reading this, you can become a web developer. No matter your occupation, academic specialization or age (unless you’re old enough to read this and use a computer).

So, how does one make a website? And learn to do so in a month? Let’s answer those two questions separately, shall we? In a plain and simple way.

## So, Q1: How does one make a website?

A web browser (Firefox, Chrome, Safari etc.) can understand three languages: HTML, CSS and Javascript. All three have very-easy-to-learn syntax (the way you are supposed to write the code), that can be written in 3 separate files:

```
1. index.html
2. styles.css
3. action.js
```

The .html file is linked to the .css and .js files. All three work together to render your website. Once you have filled up all three files with the necessary lines of code, link them to one another in the .html file and open the .html file, you will see your website.

**With me so far?**
Yes. But I have a question. Why are there three separate programming languages?

**Nice one. Let’s delve a bit deeper into each shall we?**
Okay.

**HTML** is short for (takes a deep breath) Hyper Text Markup Language. As the name suggests, it’s used for representing text on the web. Text, images, videos. It will give structure to your websites. People learn better with examples, so here’s one. This is an HTML code that's written in `index.html`:

```html
<h1 id="heading">This is a tree</h1>
<p>Trees grow really tall</p>
<img
  src="http://s1.picswalls.com/wallpapers/2014/07/19/tree-wallpaper_111651755_73.jpg"
/>
```

And when you open it in your browser, this is how it will look:
![screenshot taken from a browser window of a tree](/post-images/post-1/tree_example.png)
I know, it looks stale. and basic. and boring. How do I make it look good you ask? You use CSS!

**CSS** is short for Cascading Stylesheets. True to its name, it will provide the style to your HTML code. It can select an HTML element (like `<h1>`, `<p>` or `<img>`) and render the look as per the code that you have provided in the .css file. Again, an example of CSS code:

```css
h1#heading {
  color: red;
}

p {
  color: blue;
  text-decoration: underline;
}

img {
  height: 500px;
  width: 500px;
  border: 5px dashed purple;
}
```

The result? Your `<h1>`, `<p>` and `<img>` Will be "beautified" like this:
![same image of the tree with a border around it](/post-images/post-1/tree_example_border.png)

And finally, JavaScript (long for JS). It will determine how the website will behave. Suppose you want an alert to be displayed when you click on the heading “This is a tree”? JavaScript will do it for you:

```js
document.getElementById("heading").("click", function{
 alert("You cliked on the heading!");
});
```

![same image of the tree with a border around it and an alert dialog shown](/post-images/post-1/tree_example_js.png)

Then you open the .html file, link the .css and .js files to it. Once you open the former, voila! You can see the website. Then you just need to buy a domain (yourwebsite.com) from a marketplace vendor called a DNS provider (GoDaddy.com or BigRock.in), buy some space online to “host” or keep your files and link your files to the domain you bought. And if a person from a country that’s miles away from yours types yourwebsite.com in their browser, they can view it. So, in just 5 minutes, you came to know how websites are made. Now how do you become an expert in a couple of months? That’s question 2.

## Q2: How to learn in two months?

Two words. Courses and Practice. By courses I mean either video tutorials on YouTube or paid ones on Udemy.com (I like the one by instructor Colt Steele). There are multiple resources online as well. MDN Docs and W3Schools are good starting points.

And practice. An hour a day. Or two at the most. You can start by recreating the examples I just gave you and visiting the links above. Happy evolving!
