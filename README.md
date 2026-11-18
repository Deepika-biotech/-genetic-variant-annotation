# -genetic-variant-annotation
# Automated Genetic Variant Annotation and Pathogenicity Prioritization Using Python

## Project Overview
This project demonstrates an automated workflow for extracting, organizing, and classifying genetic variant information from the NCBI ClinVar database using Python.

The workflow processes VCF data, extracts clinical significance and disease information, categorizes variants, and assigns simplified review-evidence priority levels.

## Objectives
- Extract genetic variant information from a VCF file.
- Retrieve clinical significance and associated disease information.
- Classify variants into Pathogenic, Benign, VUS, and Other categories.
- Analyze ClinVar review status.
- Generate statistical summaries and visualizations.
- Export annotated variant information into a CSV report.

## Dataset
- Source: NCBI ClinVar
- Reference genome: GRCh38
- File format: VCF (.vcf.gz)
- Records analyzed: First 1,000 records from the downloaded dataset.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- VCF file processing

## Workflow
1. Download ClinVar GRCh38 VCF dataset.
2. Upload the compressed VCF file to Google Colab.
3. Extract variant information from VCF records.
4. Parse clinical significance, disease, and review status.
5. Categorize genetic variants.
6. Perform statistical analysis.
7. Generate variant classification visualization.
8. Assign simplified review-evidence priority.
9. Export the final annotated results as a CSV file.

## Project Outputs
- Variant annotation notebook (.ipynb)
- Annotated variant report (.csv)
- Variant classification visualization (.png)

## Important Note
This project is an educational bioinformatics portfolio prototype. Variant classifications are obtained from ClinVar and are not independently established by this workflow. The simplified review-priority categories are for demonstration only and do not represent official ClinVar ratings or clinical recommendations.

Only the first 1,000 records were analyzed. Therefore, the results should not be interpreted as representative of the complete ClinVar database.

## Author
B. Deepika  
B.Sc. Biotechnology | Bioinformatics
