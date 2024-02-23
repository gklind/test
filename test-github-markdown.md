---
title: 'test-github-markdown'
output: html_document
---

 knit: (function(input_file, encoding) {
    out_dir <- 'docs';
    rmarkdown::render(input_file,
      encoding=encoding,
      output_file=file.path(dirname(input_file), out_dir, 'index.html'))})
  

  
