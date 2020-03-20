# INBIA
## INBIA: a boosting methodology for proteomic network inference

The analysis of tissue-specific protein interaction networks and their functional enrichment in pathological and normal tissues provides insights on the etiology of diseases. The Pan-cancer proteomic project, in The Cancer Genome Atlas, collects protein expressions in human cancers and it is a reference resource for the functional study of cancers. However, established protocols to infer interaction networks from protein expressions are still missing.

We have developed a methodology called Inference Network Based on iRefIndex Analysis (INBIA) to accurately correlate proteomic inferred relations to protein-protein interaction (PPI) networks. INBIA makes use of 14 network inference methods on protein expressions related to 16 cancer types. It uses as reference model the iRefIndex human PPI network. Predictions are validated through non-interacting and tissue specific PPI networks resources. The first, Negatome, takes into account likely non-interacting proteins by combining both structure properties and literature mining. The latter, TissueNet and GIANT, report experimentally verified PPIs in more than 50 human tissues. The reliability of the proposed methodology is assessed by comparing INBIA with PERA, a tool which infers protein interaction networks from Pathway Commons, by both functional and topological analysis.

Results show that INBIA is a valuable approach to predict proteomic interactions in pathological conditions starting from the current knowledge of human protein interactions.

<hr />
## License
*INBIA* is distributed under the MIT license. This means that it is free for both academic and commercial use. Note however that some third party components in *INBIA* require that you reference certain works in scientific publications.
You are free to link or use *INBIA* inside source code of your own program. If do so, please reference (cite) *INBIA* and this website. We appreciate bug fixes and would be happy to collaborate for improvements. 
[License](https://raw.githubusercontent.com/InfOmics/INBIA/master/LICENSE)

<hr />

## Citation
If you have used the package INBIA in your project, please cite the following paper:

     Sardina, D. S., Micale, G., Ferro, A., Pulvirenti, A., & Giugno, R. 
     INBIA: a boosting methodology for proteomic network inference. 
     BMC bioinformatics, 19(7), 188. (2018).
     
<hr />
