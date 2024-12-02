# DLBCL_Proteogenotypes

This respository contains code from the analysis presented in the paper: 

## Pathogenesis of Diffuse Large B-cell Lymphoma Proteogenotypes

*Julius C. Enssle<sup>1,2,3,4,23</sup>, Björn Häupl<sup>1,2,3,5,23</sup>, Arber Qoku<sup>2,5,6,23</sup>, Boya Wang<sup>4</sup>, George W. Wright<sup>4</sup>, Sharon Barrans<sup>7</sup>, Matthew A. Care<sup>8</sup>, Cathy Burton<sup>7</sup>, Caitlin Gribbin<sup>9</sup>, Stephan Eckert<sup>10,11</sup>, Sebastian Scheich<sup>1,2,3,12</sup>, Sebastian Wolf<sup>1,2,3</sup>, James D. Phelan<sup>4</sup>, Da Wei Huang<sup>4</sup>, Andrea Di <sup>Fonzo1,3,Δ</sup>, Martine Pape<sup>1,2</sup>, Marion Bodach<sup>1,2,5</sup>, Dominique Jahn<sup>1,2,5</sup>, Uwe Plessmann<sup>2,13</sup>, Annette M. Staiger<sup>14,15</sup>, German Ott<sup>14</sup>, Philipp Berning<sup>16</sup>, Georg Lenz<sup>16</sup>, Daniel J. Hodson<sup>17</sup>, Bernhard Kuster<sup>10,11</sup>, Roland Schmitz<sup>18</sup>, Henning Urlaub<sup>13,19</sup>, Reuben Tooze<sup>7,20</sup>, Giorgio Inghirami<sup>21</sup>, Florian Buettner<sup>2,3,5,6,22,24,#</sup>, Louis M. Staudt<sup>4,24</sup>, Thomas Oellerich<sup>1,2,3,5,12,24,25,#</sup>*

Affiliations:	
1	Department of Medicine, Hematology and Oncology, University Hospital, Goethe University Frankfurt, Frankfurt am Main, Germany
2	German Cancer Consortium (DKTK), partner site Frankfurt/Mainz, a partnership between DKFZ and UCT Frankfurt-Marburg, Germany, Frankfurt am Main, Germany
3	Frankfurt Cancer Institute (FCI), Frankfurt am Main, Germany
4	Lymphoid Malignancies Branch, National Cancer Institute, National Institutes of Health, Bethesda, MD, USA
5	German Cancer Research Center (DKFZ), Heidelberg, Germany
6	Goethe University Frankfurt, Department of Computer Science and Mathematics, Institute for Informatics, Frankfurt am Main, Germany
7	Haematological Malignancy Diagnostic Service, St James' University Hospital, Leeds, UK
8	Section of Experimental Haematology, University of Leeds, Leeds, UK
9	Division of Hematology and Medical Oncology, Weill Cornell Medicine, New York, NY, USA
10	Chair of Proteomics and Bioanalytics, School of Life Sciences, Technical University of Munich, Freising, Germany
11	German Cancer Consortium (DKTK) and German Cancer Research Center (DKFZ), Heidelberg, Germany
12	University Cancer Center (UCT), Frankfurt am Main, Germany
13	Bioanalytical Mass Spectrometry, Max Planck Institute for Multidisciplinary Sciences, Göttingen, Germany
14	Department of Clinical Pathology, Robert-Bosch-Krankenhaus, Stuttgart, Germany
15	Dr. Margarete Fischer-Bosch Institute for Clinical Pharmacology, Stuttgart and University of Tuebingen, Tuebingen, Germany
16	Department of Medicine A - Hematology, Oncology and Pneumology, University Hospital Münster, Münster, Germany
17	Department of Haematology, Cambridge Stem Cell Institute, University of Cambridge, Jeffrey Cheah Biomedical Centre, Cambridge, UK
18	Institute of Pathology, Justus Liebig University Giessen, Giessen, Germany
19	Bioanalytics, Institute of Clinical Chemistry, University Medical Center Göttingen, Göttingen, Germany
20	Division of Haematology and Immunology, Leeds Institute of Medical Research, University of Leeds, Leeds, UK
21	Department of Pathology and Laboratory Medicine, Weill Cornell Medicine, New York, NY, USA
22	Goethe University Frankfurt, Department of Medicine, Frankfurt am Main, Germany
23,24	These authors contributed equally
25	Lead contact
Δ Present affiliation: 	Analytical Chemistry Lab, Istituto Italiano di Tecnologia, Genoa, Italy

Corresponding author (#) email: oellerich@em.uni-frankfurt.de, buettner@med.uni-frankfurt.de 

### Following analysis code is included:
- Integration of RNA and Protein expression data using MuVI, see also: https://github.com/MLO-lab/MuVI
- Inference of DLBCL proteogenotypes
- scRNA and scATAC sequencing data processing and integration, DA testing by miloR

### Data availablity:
- RNA expression data: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE181063
- Protein expression data: https://massive.ucsd.edu/ProteoSAFe/static/massive.jsp
- scRNA and scATAC sequencing data: Wang B et al. (PMID to be included)

For further questions, please reach out the the corresponding author.
