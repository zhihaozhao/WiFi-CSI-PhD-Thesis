# WiFi-CSI PhD Thesis Repository

This repository contains the LaTeX source files for the PhD dissertation on WiFi CSI sensing.

## Thesis Structure

**Title**: Deep Learning Approaches for Trustworthy WiFi Channel State Information Sensing: From Algorithm Design to Cross-Domain Validation

### Chapters

1. **Introduction** - Research background and motivation
2. **Literature Review** - State-of-the-art in WiFi CSI sensing
3. **Enhanced Model Architecture** - CNN+SE+Attention framework design
4. **Calibration and Reliability** - Trustworthy evaluation methodologies  
5. **Cross-Domain Generalization** - LOSO/LORO validation strategies
6. **Sim2Real Label Efficiency** - Few-shot learning for domain adaptation
7. **Experimental Validation** - Comprehensive benchmark evaluations
8. **Conclusion and Future Work** - Summary and research directions

## Repository Structure

- `chapters/` - Individual chapter LaTeX files
- `figures/` - Thesis figures and diagrams
- `appendices/` - Supplementary materials
- `main.tex` - Main thesis document
- `refs.bib` - Bibliography
- `formatting/` - University-specific formatting files
- `defense/` - Defense presentation materials

## Dependencies

- LaTeX distribution (TeX Live/MiKTeX)
- Required packages: `amsmath`, `graphicx`, `biblatex`, `hyperref`, etc.
- University thesis template (if applicable)

## Compilation

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## University Requirements

- [ ] Follow university formatting guidelines
- [ ] Include required front matter (abstract, acknowledgments, etc.)
- [ ] Meet minimum page/word count requirements
- [ ] Obtain supervisor approvals
- [ ] Submit for committee review

## Related Repositories

- **Core Code**: WiFi-CSI-Sensing-Core (algorithms and scripts)
- **Experimental Results**: WiFi-CSI-Sensing-Results (data and analysis)
- **Journal Paper**: WiFi-CSI-Journal-Paper (publication materials)

## Timeline

- [ ] Chapter drafts completion
- [ ] Internal review rounds
- [ ] Supervisor approval
- [ ] Committee submission
- [ ] Defense preparation
- [ ] Final submission

## Notes

This thesis incorporates and extends the work from the journal paper submissions and builds upon the experimental framework developed in the core repository.