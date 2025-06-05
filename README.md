# Definition

SEO is a practice that optimizes web pages so they become more visible and rank higher on search engines.

# HTML 

## The role of the meta tag and how it affects SEO 

One way to improve your site's SEO is to provide a short description for the web page using the **meta** element.  
```html
<meta name="description" content="Discover expert tips and techniques for gardening" />
```
By setting the `name` attribute to "description", we make sure that browsers, search engines, and other web tools correctly interpret this metadata.
The `content` attribute is where we place our description.  

It is recommended to keep our description concise because search engines will often truncate it based on the results page layout.  

Even though meta descriptions won't directly affect a site's ranking on a search engine, having a strong description could result in more traffic to your site.  

---

## The role of Open Graph Tags and how they affect SEO

The open graph protocol enables you to control how your website's content appears across various social media platforms.  

By setting the open graph properties, you can entice users to click and engage with your content.  
You can set these properties through a collection of **meta** elements inside your HTML **head** section.  

### property="og:title"

The first important OG property to include would be the **title**. For example:
```html
<meta content="freeCodeCamp.org" property="og:title" />
```
The **content** attribute is where we need to write the title we want to be displayed for social media sites.  

### property="og:type"

The next important OG property would be the **type**.  
```html
<meta property="og:type" content="website" />
```
The **type** property is used to represent the type of content being shared on social media.  
It can be articles, music, videos, or websites.  

### property="og:image"

Example:
```html
<meta
  property="og:image"
  content="https://path-to-image"
/>
```

Make sure the image quality is good.  
Most social media platforms will include criteria for image requirements to help you ensure that your content displays well on their site.  

### property="og:url"

Example: 
```html
<meta property="og:url" content="https://www.freecodecamp.org" />
```

There are many more OG properties that you can set: `og:video`, `og:audio`, `og:description`, `og:locale`, ...  
However, the 4 properties mentioned above are the most important ones to include.  

### How do these OG properties affect SEO?

