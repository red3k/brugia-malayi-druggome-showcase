# Proteome-wide reverse docking in *Brugia malayi*

**Independent computational study · Research Square preprint, version 1 (17 July 2026)**

This study used a reverse-docking workflow to investigate compound 6a, a glycyrrhetinic acid analog with reported antifilarial activity, and to prioritize a candidate protein target in *Brugia malayi*.

## Approach reported in the preprint

- Started from a set of 589 essential parasite protein targets and retained 395 AlphaFold models meeting the reported mean pLDDT threshold.
- Used predicted binding pockets and AutoDock Vina to screen compound 6a across the filtered target set.
- Prioritized mitochondrial ATP synthase subunit β (UniProt A0A4E9FU14) for follow-up, including repeated docking and comparison with a human ortholog.
- Used pocket prediction and protein–ligand interaction profiling as complementary computational analyses.

## Main computational finding

The preprint reports a mean Vina score of −8.818 ± 0.122 kcal/mol for compound 6a in the selected parasite target pocket and a modest predicted difference versus the human ortholog. These are docking predictions; they do not establish binding, selectivity, biological activity, or a validated mechanism.

## Limitations and status

The work is computational and awaits experimental validation. The paper notes that the predicted selectivity difference is modest and within the uncertainty of empirical docking scores. Molecular-dynamics simulations and experimental studies are identified as future validation steps.

This page summarizes the preprint and is not a reproducible code release. The current local druggome tracker and ATP synthase workbench have different target counts and docking-run settings from those reported in the manuscript; the exact versioned inputs and workflow need reconciliation before claiming reproducibility.

## Reference

K. Dubey, “Unmasking the Black Box: Computational Evidence Identifying Mitochondrial ATP Synthase Subunit β as a High-Confidence Target of Glycyrrhetinic Acid Analogs Against *Brugia malayi*,” Research Square, v1, 2026. [https://doi.org/10.21203/rs.3.rs-10383379/v1](https://doi.org/10.21203/rs.3.rs-10383379/v1)

No separate license is provided for this summary. Refer to the linked preprint for its stated CC BY 4.0 terms.
