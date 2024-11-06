
### Hugo


To refresh the knowledge of Hugo [Fireship](https://www.youtube.com/watch?v=0RKpf3rK57I)

Add new page:

```
    export PATH=$PATH:/home/lukasz/go/bin
    hugo new posts/my-first-post.md
```

### Congo theme

Update:

```
    git submodule add -b stable https://github.com/jpanther/congo.git themes/congo
    git submodule update --remote --merge
```


### Features

#### Automatic image resizing

<!-- Markdown: ![My image](image.jpg) -->
<img
  srcset="
    /image_320x0_resize_q75_box.jpg 320w,
    /image_635x0_resize_q75_box.jpg 635w,
    /image_1024x0_resize_q75_box.jpg 1024w,
    /image_1270x0_resize_q75_box.jpg 2x"
  src="/image_635x0_resize_q75_box.jpg"
  alt="My image"
/>

#### Fuze.js Site Search
All searches are performed client-side meaning there’s nothing to configure on the server and queries are performed super fast. Simply enable the feature in your site configuration and you’re all set.

#### Tables of contents 
On article pages

### Folder strucutre

- Layouts - for theme layouts override
- Static - for static files, it is the folder that is copied to public during build time
- Assets - default location for images, css, js
- Archetypes - how new content is created with `hugo new`

### Vocabulary

Front Matter - the top section of the markdown file that contains metadata about the post


### Features

#### Automatic image resizing

<!-- Markdown: ![My image](image.jpg) -->
<img
  srcset="
    /image_320x0_resize_q75_box.jpg 320w,
    /image_635x0_resize_q75_box.jpg 635w,
    /image_1024x0_resize_q75_box.jpg 1024w,
    /image_1270x0_resize_q75_box.jpg 2x"
  src="/image_635x0_resize_q75_box.jpg"
  alt="My image"
/>

#### Fuze.js Site Search
All searches are performed client-side meaning there’s nothing to configure on the server and queries are performed super fast. Simply enable the feature in your site configuration and you’re all set.

#### Tables of contents 
On article pages

#### Embed PDF
https://github.com/anvithks/hugo-embed-pdf-shortcode

```
{{< embed-pdf url="./poster-mlinpl-2023.pdf" hideLoader="true" hidePaginator="true">}}
```
