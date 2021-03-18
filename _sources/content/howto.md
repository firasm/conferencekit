# How to use this website

## Video Tutorials

```{dropdown} Step 1. Create a GitHub Account
    :container: + shadow
    :title: bg-success text-white font-weight-bold
    :open:

<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube-nocookie.com/embed/pLe4DoB_ghA" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Step 2. Tutorial on Editing the Website
    :container: + shadow
    :title: bg-primary text-white font-weight-bold
    :open:

<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube-nocookie.com/embed/IogWc98v8OU" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```
## Useful Components

Below are some more useful components that can be used to style the pages.

### Dropdown with text

```{dropdown} Here's my dropdown
Donec facilisis porta nulla, eu mollis lectus pellentesque et. Vivamus blandit dui euismod, tincidunt purus ac, dignissim risus. Aenean pharetra pellentesque metus, a rutrum risus. Nulla leo sapien, molestie nec ex eget, euismod suscipit arcu. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nam lobortis dapibus nulla gravida lacinia. Cras metus ligula, rhoncus quis ligula cursus, sagittis varius ligula. Nunc sed viverra augue, ut pellentesque risus. Aliquam tempor ultrices ornare. Suspendisse potenti. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam gravida accumsan lacus nec accumsan. Nunc vel tortor massa. Aliquam tristique velit turpis, non auctor magna facilisis in. Phasellus ac condimentum ligula, ac cursus lorem.
```

### Dropdown with Video (initially closed, default)

```{dropdown} Testimonial from conference
    :container: + shadow
    :title: bg-primary text-white font-weight-bold

<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/3gIXlLax0bk" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

### Dropdown with Video (initially open)

```{dropdown} Testimonial from conference
    :container: + shadow
    :title: bg-primary text-white font-weight-bold
    :open:

<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/3gIXlLax0bk" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

### Tabbed 
```{tabbed} Tab 1 title
My first tab
```

```{tabbed} Tab 2 title
My second tab with `some code`!
```

### Tables

Here is how to create a table in Markdown:

| Training | Validation |
|:---------|-----------:|
| 0        |          6 |
| 1        |          5 |
| 2        |          3 |
| 3        |          4 |
| 4        |          2 |
| 5        |          1 |

### Admonitions

```{admonition} This is a title
An example of an admonition with a title.
```

```{note} Notes require **no** arguments,
so content can start here.
```

```{warning} This is an example
of a warning directive.
```

```{tip} This is an example
of a tip directive.
```

```{caution} This is an example
of a caution directive.
```

```{attention} This is an example
of an attention directive.
```

```{danger} This is an example
of a danger directive.
```

```{error} This is an example
of an error directive.
```

```{hint} This is an example
of a hint directive.
```

```{important} This is an example
of an important directive.
```

### Adding images

1. Upload the image to the GitHub repository. You can do this by dragging and dropping the image to the [content/images]() folder on GitHub.

2. Note the filename of the image, mine is called "demoImage.jpg".

3. Add the image to the Website like this:

```
![](images/demoImage.jpg)
```

![](images/demoImage.jpg)

4. (Optional) By default, the image will be the same size you upload it. To change the width or the height, instead of using `![](content/images/demoImage.jpg)` you will need to use this syntax:

```
<img src="images/demoImage.jpg" width=50>
```
<img src="images/demoImage.jpg" width=50>

```{warning}
When adding images to .md files **inside** content, your path (i.e. `images/demoImage.jpg`) will need to have an additional `../` so the full code would look like `![](../content/images/demoImage.jpg)`).
```