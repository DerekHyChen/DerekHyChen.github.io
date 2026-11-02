# derekhychen.github.io

Personal academic website for Derek Chen.

Template adapted from [Andy Zeng's website](https://github.com/andyzeng/andyzeng.github.io).

## Editing

- `index.html` holds all content. Each tab (Highlights, Publications, Projects, Experience, Service) is a set of `list-item` blocks with a matching class.
- `images/` holds the profile photo and thumbnails. Replace the placeholder images, keeping the same file names, or change the `src` paths.
- `cv.pdf` is linked from the header. Add your CV PDF at that path.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
