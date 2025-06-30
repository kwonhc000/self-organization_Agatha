# Literary Systems as Complex Adaptive Systems: A Study of Motif Self-Organization in Agatha Christie's 66 Detective Novels

This repository contains the code, processed datasets, and analysis results supporting the research paper submitted to *Digital Scholarship in the Humanities*.

## Abstract

This study empirically demonstrates that literary works function as complex adaptive systems by analyzing the 56-year evolution of core motifs in Agatha Christie's 66 detective novels (1920-1976, totaling 4,243,056 words) from a complexity theory perspective.

## Key Findings

- **48%** of motifs (12/25) showed significant temporal correlations (|r| > 0.2, p < 0.05)
- **20** strong inter-motif correlations (|r| > 0.3) demonstrate co-evolutionary phenomena  
- **1935** identified as critical transition point with 12 motifs changing simultaneously
- **Shannon entropy decrease** (4.382 → 4.177) quantifies system self-organization
- **5 semantic clusters** emerged: legal/judgment, physical evidence, crime structure, spatial/atmospheric, character types

## Repository Contents

### Data Files
- `Christie_66list.csv` - List of 66 analyzed novels with metadata
- `motif_frequencies_25.csv` - Frequency matrix for 25 motifs across 66 novels
- `motif_correlations_25.csv` - Inter-motif correlation coefficients
- `significance_scores_25.csv` - Motif significance rankings
- `cluster_assignments_25.csv` - K-means clustering results
- `critical_points_25.csv` - Critical point analysis data
- `summary_statistics_25.csv` - Descriptive statistics
- `comprehensive_report_25motifs.txt` - Detailed analysis report

### Code
- `modified_code.txt` - Complete analysis pipeline

### Figures
- `Fig1_significance_ranking.png` - Motif significance scores
- `Fig2_temporal_evolution.png` - Time series patterns
- `Fig3_correlation_heatmap.png` - Inter-motif correlations
- `Fig4_motif_network.png` - Network analysis
- `Fig5_critical_points_analysis.png` - Critical transitions
- `Fig6_cluster_analysis.png` - Clustering results

## Methodology

Hybrid approach combining:
- **TF-IDF analysis** with genre-specific domain knowledge
- **Time series analysis** with 5-year moving averages
- **Network analysis** and correlation detection
- **K-means clustering** and critical point identification
- **Shannon entropy** calculation for self-organization measurement

## 25 Core Motifs

`garden`, `murderer`, `accident`, `study`, `motive`, `suicide`, `frightened`, `guilty`, `locked`, `clue`, `key`, `alibi`, `servant`, `weapon`, `evidence`, `room`, `poison`, `criminal`, `butler`, `victim`, `police`, `house`, `accused`, `enemy`, `nephew`, `niece`

## Reproducing the Analysis

**Prerequisites:** Python with pandas, numpy, scikit-learn, matplotlib, seaborn, networkx, scipy

**Copyright Notice:** Original Agatha Christie texts cannot be shared due to copyright restrictions. To replicate this study, obtain legal copies through academic libraries, legal digital collections, or commercial sources, then apply the methodology provided in `modified_code.txt`.

## Citation

```bibtex
@article{kwon_christie_2025,
  title={Literary Systems as Complex Adaptive Systems: A Study of Motif Self-Organization in Agatha Christie's 66 Detective Novels},
  author={Kwon, HC},
  journal={Digital Scholarship in the Humanities},
  year={2025},
  note={Data and code: https://github.com/kwonhc000/self-organization_Agatha}
}
```

## License

This work is licensed under the [MIT License](LICENSE).

## Contact

For questions about methodology or data: [Your Email]

---

**Note:** This repository supports computational literary analysis research. The methodology is applicable to other large literary corpora with appropriate domain-specific modifications.
