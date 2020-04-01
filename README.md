# Structural-analogy from a Single Image Pair

![teaser](https://github.com/sagiebenaim/structural-analogy/blob/master/images/teaser.png)

Sagie Benaim, Ron Mokady, Amit Bermano, Daniel Cohen-or, Lior Wolf

### Abstract

The task of unsupervised image-to-image translation has
seen substantial advancements in recent years through the use of deep
neural networks. Typically, the proposed solutions learn the characterizing
distribution of two large, unpaired collections of images, and are able
to alter the appearance of a given image, while keeping its geometry
intact. In this paper, we explore the capabilities of neural networks to
understand image structure given only a single pair of images, A and
B. We seek to generate images that are structurally aligned : that is,
to generate an image that keeps the appearance and style of B, but
has a structural arrangement that corresponds to A. The key idea is to
map between image patches at different scales. This enables controlling
the granularity at which analogies are produced, which determines the
conceptual distinction between style and content. In addition to structural
alignment, our method can be used to generate high quality imagery in
other conditional generation tasks utilizing images A and B only: guided
image synthesis, style and texture transfer, as well as text translation.
Our code will be made publicly available.

You can use the [editor on GitHub](https://github.com/sagiebenaim/structural-analogy/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Abstract

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sagiebenaim/structural-analogy/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
