# NMFS Stock Assessment Cloud Pipeline

Presentation for an ideal semi-automated cloud stock assessment pipeline 
for NOAA Fisheries.

## How presentation was made

I used a Quarto extention called [closeread](https://github.com/qmd-lab/closeread#readme).

Run the following line in the project to make the extension available:
```
quarto add qmd-lab/closeread
```

This format can be accessed in the format section in a Quarto yaml as such:

```
---
title: My First Closeread
format: closeread-html
---
```

## Project notes

- Enclosing all content inside `{.cr-section}` indicates a 100% CloseRead document
- 

Options for layout of content:

- sidebar-left (default)
- sidebar-right
- overlay-left
- overlay-center
- overlay-right

*All layouts will automatically revert to overlay-center when viewed on a mobile device

- `remove-header-space: true` in the yaml under format removes the headerspace. *Only* use this when doing a 100% CloseRead document
- 


