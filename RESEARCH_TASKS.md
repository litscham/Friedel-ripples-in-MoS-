# Research Tasks for Friedel Ripples in MoS₂ Thesis

This document outlines all research tasks and milestones needed to complete this PhD thesis. Tasks are organized by category and can be converted into GitHub issues.

---

## Phase 1: Literature Review & Theoretical Foundation

### 1.1 Literature Review: Friedel Oscillations in Bulk Materials
**Objective:** Comprehensive literature review on classical Friedel oscillations theory and experiments

**Tasks:**
- Study Friedel's original 1952 paper and foundational concepts
- Review phase shift analysis and scattering theory
- Document Friedel sum rule derivations
- Compile experimental observations in metals and alloys
- Create comparison table of oscillation characteristics vs material type

**Deliverable:** Literature review section (2000-3000 words)

---

### 1.2 Literature Review: Electronic Structure of MoS₂
**Objective:** Deep dive into MoS₂ crystal structure, band structure, and electronic properties

**Tasks:**
- Document MoS₂ crystal structure and symmetry (2H phase)
- Review band structure calculations from literature
- Study direct bandgap properties in monolayers
- Investigate spin-orbit coupling effects
- Compare with other TMD materials

**Deliverable:** MoS₂ electronic properties section with figures and tables

---

### 1.3 Literature Review: Defects in 2D Materials
**Objective:** Comprehensive review of point defects and their characterization

**Tasks:**
- Classify defect types: vacancies, antisites, adatoms
- Study formation energies and thermodynamics
- Review defect-induced state localization
- Document experimental defect imaging techniques
- Analyze charge state effects on defect properties

**Deliverable:** Defects section with classification and properties table

---

### 1.4 Literature Review: STEM-EELS Techniques
**Objective:** Master scanning transmission electron microscopy and electron energy loss spectroscopy fundamentals

**Tasks:**
- Study STEM operating principles and electron beam interactions
- Review STEM imaging modes (bright-field, dark-field, HAADF)
- Learn EELS measurement principles and spectroscopic capabilities
- Document spatial and energy resolution limits
- Compile examples of defect characterization in 2D materials via STEM-EELS
- Study local density of states mapping through EELS

**Deliverable:** STEM-EELS methods section with technical specifications and diagrams

---

### 1.5 Theoretical Framework: Quantum Scattering Theory
**Objective:** Develop mathematical framework for electron-defect scattering

**Tasks:**
- Derive Friedel sum rule from first principles
- Work through phase shift calculations
- Develop Born approximation treatment
- Apply to 2D electron systems
- Document perturbation theory approach

**Deliverable:** Theory chapter section with derivations and equations

---

### 1.6 Theoretical Framework: Green's Function Formalism
**Objective:** Master Green's function approach for defect scattering in 2D

**Tasks:**
- Study free electron Green's function
- Derive retarded/advanced propagators in 2D
- Apply to defect potential perturbations
- Calculate local density of states (LDOS) via Green's functions
- Document Fourier transform relationships

**Deliverable:** Detailed mathematical framework with Green's function relations

---

## Phase 2: Computational Setup & Validation

### 2.1 Computational Setup: DFT Code Implementation
**Objective:** Establish and validate DFT computational workflow

**Tasks:**
- Install and configure VASP or Quantum ESPRESSO
- Set up pseudopotentials (PAW or norm-conserving)
- Create test systems for convergence testing
- Validate exchange-correlation functionals (GGA, HSE)
- Document all computational parameters

**Deliverable:** Computational methods documentation and parameter files

---

### 2.2 Computational: Pristine MoS₂ Reference System
**Objective:** Calculate and validate defect-free monolayer MoS₂

**Tasks:**
- Construct 2D supercell for monolayer MoS₂
- Optimize atomic geometry
- Calculate band structure and compare with literature
- Compute density of states (DOS)
- Generate LDOS maps at different energies

**Deliverable:** Reference system data: band structure plots, DOS figures, validated geometry

---

### 2.3 Computational: Mo Vacancy Defects
**Objective:** Complete DFT study of Mo vacancies

**Tasks:**
- Create supercells with Mo vacancies
- Optimize atomic geometry with/without symmetry constraints
- Calculate electronic structure and band structure
- Map LDOS around vacancy site
- Analyze charge density redistribution
- Study multiple supercell sizes for convergence

**Deliverable:** Mo vacancy results: relaxed geometries, band structures, LDOS maps, energy data

---

### 2.4 Computational: S Vacancy Defects
**Objective:** Complete DFT study of S vacancies

**Tasks:**
- Create supercells with S vacancies (single and double)
- Optimize atomic geometry
- Calculate electronic structure
- Map LDOS around vacancy sites
- Analyze local charge redistribution
- Compare with Mo vacancy effects

**Deliverable:** S vacancy results: geometries, electronic structures, comparative LDOS maps

---

### 2.5 Computational: Antisite Defects
**Objective:** Study Mo-S and S-Mo antisite defects

**Tasks:**
- Create supercells with antisite substitutions
- Optimize geometries with symmetry variations
- Calculate band structures and DOS
- Map LDOS for both defect types
- Analyze hybridization effects
- Compare with vacancy-induced changes

**Deliverable:** Antisite defect results: structures, electronic properties, LDOS visualizations

---

## Phase 3: Analysis & Characterization

### 3.1 Analysis: Friedel Oscillation Wavelength
**Objective:** Extract and characterize wavelengths of Friedel ripples

**Tasks:**
- Write Python scripts for LDOS Fourier analysis
- Extract oscillation wavelengths from spatial maps
- Relate wavelengths to Fermi wavevector (k_F)
- Compare with theoretical predictions (λ_F = 2π/k_F)
- Create wavelength vs defect type table

**Deliverable:** Wavelength analysis figures and comparative tables

---

### 3.2 Analysis: Oscillation Amplitude Study
**Objective:** Characterize amplitude of Friedel ripples

**Tasks:**
- Quantify LDOS oscillation amplitudes
- Analyze decay with distance from defect
- Study amplitude dependence on defect strength
- Compare with theoretical models
- Document amplitude vs energy relationships

**Deliverable:** Amplitude analysis plots and functional relationships

---

### 3.3 Analysis: Energy Dependence Study
**Objective:** Investigate Friedel oscillations as function of energy

**Tasks:**
- Calculate LDOS at multiple energy slices
- Create energy-dependent LDOS maps
- Analyze oscillation wavelength vs energy
- Study resonance features
- Compare with band structure features

**Deliverable:** Energy-dependent LDOS maps and wavelength-energy plots

---

### 3.4 Analysis: STEM-EELS Simulation
**Objective:** Generate simulated STEM-EELS spectra and maps from computed LDOS

**Tasks:**
- Implement STEM imaging simulator for ADF (Annular Dark Field) contrast
- Implement EELS simulator for core-loss and low-loss spectroscopy
- Convert LDOS to simulated STEM-EELS signals
- Vary electron probe energy and collection angles
- Compare simulated signals with theoretical patterns
- Generate publication-quality energy-filtered maps

**Deliverable:** Simulated STEM-EELS images and spectra for all defect types

---

### 3.5 Analysis: Defect-Specific Signatures
**Objective:** Identify unique electronic signatures for defect identification

**Tasks:**
- Compare LDOS patterns across defect types
- Identify differentiating features (wavelength, symmetry, amplitude)
- Study charge state effects on signatures
- Create decision tree for experimental defect identification
- Document distinguishing characteristics

**Deliverable:** Comprehensive comparison table and signature schematic diagrams

---

### 3.6 Analysis: Comparison with Scattering Theory
**Objective:** Validate DFT results against theoretical predictions

**Tasks:**
- Calculate expected oscillations from scattering theory
- Compare theoretical predictions with DFT LDOS
- Analyze discrepancies (if any)
- Study effective scattering potential from DFT
- Document agreement/disagreement metrics

**Deliverable:** Theory vs computation comparison figures and quantitative analysis

---

## Phase 4: Experimental Implications & Comparisons

### 4.1 Experimental Implications: STEM-EELS Detection Feasibility
**Objective:** Assess experimental observability of Friedel ripples via STEM-EELS

**Tasks:**
- Analyze required STEM spatial resolution for ripple imaging
- Study electron beam energy effects on contrast
- Estimate signal-to-noise requirements for EELS measurements
- Review experimental STEM-EELS capabilities in literature
- Propose optimal experimental conditions (beam energy, collection angle)
- Compare detection feasibility across different STEM modes

**Deliverable:** Experimental feasibility assessment with technical recommendations

---

### 4.2 Comparison Study: 2D vs Bulk Systems
**Objective:** Systematically compare MoS₂ results with bulk systems

**Tasks:**
- Collect Friedel oscillation data from bulk systems
- Compare wavelengths and amplitudes
- Study dimensionality effects
- Analyze band structure influence
- Document fundamental differences

**Deliverable:** Comparative analysis with figures showing 2D vs 3D differences

---

### 4.3 Comparison Study: Other 2D Materials
**Objective:** Compare with Friedel oscillations in graphene, WS₂, etc.

**Tasks:**
- Collect data on other 2D TMDs if available
- Compare with graphene studies
- Analyze material-specific effects
- Document material parameter influences
- Create unified 2D materials comparison

**Deliverable:** Cross-material comparison table and analysis

---

## Phase 5: Manuscript Preparation

### 5.1 Manuscript: Methods Section
**Objective:** Write comprehensive computational methods section

**Tasks:**
- Document DFT parameters and convergence tests
- Explain supercell construction and k-point sampling
- Detail LDOS calculation procedures
- Describe STEM-EELS simulation methods
- Document relationship between LDOS and STEM-EELS observables
- Include computational resource requirements

**Deliverable:** Complete methods section (3500-4500 words) with parameter table and diagrams

---

### 5.2 Manuscript: Results Section
**Objective:** Present research findings clearly and comprehensively

**Tasks:**
- Organize results logically (pristine → defects → analysis)
- Create high-quality figures with proper captions
- Present data tables with key metrics
- Write clear descriptive text for each result
- Ensure consistent notation and terminology

**Deliverable:** Complete results chapter (4000-5000 words) with 15-20 figures

---

### 5.3 Manuscript: Discussion Section
**Objective:** Interpret findings and place in broader context

**Tasks:**
- Interpret Friedel oscillation characteristics
- Compare with theoretical predictions
- Discuss band structure influences
- Address experimental implications
- Identify limitations and uncertainties
- Propose extensions and future work

**Deliverable:** Discussion chapter (3000-4000 words)

---

### 5.4 Manuscript: Conclusion and Outlook
**Objective:** Summarize contributions and future directions

**Tasks:**
- Summarize key scientific findings
- Highlight novel contributions
- Discuss implications for defect physics in 2D
- Suggest experimental validation approaches
- Outline potential applications
- Propose future research directions

**Deliverable:** Conclusion chapter (1500-2000 words)

---

## Phase 6: Supplementary Materials & Finalization

### 6.1 Appendix: Supplementary Computational Data
**Objective:** Organize and document additional computational results

**Tasks:**
- Prepare additional LDOS maps for appendix
- Create supplementary band structure plots
- Document convergence test results
- Include raw data tables
- Organize all data in structured format

**Deliverable:** Complete appendix with supplementary figures and data

---

### 6.2 Appendix: Computational Scripts
**Objective:** Document and archive analysis and visualization code

**Tasks:**
- Clean up Python scripts for LDOS processing
- Document MATLAB routines for analysis
- Create README with usage instructions
- Version scripts appropriately
- Ensure reproducibility

**Deliverable:** Documented code archive with version history

---

### 6.3 Bibliography & References
**Objective:** Finalize and validate all citations

**Tasks:**
- Verify all cited references are complete
- Check formatting consistency
- Validate DOIs and URLs
- Ensure comprehensive coverage
- Cross-reference chapter citations

**Deliverable:** Final, validated bibliography file (references.bib)

---

### 6.4 Thesis Proofreading
**Objective:** Polish thesis for final submission

**Tasks:**
- Spell check and grammar review
- Verify formatting consistency throughout
- Check figure and table numbering
- Review equation formatting
- Ensure cross-reference accuracy

**Deliverable:** Final, proofread thesis document

---

### 6.5 Final Thesis Compilation
**Objective:** Prepare thesis for submission

**Tasks:**
- Compile complete LaTeX document
- Generate table of contents and indices
- Create PDF with proper bookmarks
- Verify all cross-references work
- Test hyperlinks

**Deliverable:** Final thesis PDF ready for submission

---

## Timeline & Priority

### High Priority (Critical Path)
- [x] Literature review (all sections)
- [x] Theoretical framework development
- [ ] Pristine MoS₂ calculations
- [ ] Mo vacancy calculations
- [ ] S vacancy calculations
- [ ] Friedel oscillation analysis
- [ ] Results manuscript

### Medium Priority
- [ ] Antisite defect calculations
- [ ] STEM-EELS simulation and comparison
- [ ] Energy dependence study
- [ ] Discussion manuscript

### Lower Priority (Important but Flexible)
- [ ] 2D vs bulk comparison
- [ ] Cross-material comparison
- [ ] Supplementary materials
- [ ] Final polishing and formatting

---

## Notes

- Regular commits to GitHub should track progress on computational work
- Each major computational calculation should be its own branch/PR
- Manuscript sections should be drafted progressively
- Figures should be finalized as calculations complete
