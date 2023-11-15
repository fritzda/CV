[![](./img/cvPreview.png)](https://github.com/douglasfritz/CV/blob/master/GoogleSheetsCV.pdf)

# My Data Driven CV
### Credit to [`brian jenks`](https://github.com/tallguyjenks/CV) and [`anthony schmidt`](https://www.anthonyschmidt.co/post/2022-04-21-make-an-easy-to-maintain-cv-or-resume-using-r/) for the inspo

## What

This CV is created primarily using the **`R`** Package [`vitae`](https://github.com/mitchelloharawild/vitae) and Google sheets

## Why

Automation is fun to learn, just in case it comes in handy!

I needed a CV that I can easily update without worrying about formatting.

## How

This document utilizes **RMarkdown** and is compiled through pandoc/LaTex.

With RStudio, I read in my google sheet data, then using the `vitae` functions and other table functions, I build the CV.

The header portion of the document is comprised in the `YAML` portion of the `RMarkdown` document.

I can use the google sheet as the master database and update the document as I see fit. Keeps things easily customizable with minimal effort
