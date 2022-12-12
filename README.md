Transcriptional and translational dynamics underlying heat shock
response in the thermophilic Crenarchaeon *Sulfolobus acidocaldarius*
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

------------------------------------------------------------------------

## About this repository

This is the repository for the manuscript “Transcriptional and
translational dynamics underlying heat shock response in the
thermophilic Crenarchaeon *Sulfolobus acidocaldarius*” (Rani Baes *et
al*).

## Analysis

### TMT-labeled Liquid Chromatography-Tandem-Mass-Spectrometry

> Compare Supplementary Methods section in the Supplementary
> Information.

Differential protein expression analysis was performed using the DEqMS
pipeline for TMT-labeled MS data ([Zhu et al.
2020](#ref-zhu_deqms_2020)). To this end, protein abundance values were
log2 transformed, replicate outliers removed and data normalized to have
equal medians in all samples. Benjamini-Hochberg corrected p-values
([Benjamini and Hochberg 1995](#ref-benjamini_controlling_1995)) were
considered statistically significant at a threshold \< 0.05.  
The protein expression analysis workflow can be found in the [DEqMS
folder](DEqMS).

------------------------------------------------------------------------

## License

This project is under the general MIT License - see the
[LICENSE](LICENSE) file for details

------------------------------------------------------------------------

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-benjamini_controlling_1995" class="csl-entry">

Benjamini, Yoav, and Yosef Hochberg. 1995. “Controlling the False
Discovery Rate: A Practical and Powerful Approach to Multiple Testing.”
*Journal of the Royal Statistical Society: Series B (Methodological)* 57
(1): 289–300. <https://doi.org/10.1111/j.2517-6161.1995.tb02031.x>.

</div>

<div id="ref-zhu_deqms_2020" class="csl-entry">

Zhu, Yafeng, Lukas M. Orre, Yan Zhou Tran, Georgios Mermelekas, Henrik
J. Johansson, Alina Malyutina, Simon Anders, and Janne Lehtiö. 2020.
“DEqMS: A Method for Accurate Variance Estimation in Differential
Protein Expression Analysis.” *Molecular & Cellular Proteomics: MCP* 19
(6): 1047–57. <https://doi.org/10.1074/mcp.TIR119.001646>.

</div>

</div>
