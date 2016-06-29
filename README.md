# OrganizationRelationRecognition

Ontologies/HolderNear.txt and SubsidiaryNear.txt contains words that may be found near relation example often. 

Ontologies/CompanySyn.txt contains synonims of the word "organization".

organizatoinsUnique.txt contains all organization names extracted from Wikipedia.

folder manualAnnotation contains folders with annotations in BRAT format http://brat.nlplab.org/standoff.html

rel-owningCompany-ru.csv, rel-parentCompany-ru.csv, rel-parentOrganisation-ru.csv --- are extracted relations from DBpedia.
FINAL_RES_DAUTHER_COMP.ods, FINAL_RES_MOTHER_COMP.ods --- are extracted relations from infoboxes. Text from infobox about mother/daughter companies is in first column, second --- is the source article. Relations can be easily extracted with help of Wikipedias "[[]]" link structure.
sum_parent_redirects.csv unites all this files under as Holder relation examples.

contextesAuto.csv contains extracted contexts before filtering. 
Structure is as follows: "name of found company", "amount of symbols offcet is source organization", "length", "source organization", "context text"
