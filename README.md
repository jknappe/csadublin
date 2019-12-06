# Dublin CSA website

This is the website of the Dublin CSA, a community supported agricultrure groupe based in Dublin, Ireland.

## Website Template

This website is hosten on GitHub and written in Jekyll. We use the [Feeling Responsive](http://phlow.github.io/feeling-responsive/) template. The template has been adjusted to suit our needs and some features of the original template have been removed for improved editability, while some new features have benn added.

## How to...

### ... edit the navigation panel?

To customize the navigation panel, open `_data/navigation.yml`. You can add menu items with the following code for a directly clickable item:

```
- title: "Title"	# text that will appears in the navigation panel
  url: "/url"		# relative link address
  side: left		# alignment of menu item (left, right)
```

or similarly ig you want to create a menu item with dropdown options:

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
