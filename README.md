# UL-thesis-Template
Example of the Dissertation (Undergraduate/Master/PhD) Template for University of Limerick.


## Customization

- **Spacing**: Change `\DoubleSpacing` to `\OnehalfSpacing` in `thesis.sty` for 1.5 spacing.
- **Title Page Margin**: Adjust before `\maketitle`:
  ```latex
  \setlength{\titlepagemedskip}{0.15in}
  \setlength{\titlepagebigskip}{0.55in}
  ```
-  **Table of Contents Style**: Customize using the `tocloft` package. Refer to the style file [here](https://github.com/f-amerehi/UL-thesis-Template/blob/main/thesis.sty#L204-L247).

- **Section Numbering and TOC Depth**:
  ```latex
  \setcounter{secnumdepth}{2}
  \setcounter{tocdepth}{1}
  ```

## Acknowledgements

This template is adopted from [wisc-thesis-template](https://github.com/Lodour/wisc-thesis-template). MIT-licensed.

```
