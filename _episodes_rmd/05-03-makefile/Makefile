all: article.docx article.html

article.docx: article.Rmd
	Rscript -e 'rmarkdown::render("article.Rmd", "word_document")'

article.html: article.Rmd
	Rscript -e 'rmarkdown::render("article.Rmd", "html_document")'
