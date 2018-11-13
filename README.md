# Jekyll-Breadcrumb-Microdata

A [BreadcrumbList](https://schema.org/BreadcrumbList) is an ItemList consisting of a chain of linked Web pages, typically described using at least their URL and their name, and typically ending with the current page.

## Usage

1. Add `breadcrumbs.html` to your site's `_includes` folder
2. Place the following into your **_layouts** files or into your pages where you want your **breadcrumbs** appear:

  ```liquid
  {% include breadcrumbs.html path=page.path title=page.title %}
  ```

3. Style it with your own CSS or use my style, see: `<!-- comments -->

*If you don't know how **includes** work, go to [Jekyll includes](https://jekyllrb.com/docs/includes/) on Jekyll official website.*

## What it does

Jekyll-Breadcrumb-Microdata **automatically** and **dynamically** generates breadcrumbs for your website. 
Together with breadcrumbs, **structured data** in **Microdata** format are also generated.

## A breadcrumb trail with structured data for Jekyll websites

Tested with [Google Structured data](https://search.google.com/structured-data/testing-tool?hl=it)

Good for GitHub Pages

### [Gist](https://gist.github.com/enricocaputo/2509e00403aa4218df28a730ce1aa57a) 

