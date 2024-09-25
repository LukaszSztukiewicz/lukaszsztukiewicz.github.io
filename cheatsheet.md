
### Hugo

Add new page:

```
    hugo new posts/my-first-post.md
```

### Congo theme

Update:

```
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
