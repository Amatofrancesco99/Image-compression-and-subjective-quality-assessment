# Image-compression-and-subjective-quality-assessment
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
<br>
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://github.com/Amatofrancesco99/Image-compression-and-subjective-quality-assessment/blob/main/LICENSE)
<br>
<br>
The aim of this project is to apply a [two-level degradation algorithm](https://github.com/Amatofrancesco99/Image-compression-and-subjective-quality-assessment/tree/main/main.py) on [10 images](https://github.com/Amatofrancesco99/Image-compression-and-subjective-quality-assessment/tree/main/Original%20images) ([JPEG compression](https://www.ece.ucdavis.edu/cerl/reliablejpeg/compression/)).
<br>
After applying this algorithm, some users (24) were asked to give their personal opinion (opinion score, OS) on the quality of such damaged images ([module link](https://docs.google.com/forms/d/1sbGq9buDY81KzAQer61JFAOOB_Cx7w-6KJtURkBYlQM/edit?usp=sharing)).
<br>
Subsequently, some [statistics](https://docs.google.com/spreadsheets/d/1KzE92K5fdU3O7zQb6gbgB_71cHL2H_fhqHaPDHUbvUY/edit?usp=sharing) were automatically made on these obtained data.
<br>
Finally, the results are studied in depth, to better understand why some images have confused most users.
<br><br>
**Some statistic results**
<br>
This table shows for each image its *[MOS](https://www.twilio.com/docs/glossary/what-is-mean-opinion-score-mos)* (&mu;, [mean](https://en.wikipedia.org/wiki/Mean) opinion score) and *[variance](https://en.wikipedia.org/wiki/Variance)* (&#963;<sup>2</sup>).
<br>
Moreover, for each impairment group (original, imp1, imp2) is performed its overall MOS and variance.
<br>
<img src="https://github.com/Amatofrancesco99/Image-compression-and-subjective-quality-assessment/blob/main/statistical%20results%20images/mos-table.png" width="800" height="300">
<br>
This graph shows the same results discussed in the previous table, in a different way (through a multi-line graph).
<br>
<img src="https://github.com/Amatofrancesco99/Image-compression-and-subjective-quality-assessment/blob/main/statistical%20results%20images/mos-graph.png" width="600" height="350">
<br>
We can see that none of this images has a strange behaviour in its MOS
<br>
(it means MOS<sub>imp2</sub> < MOS<sub>imp1</sub> < MOS<sub>original</sub>).
<br><br><br>
**Presentation link**
<br>
[![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://docs.google.com/presentation/d/13nk13bs2LWd0VW3bJVGlTVi19dvzVleI0sHtMW1I2rw/edit?usp=sharing)
