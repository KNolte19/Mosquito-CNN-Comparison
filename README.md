# MosquitoCNNComparison
Repository of the manuscript under review: "Robust mosquito species identification from diverse body and wing images using deep learning".

# Authors
Kristopher Nolte1*, Felix Gregor Sauer1, Jan Baumbach2, Philip Kollmannsberger3, Christian Lins4, Renke Lühken1

Affiliations
1Bernhard Nocht Institute for Tropical Medicine, Hamburg, Germany
2University of Hamburg – Institute for Computational Biology, Hamburg Germany
3Heinrich Heine University Düsseldorf – Biomedical Physics, Düsseldorf, Germany
4Hamburg University of Applied Sciences - Faculty of Engineering and Computer Science, Hamburg, Germany 


# Abstract
Mosquito-borne diseases are a major global health threat. Traditional morphological or molecular methods for identifying mosquito species often require specialized expertise or expensive laboratory equipment. The use of Convolutional Neural Networks (CNNs) to identify mosquito species based on images may offer a promising alternative, but their practical implementation often remains limited. This study explores the applicability of CNNs in classifying mosquito species. It compares the efficacy of body and wing depictions across three image collection methods: a smartphone, macro-lens attached to a smartphone and a professional stereomicroscope. The study included 796 specimens of four morphologically similar Aedes species, Aedes aegypti, Ae. albopictus, Ae. koreicus, and Ae. japonicus japonicus. The findings of this study indicate that CNN models demonstrate superior performance in wing-based classification 87.6% (CI95%: 84.2 - 91.0) compared to body-based classification 78.9% (CI95%: 77.7 - 80.0). Nevertheless, there are notable limitations of CNNs as they perform reliably across multiple devices only when trained specifically on those devices, resulting in an average decline of mean accuracy by 14%, even with extensive image augmentation. Additionally, we also estimate the required training data volume for effective classification, noting a reduced requirement for wing-based classification in comparison to body-based methods. Our study underscores the viability of both body and wing classification methods for mosquito species identification while emphasizing the need to address practical constraints in developing accessible classification systems. 
