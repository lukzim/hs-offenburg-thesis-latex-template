import os
env = Environment(ENV=os.environ)
pdfOutput = env.PDF(target='thesis.pdf',source='thesis.tex')
Depends(pdfOutput,Split('thesis.tex bibliography.bib'))
