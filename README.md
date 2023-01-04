# Add image captions

Add an image in this format:

```markdown
![[image.jpg|This is a caption]]
```

or this format:

```markdown
![This is a caption](image.jpg)
```

and it will add the caption underneath the image, like this:

![](example.png)

You can apply CSS styling by targeting the `.image-captions-figure` and `.image-captions-caption` classes.

## Limitations

This does not work for external images, for example:

```markdown
![This is an external image](https://obsidian.md/logo.png)
```

This is because Obsidian adds no identifying classes to these images, so I couldn't find a reliable way of targeting them.
Get in touch if you know a way to do this!
