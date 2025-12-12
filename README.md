# mid-infrared imaging and machine learning approaches for non-destructive and efficient material detection of textile fabrics

major project part 1 (TXD 401) submitted to the Department of Textile and Fibre Engineering at the Indian Institute of Technology Delhi.

## project investigators

lakshya kumar (2022TT12183)
keshav chachan (2022TT12148)

## project abstract

this project addresses the critical environmental challenge of textile waste management in india by proposing an automated, non-destructive framework for material identification. manual sorting currently constitutes a major bottleneck due to inefficiency and human error. this research investigates spectroscopic techniques combined with machine learning to distinguish between cotton, polyester, and nylon fibers.

the study initially focused on passive mid-infrared (mir) imaging utilizing a yolo11x-cls architecture. while the model demonstrated high accuracy on controlled validation sets, it exhibited limitations in robustness regarding environmental thermal noise and dye variations. consequently, the research methodology was reoriented towards terahertz (thz) time-domain spectroscopy. experimental results indicate that the thz regime (0.1-10 thz) offers enhanced resilience to dye interference and distinct spectral absorption peaks, proving to be a more viable candidate for robust textile sorting.

## methodology

the research was conducted in two distinct phases:

### phase i: mir based classification
* [cite_start]**dataset creation**: acquisition of 120 mir images (40 per class) under controlled conditions.
* [cite_start]**ground truth verification**: validation of samples via standard burn tests and chemical solubility tests.
* [cite_start]**modeling**: implementation of yolo11x-cls for fabric classification using transfer learning.
* [cite_start]**analysis**: identification of limitations regarding passive mir imaging in uncontrolled environments due to thermal noise and surface texture.

### phase ii: terahertz spectroscopy characterization
* **sample preparation**: analysis of laboratory-dyed, commercial, and blended cotton samples to test dye independence.
* **spectral analysis**: comparative analysis of absorbance spectra for cotton, nylon, and polyester.
* **key findings**: identification of unique absorption peaks and confirmation that thz spectroscopy effectively characterizes fiber density and structure with diminished interference from dyes.

## latex report template

the latex source files used to generate the project report are included in this repository. this template is compliant with the formatting standards of the department of textile and fibre engineering, iit delhi. it may be utilized by other students for b.tech projects, m.tech projects, or academic reports.

## acknowledgment

we express our gratitude to our supervisors, Prof. Apurba Das and Prof. Bipin Kumar, for their guidance. we also thank Mr. Sagar for his mentorship and Prof. Amartya Sen Gupta (department of physics) for his technical insights regarding spectroscopic techniques.
