# Notebooks Now! Submission Template

This submission template is for a markdown-based publication with additional supporting notebook and markdown files, as well as supporting data, bibliography, and Quarto build configuration. It is based upon a new type of project in Quarto, Manuscripts. 

Get started with Quarto and Manuscript projects here: <https://quarto.org/docs/manuscripts/>.

## Source file

The source file for this template is a Jupyter notebook. There is not necessarily anything special about this notebook. It may contain markdown cells, code cells, and outputs from common Python packages, including pandas, matplotlib, plotly, seaborn, and altair. 

The notebook has an additional markdown cell at the top of the document which configures Quarto to render the notebook.

## Supporting material

### Supplementary data

By convention, all data should be saved in `data/` directory. There is nothing magic about this directory; references to your data from your notebook must still specify the correct relative path.

### Supplementary images

Similar to the `data/` directory, images for figures should be specified in `images/` directory.

### Bibliography

Bibliography entries may be specific in the document as described in the [Quarto documentation](https://quarto.org/docs/authoring/footnotes-and-citations.html#bibliography-files). 

## Quarto configuration

Configuration for the example is provided by the Quarto project file, `_quarto.yml`, and the YAML block (front matter) that appears with the article markdown document.

## Building output artfiacts

To build PDF/JATS output from your source data, you must have the Quarto CLI installed - you can download or learn about installation at <https://quarto.org/docs/download/>

Then render the article using

```
quarto render article.ipynb
```
