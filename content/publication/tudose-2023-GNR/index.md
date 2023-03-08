---
title: "Gene essentiality in cancer is better predicted by mRNA abundance than by gene regulatory network-inferred activity"

date: '2023-03-06T00:00:00Z'

publishDate: 2023-03-06T00:00:00Z

authors: 
  - cosmin
  - Jonathan Bond
  - colm

publication_types: ["3"]

doi: 10.1101/2023.03.02.530664

add_badge: true

publication: "*bioRxiv*"

abstract: "Gene regulatory networks (GRNs) are often deregulated in tumor cells, resulting in altered transcriptional programs that facilitate tumor growth. These altered networks may make tumor cells vulnerable to the inhibition of specific regulatory proteins. Consequently, the reconstruction of GRNs in tumors is often proposed as a means to identify therapeutic targets. While there are examples of individual targets identified using GRNs, the extent to which GRNs can be used to predict sensitivity to targeted intervention in general remains unknown. Here we use the results of genome-wide CRISPR screens to systematically assess the ability of GRNs to predict sensitivity to gene inhibition in cancer cell lines. Using GRNs derived from multiple sources, including GRNs reconstructed from tumor transcriptomes and from curated databases, we infer regulatory gene activity in cancer cell lines from ten cancer types. We then ask, in each cancer type, if the inferred regulatory activity of each gene is predictive of sensitivity to CRISPR perturbation of that gene. We observe slight variation in the correlation between gene regulatory activity and gene sensitivity depending on the source of the GRN and the activity estimation method used. However, we find that there is consistently a stronger relationship between mRNA abundance and gene sensitivity than there is between regulatory gene activity and gene sensitivity. This is true both when gene sensitivity is treated as a binary and a quantitative property. Overall, our results suggest that gene sensitivity is better predicted by measured expression than by GRN-inferred activity."

tags:
  - gene regulatory network
  - gene dependency
  - CRISPR screens
  - transcription factor activity

featured: false

links:
  - name: Paper
    url: https://www.biorxiv.org/content/10.1101/2023.03.02.530664v2
  - name: Source Code
    url: https://github.com/cancergenetics/GRN_activity_corr_essentiality

---