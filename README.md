<h1>Handwritten Answer Script Evaluator</h1>
<h3>Objective</h3>
The objective of this project is to develop a system for
evaluating answer scripts that enables teachers to upload
students’ answer script images.
<ul>
<li>To produce a text file containing the student’s response,
the uploaded answer script must be fed as an input to
the tesseract OCR.</li>
<li>The sentence transformer, which generates similarity
using the cosine function, must receive the OCR output
as an input.</li>
<li>The final section, which is where the keyword matching
occurs and the final score or mark is produced.</li>
<li>Write down the results</li>
</ul>
<p>Language used : Python </p>
<p>Model used : STSB-MPNet-base-v2</p>
<h5>Packages Used</h5>
<ul>
<li>tesseract-ocr</li>
<li>pytesseract</li>
<li>xlwt</li>
<li>PIL</li>
<li>sentence-transformer</li>
<li>transformers</li>
<li>shutil</li>
</ul>

