input=article.Rmd

all: article.docx article.html

article.docx: $(input)
	Rscript -e 'rmarkdown::render("$(input)", "word_document")'

article.html: $(input)
	Rscript -e 'rmarkdown::render("$(input)", "html_document")'
