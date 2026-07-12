# Identification & Provenance

**Publication Title**: The title of the observed scientific literature. <br>
**Publication Type**: The type of publication of the observed literature (book, scientific paper, etc.). <br>
**DOI**: The unique identifier of the observed scientific literature. <br>
**URL**: The URL link to the observed scientific literature.<br>
**ISBN**: The unique numerical identifier that is assigned to books and book-like products published internationally. <br>
**Journal**: The scientific journal the literature was published in. <br>
**Author**: The first author of the literature. <br>
**Publisher**: The publisher of the literature. <br>
**Publication Date**: The date that the literature was published. (mm-dd-yyyy)<br>
**Version Information**: The most recent version of the observed scientific literature.<br>
**Contributor ORCIDs**: The unique researcher IDs of any contributors to the data in the literature.<br>
**Licensing Terms**: Licensing terms of the observed scientific literature. (MIT; open access or subscribe)<br>

# Table Identifiers

**Source Title**: The title of the literature the peak is observed in.<br>
**Page Number**: The page number of the literature that the table is located on.<br>
**Table Title**: The title of the table the peak data is displayed in.<br>
**Table Description**: The description of the table given in the observed literature.<br>
**References**: A list of references specified in the table or in context of the table. (Usually presented as [130-132, 134-136] or a similar format and may require further interpretation)<br>

# Instrument / Acquisition Parameters

**Instrument Information**: A description of the instruments used in the spectral data measurements (spectrometer, laser, detector, etc.).<br>
**Resolution**: The resolution of the spectrometer used (4 cm^-1, etc.). <br>
**Resolution Units**: The units used for the resolution of the spectrometer used (cm^-1). <br>
**Laser Wavelength**: The wavelength of the laser used to capture the observed spectroscopy data.<br>
**Laser Power**: The power of the laser used to capture the observed spectroscopy data (measured in mW). If a pulsed laser was used, this is the average power delivered over the course of the laser pulses.<br>
**Laser Diameter**: The spot size diameter of the laser used during measurement (2 microm, etc.)<br>
**Pulse Duration**: The duration of laser pulses (Continuous if not pulsed)<br>
**Integration time**: The duration that the detector collected photons from the analyte.<br>
**Objective**: A description of the objective lens used for the experiment.<br>
**Spectral Range High**: The upper bound of the spectral range observed from the experiment in cm^-1.<br>
**Spectral Range Low**: The lower bound of the spectral range observed in the experiment. in cm^-1<br>
**Acquisition Mode**: The strategy used to capture the data from the detector (static, average, time-series, etc.)<br>
**Temperature**: The temperature of the analyte during the measurement. <br>
**Temperature Units**: The unit of temperature of the analyte during the measurement (C, F, K). <br>
**Measurement Type**: The type of spectroscopy technique used to measure the peaks (Raman, IR, SERS).<br>

# Analyte Information

**Analyte Name**: The specific substance or chemical constituent that is being measured. This is the "target" of the measurement.<br>
**Type**: The high-level category describing the fundamental nature of the analyte as a physical or biological entity. (Polymer, Tissue, Environmental Sample, Biomolecule, etc.) (Qualitatively describes form, not chemistry)<br>
**Chemical Class**: The structural or functional chemical family to which the analyte belongs, based on IUPAC nomenclature. (Alcohol, Ketone, Ester, Alkaloid, etc.) (Describes chemistry)<br>
**Role**: The role that this analyte plays in the measurement (target, reference, internal_standard, matrix_component, impurity, dopant, substrate_modifier)<br>
**Chemical Identifier (SMILES)**: The plain text string that identifies the observed chemical compound by the SMILES (Simplified Molecular Input Line Entry System) standard. <br>
**Chemical Identifier (CAS Registry Number)**: The string of numbers, separated by hyphens that identify the observed chemical compound (as labeled in the CAS registry).<br>
**Solvent**: The name of the chemical compound used as a solvent in the experiment.<br>
**Sample Matrix**: A list of any other chemicals/substances in the sample that are not being targeted for observation (qualitative description).<br>
**Concentration**: The quantitative ratio of the amount of analyte relative to its sample. <br>
**Analyte Phase**: The phase of the analyte that it is observed in (solid crystal, powder, solution, vapor, etc.)<br>
**Solvent Phase**: The phase of the solvent that the analyte is observed in (solid, liquid, vapor, etc.)<br>
**Preparation Method**: The qualitative description of the procedures taken to prepare the spectroscopic measurement of the analyte.<br>

# Peak Row

**Peak Unit**: The unit of the reported shift (usually in cm^-1).<br>
**Peak High**: The upper bound of the range for the peak.<br>
**Peak Low**: The lower bound of the range for the peak.<br>
**Peak**: The single value of the peak (if only one is given).<br>
**Peak Width**: The width of the peak measured at half the peak height, where intensity is half of the maximum intensity of the peak. (FWHM "Full Width at Half Maximum")(usually in cm^-1)<br>
**Notes**: Additional details about the peak assignment from the literature. Include relative intensity strength as documented by the author of the literature (vs, s, m, w, vw, etc.) and polarization details (p, dp, etc.) with keys to specify if necessary. Also include any baseline correction if stated in literature.<br>

# Vibrational Mode (of structural environment)

**Mode Index**: The specific integer assigned to the vibration (4, 10, 3b).<br>
**Notation Convention**: The notation convention used to assign the mode index (Mulliken, Herzberg, Wilson Numbering, Wilson-Decius-Cross, or descriptive) <br>
**Assignment Label**: The shorthand identifier used to assign the vibrational mode in literature (v4, v10, etc.). This follows specific naming conventions (Mulliken, Herzberg, Wilson Numbering, Wilson-Decius-Cross, or descriptive). <br>
**Molecular Geometry**: The geometry of the structural environment (linear, bent, trigonal planar, trigonal pyramidal, tetrahedral, square planar, trigonal bipyramidal, octahedral, etc.)<br>
**Point Group**: The machine-readable plain text label for the point group of the structural environment (A1g, C2v, D3h, Td, etc.). ([getzenquery.com](https://www.getzenquery.com/tools/molecular-symmetry-analyzer/))<br>
**Mulliken Symmetry Label**: The symmetry label given to the vibrational mode using the Mulliken labeling convention. (A', a'', B, b, T, t, e, E, g-sub, u-sub).<br>
**Descriptive Symmetry Label**: The descriptive label of the vibrational symmetry (symmetric, antisymmetric, degenerate, etc.).<br>
**Descriptive Motion Label**: The descriptive label of the vibrational motion (stretch, bend, twist, etc.)<br>
**Mulliken Label**: The irreducible label of the vibrational symmetry in machine-readable, plain text, following the Mulliken notation convention (A1g, B2u, E_prime, A1g_sym, etc.)<br>
**Geometric Label**: The descriptive label of the vibrational geometry (in-plane, out-of-plane, radial, tangential, etc.).<br>
**Phase Label**: The descriptive label of the vibrational phase (in-phase, out-of-phase, etc.).<br>
**Moiety**: The distinct, identifiable bond in the molecule that is analyzed in the table (C—C, N=C=N, etc.) (Use SMILES format).<br>
**Vibrational Mode Description**: The raw text that is used to report the vibrational mode, if applicable (sym. str., C—C skel. def., etc.) (raw text. non-standardized).<br>
**Assignment Confidence**: The confidence assigned to a vibrational mode as stated in the literature if applicable. Provide proper context (0.7 out of a 1.0 scale / "certain" vs. "probable").<br>
**Functional Group**: The specific arrangement of atoms that behaves predictably in spectra (these are substructures that produce characteristic spectral peaks) (Raw qualitative data descriptions, be aware of controlled vocabulary).<br>
**Structural Environment**: The specific bond within the analyte that is being targeted for peak assignment. (Raw data, non-standardized)<br>
**Structural Position**: Raw descriptive text to describe where a group sits within a molecule. (terminal, internal, axial, endocyclic, exocyclic, backbone) <br>
**Raw Assignment**: The exact raw text used to report the vibrational mode assignment in the table (raw text. non-standardized). <br>

# SERS Substrate Information (A lot of this information can be found in the abstract section or the experimental section)

**Material**: The base material of the substrate used in the measurement (Ag, Au, Cu, Au–Ag alloy, Si + Au coating, etc.) (Follows naming conventions defined by IUPAC).<br>
**Morphology**: The described structure (and any supporting structure) of the substrate (raw text)("Ag nanograss SERS substrate", "silver nanorod array substrates", "Au NPs on a regularly arranged ZrO2 nanoporous structure", etc.) (can be expressed with abbreviations like ns, nr, nf, etc. which may require a key)<br>
**Fabrication Method**: The manufacturing process of the substrate as described in the literature. (Raw paragraph description from literature)(ISO/TS 80004-8 is a resource for nanomanufacturing vocabulary.)<br>
**Preparation Details**: The raw text description of how the substrate was prepared for the experiment (Ex: "BCP vapors were sprayed onto a CsI substrate maintained at approximately -190 C by boiling nitrogen.")<br>
**Active Area**: The area of the region of the substrate exposed to the analyte and laser (4mm^2, etc.) <br>
**Substrate Size Description**: The reported dimensions of the substrate used in the measurement (1 x 1cm, region diameter of 2mm, etc.) <br>
**Substrate Information**: A complete description of the substrate used in the SERS experiment. (Raw descriptive text extracted from literature. Ex: "In this study, a SERS-active substrate with Au NPs on a regularly arranged ZrO2 nanoporous structure was utilized to obtain the SERS spectrum of inpatient samples from COVID-19 patients.") <br>

# Preprocessing

**Preprocessing Information**: A description of the preprocessing methods used.<br>
<br><br>

# Google Sheet Link

[Peak Assignment Gold Dataset Spreadsheet](https://docs.google.com/spreadsheets/d/1O6uhUlTXZX6NvpCRCRlXQ1AWz2ZXYCEqO6_ix7QoW60/edit?usp=sharing)<br>
_Viewers have commenting privileges_
