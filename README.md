Introduction
============

These are mass spectral libraries of commonly occuring compounds found in environmental samples suitable for use in AMDIS or (soon) Aston.  There are two libraries included corresponding to different polarity fractions derivitized differently.

The first library is trimethylsilyl (TMS) derivatives of compounds that can be eluted from a silica gel column using solvents with a composition between 85% hexane and 15% ethyl acetate and 75% hexane and 25% ethyl acetate. The second libary is methanol transesterified-derivatives of fatty acids (i.e. FAMEs) and other related compounds that were eluted from a silica gel column with solvent compositions of 75% ethyl acetate and 25% methanol to 100% methanol.

The MSL files contain all spectra found in environmental samples and current best identifications obtained from literature and informal resources. They are released as is and may contain errors. The CSL files correspond to the MSL files (e.g. RKHEX -> FAME and TLEPYR -> TMS) and contain a strict subset of commonly-found compounds with known spectra and retention indices (from the NIST Chemistry WebBook) that were used by AMDIS to assign retention indices to other compounds. All retention indices are from runs on DB-5 GC columns.


Usage
=====

To use in AMDIS, click the "Analyze" menu and choose "Settings...". Under the "Libr." tab, select "Target Compounds Library", "Select New", and then choose a MSL file. Repeat with "Calibration/Standards Library", "Select New", and the corresponding CSL file. Click the Save button to close the Window, then click the "Analyze" menu and "Analyze GC/MS Data...". Choose "RI Calibration/Performance" from the "Type of analysis" dropdown menu and then the "Run" button to generate retention index calibration data for the current file; this data may be used with other runs with similar retention indices, but regenerate a calibration if retention times have dramatically changed. After generating a calibration, peaks can be identified with the "Type of analysis" -> "Use Retention Index Data" option. See AMDIS documentation for more details.


Online Mass Spectral Resources
==============================

http://webbook.nist.gov/chemistry/

http://lipidbank.jp/

http://lipidlibrary.aocs.org/ms/arch_me/index.htm
