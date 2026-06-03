# DLBCL_Proteogenotypes

This respository contains code from the analysis presented in the paper: 

## Pathogenesis of Diffuse Large B-cell Lymphoma Proteogenotypes

*Julius C. Enssle<sup>1,2,3,4,33</sup>, Björn Häupl<sup>1,2,3,5,33</sup>, Arber Qoku<sup>2,5,6,33</sup>, Boya Wang<sup>4</sup>, George W. Wright<sup>7</sup>, Sharon Barrans<sup>8</sup>, Yulai Zhou<sup>9</sup>, Matthew A. Care<sup>10</sup>, Cathy Burton<sup>8</sup>, Caitlin Gribbin<sup>11</sup>, Stephan Eckert<sup>10,11</sup>, Jennifer Ziello<sup>12</sup>, Jason Weirather<sup>13</sup>, Yibo Dai<sup>14</sup>, Atish Kizhakeyil<sup>15</sup>, Xubin Li <sup>15</sup>, James D. Phelan<sup>4</sup>, Smriti Kanangat<sup>4,16</sup>, Stephan Eckert<sup>17,18</sup>, Sebastian Scheich<sup>1,2,3,19</sup>, Sebastian Wolf<sup>1,2,3,19</sup>,  Da Wei Huang<sup>4</sup>, Josefine Jakob<sup>1,3</sup>, Sebastian P. Perner<sup>1,2,5</sup>, Andrea Di Fonzo<sup>1,2,32</sup>, Martine Pape<sup>1,2</sup>, Marion Bodach<sup>1,2,5</sup>, Dominique Jahn<sup>1,2,5</sup>, Uwe Plessmann<sup>2,20</sup>, Annette M. Staiger<sup>21,22</sup>, German Ott<sup>21</sup>, Philipp Berning<sup>23</sup>, Georg Lenz<sup>23</sup>, Daniel J. Hodson<sup>24</sup>, Bernhard Kuster<sup>14,17</sup>, Roland Schmitz<sup>25</sup>, Henning Urlaub<sup>20,26</sup>, Ari M. Melnick<sup>27,28</sup> Reuben Tooze<sup>8,29</sup>, Coraline Mlynarczyk<sup>9</sup>, Giorgio Inghirami<sup>30</sup>, Florian Buettner<sup>2,3,5,6,31,34</sup>, Louis M. Staudt<sup>4,34</sup>, Thomas Oellerich<sup>1,2,3,5,19,34,35</sup>*

Affiliations:\
<sub>1  Department of Medicine, Hematology and Oncology, University Hospital, Goethe University Frankfurt, Frankfurt am Main, Germany \
2  German Cancer Consortium (DKTK), Partner Site Frankfurt/Mainz, a Partnership Between DKFZ and UCT Frankfurt-Marburg, Germany,
Frankfurt am Main, Germany \
3  Frankfurt Cancer Institute (FCI), Frankfurt am Main, Germany\
4  Lymphoid Malignancies Branch, National Cancer Institute, National Institutes of Health, Bethesda, MD, USA\
5  German Cancer Research Center (DKFZ), Heidelberg, Germany\
6  Goethe University Frankfurt, Department of Computer Science and Mathematics, Institute for Informatics, Frankfurt am Main, Germany\
7  Biometric Research Program, National Cancer Institute, National Institutes of Health, Bethesda, MD, USA\
8  Haematological Malignancy Diagnostic Service, St James’ University Hospital, Leeds, UK\
9  Center of Molecular and Cellular Oncology, Yale Cancer Center, and Departments of Internal Medicine (Medical Oncology and Hematology)
and Pathology, Yale School of Medicine, New Haven, CT, USA\
10  Section of Experimental Haematology, University of Leeds, Leeds, UK\
11  Division of Hematology and Medical Oncology, Weill Cornell Medicine, New York, NY, USA\
12  Cell Signaling Technology, Inc., Danvers, MA, USA\
13  Elucidate Biotechnologies, Boston, MA, USA\
14  Department of Genomic Medicine, University of Texas MD Anderson Cancer Center, Houston TX 77546, USA\
15	Department of Lymphoma & Myeloma, University of Texas MD Anderson Cancer Center, Houston TX 77546, USA\
16	Department of Hematology and Medical Oncology, Emory University, Atlanta, GA, USA\
17	Chair of Proteomics and Bioanalytics, School of Life Sciences, Technical University of Munich, Freising, Germany\
18	German Cancer Consortium (DKTK), Partner Site Munich, a Partnership Between DKFZ and TU Munich, Germany\
19	University Cancer Center (UCT), Frankfurt Am Main, Germany\
20	Bioanalytical Mass Spectrometry, Max Planck Institute for Multidisciplinary Sciences, Goettingen, Germany\
21	Department of Clinical Pathology, Robert-Bosch-Krankenhaus, Stuttgart, Germany\
22	Dr. Margarete Fischer-Bosch Institute for Clinical Pharmacology, Stuttgart and University of Tuebingen, Tuebingen, Germany\
23  Department of Medicine A - Hematology, Oncology and Pneumology, University Hospital Muenster, Muenster, Germany\
24  Department of Haematology, Cambridge Stem Cell Institute, University of Cambridge, Jeffrey Cheah Biomedical Centre, Cambridge, UK\
25  Institute of Pathology, Justus Liebig University Giessen, Giessen, Germany\
26  Bioanalytics, Institute of Clinical Chemistry, University Medical Center Goettingen, Goettingen, Germany\
27  Josep Carreras Leukemia Research Institute, Barcelona, Spain\
28  Division of Hematology and Medical Oncology, Department of Medicine, Weill Cornell Medicine/NewYork-Presbyterian Hospital, New York,
NY, USA\
29  Division of Haematology and Immunology, Leeds Institute of Medical Research, University of Leeds, Leeds, UK\
30  Department of Pathology and Laboratory Medicine, Weill Cornell Medicine, New York, NY, USA\
31  Goethe University Frankfurt, Department of Medicine, Frankfurt Am Main, Germany\
32  Present address: Analytical Chemistry Lab, Istituto Italiano di Tecnologia, Genoa, Italy\
33,34 These authors contributed equally\
35	Lead contact

Corresponding author (#) email: oellerich@em.uni-frankfurt.de, buettner@med.uni-frankfurt.de 

### Following analysis code is included:
- Integration of RNA and Protein expression data using MuVI, see also: https://github.com/MLO-lab/MuVI
- Inference of DLBCL proteogenotypes
- scRNA and scATAC sequencing data processing and integration, DA testing by miloR

### Data availablity:
- RNA expression data: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE181063
- Protein expression data: https://massive.ucsd.edu/ProteoSAFe/static/massive.jsp
- scRNA and scATAC sequencing data: EGA: [EGAS50000001227](https://www.ega-archive.org/studies/EGAS50000001227), https://www.cell.com/cancer-cell/fulltext/S1535-6108(25)00549-5

### DLBCL proteogenotype classifier:
https://dlbcl-pg-classifier.uni-frankfurt.de/

For further questions, please reach out the the corresponding author.
