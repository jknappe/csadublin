# Dublin CSA website

This is the website of the Dublin CSA, a community supported agricultrure groupe based in Dublin, Ireland.

## Website Template

This website is hosten on GitHub and written in Jekyll. We use the [Feeling Responsive](http://phlow.github.io/feeling-responsive/) template. The template has been adjusted to suit our needs and some features of the original template have been removed for improved editability, while some new features have benn added.

## How to...

### ...edit the navigation menu?

To customize the navigation menu, open `_data/navigation.yml`. You can add menu items with the following code for a directly clickable item:

```
- title: "Title"	# text that will appears in the navigation menu
  url: "/url"		# relative link address
  side: left		# alignment of menu item (left, right)
```

or similarly if you want to create a menu item with dropdown options:

```
- title: "About Us"
  url: "/about/"
  side: left
  dropdown:
  - title: "What is Dublin CSA?"
    url: "/about/dublin-csa/"
  - title: "How it works"
    url: "/about/how-it-works/"
```

### ...add a new static page?



### ...add a new blog post?

YAML header arguments:

- `layout:`
- `title:`
- `subheadline:`
- `author:`
- `teaser:`
- `categories:`
- `tags:`
- `sidebar:` *true*, *false* ... enables/diables a sidebar on the left
- `show_meta:` *true*, *false* ... enables/diables display of meta data at the end of the post (e.g. author, category, tags)
- `image:` has three sub-arguments
  - `header:` 
  - `thumb:` link to thumbnail image used on archive pages; 150 x 150 px
  - `homepage:` link to image feature on the index page; 970 px wide

### ...customize the sidebar?

To customize the sidebar, open `_includes/sidebar.html`.

```
- title: "Title"	# text that will appears in the navigation menu
  url: "/url"		# relative link address
  side: left		# alignment of menu item (left, right)
```






