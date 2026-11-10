# Run 3 dilepton trigger AN

Build with `make -f Make` (CMS tdr utilities and TeX required).

The package includes the complete LaTeX draft, CMS template utilities, 226 selected vector-PDF plots (113 per year), both original ROOT correction files, and the latest compiled PDF.

Results, uncertainty breakdowns, and appendix diagnostics are separated into 2024 and 2025. Original plot luminosities are 109.82/fb and 110.37/fb, respectively. Figures are under figures/2024 and figures/2025.

The JSON manifests record source-to-package mappings; they are optional and are not used for compilation. FIGURE_COVERAGE.md records the selection scope. No new SF values or uncertainties were computed.

The independent application-validation study is pending and is retained in validation.tex without being included in the compiled note. Remaining scientific checks are marked explicitly in the draft, including actual datasets/certification, statistical interval construction, correlation-uncertainty combination, and ROOT lookup/error semantics.
