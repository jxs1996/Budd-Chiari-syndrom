# Budd-Chiari-syndrom
<b>Background:</b> Budd-Chiari syndrome (BCS) is characterized by hepatic venous outflow obstruction and in severe cases, is even life-threatening. In the past few decades, the risk factors related to BCS, including inherited and acquired hypercoagulable states or other predisposing factors, have been reported. However, a large number of patients have no identifiable etiological factors. And, there are different causes for BCS in the West and East. In China, segmental or membranous inferior vena cava obstruction is the main manifestation of BCS. The prevalence of prothrombotic disorders seems to be relatively low. 


<b>Methods:</b> In this study, 500 BCS patients and 696 normal individuals were recruited for whole-exome sequencing. We carried out whole-exome sequencing and developed polygenic risk scoring (PRS) model based on the PLINK, LASSOSUM, BLUP, and BayesA method. We further performed the BCS risk prediction by intersecting the BCS PRS model with the venous thromboembolism and vascular malformations model. 


<b>Results:</b> BCS-related mutations, such as rs1042331, rs34370305, and rs73739662, were discovered by BCS genome-wide association studies. By comparing different polygenic risk scoring algorithms, the optimal model produced by the BayesA algorithm was determined. By testing additionally recruited experimental samples, it was found that area under the ROC curve>0.9.

<b>Conclusion:</b> Further interpretation of the model also provides new insights to explain the difference in genetic risk for BCS between China and the West. In addition, we also found that BCS, venous thromboembolism, and vascular malformations might share some common genetic risks, which might provide new insights into the pathogenesis of BCS.

### Figure
<b>Figure 1: PRS analysis process of Budd-Chiari syndrome.</b> 1196 samples (case=500, control=696) were used for model construction, of which 80% were used for training and 20% were used for testing. The PRS analysis process follows the published PRS guidelines. For the constructed model, 346 external independent samples (case=30, control=316) were used for evaluation. For model results, weight information will be extracted for downstream analysis such as model interpretation and GO, KEGG enrichment analysis.

<b>Figure 2: Genome-wide association analysis results of Budd-Chiari syndrome.</b> 8 SNPs (rs1042331, rs34370305, rs73739662, rs73739663, rs77350016, rs77981473, rs2308928, rs4247257) were significantly related to BCS and met the significance condition of the whole genome (p < 5e-8) . These sites are located in the 6p21-p32 zone. rs1042331 is located on the HLA-DPB1 gene. The other 7 SNPs are located within 20kb upstream of rs1042331 and are located on the HLA-DPA1 gene.

<b>Figure 3: PRS model evaluation analysis.</b> <b>a)</b> The evaluation results of each model under different algorithms and different p-value conditions, and each condition is repeated 10 times. <b>b)</b> The AUC result of the BayesA model in the internal test set. <b>c)</b> Distribution of sample scores of BayesA model in external test set. the white line is the optimal threshold in b. <b>d)</b> The confusion matrix result of the BayesA model in the external test set, the result is obtained under the optimal threshold in b. <b>e)</b> The AUC result of the BLUP model in the internal test set. <b>f)</b> Distribution of sample scores of BLUP model in external test set. the white line is the optimal threshold in e. <b>g)</b> The confusion matrix result of the BLUP model in the external test set, the result is obtained under the optimal threshold in e.

### Supplementary File
S4:GWAS_analysis_result.txt

S5:bayesA_snp_weight.txt

S6:blup_snp_weight.txt

S7:Enrichr_analysis_result.xlsx
