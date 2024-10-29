# Researcher

### [Demo Page](http://gsmark36.github.io)

This is a jekyll theme template based personal website template based on **Researcher** and **Cactus**. You can find them on GitHub. 

- [Researcher](https://github.com/bk2dcradle/researcher)  
- [Cactus](https://github.com/chrismwilliams/astro-theme-cactus)  

### Directory

```
.
├── _includes       # Components loaded in layout templates
├── _layouts        # Layout templates
├── _posts          # Blog post articles
├── _sass           # SASS files
├── assets          # Media assets
├── css             # CSS files
├── _config.yml       # Jekyll configuration file (Important!)
├── 404.md            # 404 page
├── blog.md           # Blog page
├── contact.md        # Contact details
└── index.md          # Homepage/index
```

### Custom design

- Add or remove `.md` files as you need. Added page `example.md` will be accessible via link `{{ site.url }}{{ site.baseurl }}/example`.
- Use `permalink` to overwrite page address.
- Edit `title` variable in `_config.yml` to change **top heading**.
- Edit `nav` variable in `_config.yml` for the content of navigation bar.

```
nav:
 - name: "Home"
   link: "/"
 - name: "Blog"
   link: "/blog"
 - name: "Contact"
   link: "/contact"
```

- Add or change global variables in `_sass/vars.scss`. This file includes basic colors for the template.
- Create image tags with class `profile-picture` in markdown files to add profile pictures. 
- Edit the footer content by changing `footer_text` variable in `_config.yml`.
