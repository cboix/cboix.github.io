---
title: "Single-nucleus alternative polyadenylation repository"
author_profile: false
layout: project
# layout: single
excerpt: This is a repository for the data release for the paper on the landscape and regulation of alternative polyadenylation in the brain at the cell type level.
---

---

##### Overview

This is a supplementary website for: _Single-cell landscape and regulation of alternative polyadenylation in the brain_

We report a single-nucleus atlas of alternative polyadenylation (APA) of the aged human brain across 2 million cells from 379 human post-mortem brains across aged individuals with and without Alzheimer’s disease (AD).

&nbsp;
{% include figure image_path='./assets/img/snAPA_overview_figure.png' alt='snRNA-seq profiling overview' width='100%' caption='**Cohort overview:** A cell-type-specific atlas of alternative polyadenylation in the aged human brain. We use single-nucleus data to report the APA landscape of the pre-frontal cortex, AD-differential changes and 3\'UTR QTLs in each cell type, and interpret GWAS loci for brain traits.' %}

We also integrate APA variation with whole genome sequencing (WGS) to identify cell-type-resolved 3'UTR quantitative trait loci (3’aQTLs) for 4,288 APAs. We find that 3’aQTLs preferentially colocalize with pQTLs over eQTLs. This extends to 168 GWAS and 3'aQTL colocalized loci, of which only 17.5% are shared with eQTLs. APA provides a complementary and largely independent mechanistic layer both for understanding gene regulatory changes in disease, as well as for interpreting non-coding genetic variation in brain traits and diseases.

<!-- TODO: add the supplementary tables too -->
- Summary analyses are currently available as supplementary tables below.
- Analysis code for the paper can be found on [github](https://github.com/xiongxslab/NanJ_Carles_et_al_3aQTL_project)
- RNA-seq data for the knock-down experiments for regulator validation are available at National Genomics Data Center (NGDC) under the accession [HRA014304](https://ngdc.cncb.ac.cn/gsa-human/browse/HRA014304)
- In addition to resources provided below and on [Synapse](https://www.synapse.org/#!Synapse:syn52293442), the original single-cell transcriptomic dataset is available for interactive visualization through the [UCSC Cell Browser](https://cells.ucsc.edu/?ds=rosmap-ad-aging-brain+ad-aging-brain), as part of the [AD and Aging brain atlas](https://compbio.mit.edu/ad_aging_brain/)
<!-- TODO: Add Zenodo link -->
<!-- or on [zenodo](https://doi.org/10.5281/zenodo.11051021). -->

**Contact:** Xushen Xiong - xiongxs at zju dot edu dot cn / Carles Boix - carles_boix at hms dot harvard dot edu

---

##### Datasets

Datasets corresponding to manuscript analyses can be found [here](https://personal.broadinstitute.org/cboix/snAPA_data/) and are summarized in the table below. Processed human datasets have been deidentified to protect confidentiality - the mapping to ROSMAP IDs and complete metadata can be found on [Synapse](https://www.synapse.org/#!Synapse:syn52293417).

| Dataset | Files | Description |
| ---------   | -------- | ----------- |
| Individual metadata | Table ([tsv](https://personal.broadinstitute.org/cboix/snAPA_data/individual_metadata_deidentified.tsv)) |  De-identified individual-level metadata from aging and AD [atlas](https://compbio.mit.edu/ad_aging_brain) |
| APA definitions | Table ([tsv](https://personal.broadinstitute.org/cboix/snAPA_data/All_cts.Merged.pASite_MeanPDUI.tsv), [rds](https://personal.broadinstitute.org/cboix/snAPA_data/All_cts.Merged.pASite_MeanPDUI.rds)) | APA definitions and mean PDUI values across cell types |
| Individual-level APA matrices | Directory with [rds files](https://personal.broadinstitute.org/cboix/snAPA_data/APA_matrices/) | Individual-level APA matrices (PDUI values) for each cell type |
| AD differential APAs (DAPAs) | Table ([tsv](https://personal.broadinstitute.org/cboix/snAPA_data/All_cts.AD_DAPA.gAPA_risk_annotated.Merged.tsv), [xlsx](https://personal.broadinstitute.org/cboix/snAPA_data/All_cts.AD_DAPA.gAPA_risk_annotated.Merged.xlsx)) | Differential APAs associated with Alzheimer's disease status in each cell type. Genes are annotated with AD risk gene status, 3'aQTL status, and AD GWAS colocalization status |
| 3'aQTL and eQTL summary statistics | Directory with [sumstat files](https://personal.broadinstitute.org/cboix/snAPA_data/apaQTL_sumstats/) | Summary statistics for 3'aQTL and eQTL mapping in each cell type |
| Genetically regulated APAs | Tables ([tsv](https://personal.broadinstitute.org/cboix/snAPA_data/All_cts.gAPA.Merged.tsv), [xlsx](https://personal.broadinstitute.org/cboix/snAPA_data/All_cts.gAPA.Merged.xlsx)) | Merged table of all APA sites with genetic regulation (g-APA) in each cell type, identified through 3'aQTL mapping |

Complete human raw data were released as part of the [AD and Aging brain atlas](https://compbio.mit.edu/ad_aging_brain/) in collaboration with ROSMAP through [Synapse (syn52293442)](https://www.synapse.org/#!Synapse:syn52293442). The data and human metadata must be accessed through [Synapse](https://adknowledgeportal.synapse.org/) with a [Data Use Certificate (DUC)](https://adknowledgeportal.synapse.org/Data%20Access). Human metadata can be found at [Synapse (syn3157322)](https://www.synapse.org/#!Synapse:syn3157322) or can be requested through the [RADC Hub](https://www.radc.rush.edu/).
