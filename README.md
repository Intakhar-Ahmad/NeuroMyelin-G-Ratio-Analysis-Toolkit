MyeliMetric: Open-Source G-Ratio Analysis Toolkit

Current Recommended Release: MyeliMetric V2.1

MyeliMetric is an open-source, Python-based toolkit for standardized post-segmentation analysis of the g-ratio, a widely used measure of myelin sheath thickness relative to axon diameter.

The toolkit simplifies quantitative axon–myelin analysis through automated data processing, customizable measurements, visualization, and statistical analysis.

MyeliMetric has evolved from its original published version (V1) to V2 and the current V2.1, with improvements in analytical flexibility, usability, reproducibility, and statistical rigor.

MyeliMetric Versions

V1 — Original Published Version (Legacy)

MyeliMetric V1 is the original published toolkit, designed to simplify conventional g-ratio analysis through an automated and standardized workflow.

It provides fundamental g-ratio measurements, data processing, and quantitative outputs.

Recommended for: Reproducing analyses conducted using the original published version.

Status: Legacy release.

V2 — Enhanced Quantitative Analysis

MyeliMetric V2 expanded the original toolkit by introducing improvements in processing flexibility, quality control, and data management.

Key features:

Adjustable g-ratio binning and measurement thresholds.

Pooled-control binning options for comparisons.

Improved Excel and CSV data export.

Automated output organization.

Activity logging and exclusion auditing.

Simplified analysis workflow and improved usability.

Recommended for: Researchers requiring flexible g-ratio quantification, customizable analysis settings, and expanded quality control.

Status: Previous release.

V2.1 — Current Recommended Version

MyeliMetric V2.1 builds upon V2 and introduces an important improvement in statistical analysis: support for hierarchical experimental designs involving multiple axons, tissue sections, and animals.

In typical myelin studies, multiple axons are measured from each tissue section, and several sections may originate from the same animal. These observations are not fully independent.

Conventional analyses that treat individual axons as independent biological replicates can introduce pseudoreplication, underestimate uncertainty, and produce misleading statistical conclusions.

V2.1 addresses this challenge by incorporating animal identity and section-level structure into the analysis workflow.

Key improvements:

Animal-level g-ratio analysis.

Support for multiple sections and axons within each animal.

Nested or hierarchical statistical analysis.

Clear distinction between biological replicates and subsampled measurements.

Improved reporting of experimental sample sizes.

Integration with the established V2 quantification and quality-control workflow.
