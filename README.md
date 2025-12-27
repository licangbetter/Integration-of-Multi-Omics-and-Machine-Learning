Project Code Repository: File Descriptions	
This repository contains all data. "Methylation-modified CAPG mediates bilirubin metabolism in sepsis via monocytes/macrophages derived from Integration of Multi-Omics and Machine Learning".
	
1. Bulk Screening Results	
These files contain the results of initial large-scale analyses used to screen for genes and proteins associated with sepsis risk.	
File Name	Description
eQTL_results_unfiltered.txt	"Raw, unfiltered results from the two-sample Mendelian Randomization (MR) analysis using eQTL data, testing the association between genetically predicted gene expression and sepsis risk."
eQTL_results_filtered.txt	List of genes with a significant causal association with sepsis risk after multiple testing correction (FDR < 0.05) in the eQTL MR analysis.
pQTL_results_filtered.txt	List of plasma proteins with a significant causal association with sepsis risk after multiple testing correction (FDR < 0.05) in the pQTL MR analysis.
GSE28750_diffgene.txt	"Results of differential expression analysis on the GEO dataset GSE28750, listing genes significantly dysregulated in sepsis patients versus healthy controls (log2FC, adjusted p-value)."
2. Mendelian Randomization Analysis Files for Candidate Genes	
"These files contain the detailed results of MR analyses performed for each of the four candidate genes (ALDH1A1, CAPG, PCSK7, POR) identified in the intersection analysis. For each gene, separate analyses were run using expression Quantitative Trait Loci (eQTL) and protein QTL (pQTL) data."	
ALDH1A1 Gene & Protein	
File Name	Description
aldh1a1_eqtl_harmonise.txt	Allele harmonization results for ALDH1A1 eQTL instrumental variables and the sepsis outcome data.
aldh1a1_eqtl_heterogeneity.txt	Heterogeneity test results (Cochran's Q) for the ALDH1A1 eQTL MR analysis.
aldh1a1_eqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the ALDH1A1 eQTL MR analysis.
aldh1a1_eqtl_pleiotropy.txt	Horizontal pleiotropy test results (MR-Egger intercept) for the ALDH1A1 eQTL MR analysis.
aldh1a1_eqtl_presso.txt	MR-PRESSO outlier detection and corrected results for the ALDH1A1 eQTL MR analysis.
aldh1a1_eqtl_singlesnpOR.txt	Leave-one-out sensitivity analysis results for the ALDH1A1 eQTL MR analysis.
aldh1a1_pqtl_harmonise.txt	Allele harmonization results for ALDH1A1 pQTL instrumental variables and the sepsis outcome data.
aldh1a1_pqtl_heterogeneity.txt	Heterogeneity test results for the ALDH1A1 pQTL MR analysis.
aldh1a1_pqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the ALDH1A1 pQTL MR analysis.
aldh1a1_pqtl_pleiotropy.txt	Horizontal pleiotropy test results for the ALDH1A1 pQTL MR analysis.
aldh1a1_pqtl_presso.txt	MR-PRESSO results for the ALDH1A1 pQTL MR analysis.
aldh1a1_pqtl_singlesnpOR.txt	Leave-one-out sensitivity analysis results for the ALDH1A1 pQTL MR analysis.
CAPG Gene & Protein	
File Name	Description
capg_eqtl_harmonise.txt	Allele harmonization results for CAPG eQTL instrumental variables and the sepsis outcome data.
capg_eqtl_heterogeneity.txt	Heterogeneity test results for the CAPG eQTL MR analysis.
capg_eqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the CAPG eQTL MR analysis.
capg_eqtl_pleiotropy.txt	Horizontal pleiotropy test results for the CAPG eQTL MR analysis.
capg_eqtl_presso.txt	MR-PRESSO results for the CAPG eQTL MR analysis.
capg_eqtl_singlesnpOR.txt	Leave-one-out sensitivity analysis results for the CAPG eQTL MR analysis.
capg_pqtl_harmonise.txt	Allele harmonization results for CAPG pQTL instrumental variables and the sepsis outcome data.
capg_pqtl_heterogeneity.txt	Heterogeneity test results for the CAPG pQTL MR analysis.
capg_pqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the CAPG pQTL MR analysis.
capg_pqtl_pleiotropy.txt	Horizontal pleiotropy test results for the CAPG pQTL MR analysis.
capg_pqtl_presso.txt	MR-PRESSO results for the CAPG pQTL MR analysis.
capg_pqtl_singlesnpOR.txt	Leave-one-out sensitivity analysis results for the CAPG pQTL MR analysis.
PCSK7 Gene & Protein	
File Name	Description
pcsk7_eqtl_harmonise.txt	Allele harmonization results for PCSK7 eQTL instrumental variables and the sepsis outcome data.
pcsk7_eqtl_heterogeneity.txt	Heterogeneity test results for the PCSK7 eQTL MR analysis.
pcsk7_eqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the PCSK7 eQTL MR analysis.
pcsk7_eqtl_pleiotropy.txt	Horizontal pleiotropy test results for the PCSK7 eQTL MR analysis.
pcsk7_pqtl_harmonise.txt	Allele harmonization results for PCSK7 pQTL instrumental variables and the sepsis outcome data.
pcsk7_pqtl_heterogeneity.txt	Heterogeneity test results for the PCSK7 pQTL MR analysis.
pcsk7_pqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the PCSK7 pQTL MR analysis.
pcsk7_pqtl_pleiotropy.txt	Horizontal pleiotropy test results for the PCSK7 pQTL MR analysis.
pcsk7_pqtl_presso.txt	MR-PRESSO results for the PCSK7 pQTL MR analysis.
pcsk7_pqtl_singlesnpOR.txt	Leave-one-out sensitivity analysis results for the PCSK7 pQTL MR analysis.
POR Gene & Protein	
File Name	Description
por_eqtl_harmonise.txt	Allele harmonization results for POR eQTL instrumental variables and the sepsis outcome data.
por_eqtl_heterogeneity.txt	Heterogeneity test results for the POR eQTL MR analysis.
por_eqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the POR eQTL MR analysis.
por_eqtl_pleiotropy.txt	Horizontal pleiotropy test results for the POR eQTL MR analysis.
por_pqtl_harmonise.txt	Allele harmonization results for POR pQTL instrumental variables and the sepsis outcome data.
por_pqtl_heterogeneity.txt	Heterogeneity test results for the POR pQTL MR analysis.
por_pqtl_OR.txt	Odds Ratios (OR) and confidence intervals from the POR pQTL MR analysis.
por_pqtl_pleiotropy.txt	Horizontal pleiotropy test results for the POR pQTL MR analysis.
por_pqtl_presso.txt	MR-PRESSO results for the POR pQTL MR analysis.
por_pqtl_singlesnpOR.txt	Leave-one-out sensitivity analysis results for the POR pQTL MR analysis.
3. Experimental Validation Data	
These files contain the qRT-PCR results used to independently validate the expression of the key gene CAPG in clinical samples.	
File Name	Description
CAPG_PCR_healthy_human_serum.txt	ΔCt values from qRT-PCR measuring CAPG mRNA expression in serum from healthy volunteers (control group).
CAPG_PCR_icu_uncorrected.txt	"Raw, uncorrected ΔCt values from qRT-PCR measuring CAPG mRNA expression in serum from the prospective ICU patient cohort."
CAPG_PCR_icu_corrected.txt	"Batch-effect corrected ΔCt values (using a universal reference sample and ComBat algorithm) for CAPG expression in the ICU cohort, used for final model construction."
4. Methylation QTL (mQTL) Mediation Analysis Files	
"These files support the analysis of upstream epigenetic regulation, specifically how DNA methylation of a CpG site influences CAPG expression and sepsis risk."	
File Name	Description
mqtl_cg_gene.txt	Results of the methylation QTL (mQTL) analysis testing the association between the CpG site cg04881903 and CAPG gene expression.
mqtl_cg_outcome.txt	Results of the MR analysis testing the total effect of the CpG site cg04881903 on sepsis risk.
mqtl_gene_outcome.txt	Results of the MR analysis testing the effect of CAPG gene expression on sepsis risk (used in the mediation analysis).
mqtl_mediation_effect.txt	Results of the two-step MR mediation analysis quantifying the proportion of the CpG site's effect on sepsis risk that is mediated through CAPG expression.
5. Metabolite Mediation Analysis Files	
"These files support the analysis of downstream metabolic regulation, screening for metabolites causally influenced by CAPG and assessing their role in sepsis risk."	
File Name	Description
met_gene_outcome.txt	Results of the MR analysis confirming the total effect of CAPG gene expression on sepsis risk.
met_gene_metabolite_result.txt	Results of the MR screening analysis identifying blood metabolites whose levels are potentially causally influenced by CAPG expression.
met_metabolite_out_result.txt	Results of the MR analysis verifying the causal association between the candidate metabolites (from the previous screen) and sepsis risk.
met_mediation_effect.txt	"Results of the two-step MR mediation analysis quantifying the proportion of CAPG's effect on sepsis risk that is mediated through specific metabolites (e.g., bilirubin)."
6. Model Performance Comparison	
File Name	Description
Data Model Comparison.txt	"Summary of performance metrics (e.g., AUC) for different machine learning models, comparing their performance on internal hospital data (with and without CAPG) and external MIMIC-IV data."
