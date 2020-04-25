book: pdf_book epub_book gitbook
pdf_book:
	Rscript -e "bookdown::render_book('index.Rmd', 'bookdown::pdf_book')"
epub_book:
	Rscript -e "bookdown::render_book('index.Rmd', 'bookdown::epub_book')"
gitbook:
	Rscript -e "bookdown::render_book('index.Rmd', 'bookdown::gitbook')"
s3publish: gitbook
	# This S3 bucket is hosted at http://fsds.alpha-epsilon.de
	# Access the web version of the book there.
	aws s3 cp _book/ s3://fullstackdatascience --recursive --acl public-read
