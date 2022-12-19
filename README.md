
--- # Annotation for Dataset

Title: 'Data for: Chimney-like intense pelagic upwelling in the center of basin-scale cyclonic gyres in large Lake Geneva'

Associated Publication: 'S. M. Hamze-Ziabari, U. Lemmin, M. Foroughan, R. S. Reiss, and D. A. Barry (2022). "Chimney-like intense pelagic upwelling in the center of basin-scale cyclonic gyres in large Lake Geneva.'

Description: ' The data include measurements from Acoustic Doppler Current Profilers (ADCP) and the Conductivity Temperature Depth (CTD) instruments along with the predefined transects described in the main text.
The three-dimensional model used in this study is based on the MIT General Circulation Model (MITgcm, http://mitgcm.org/, https://doi.org/10.1029/96JC02775). The model confguration and codes are included. 



Files: 
  - name: Field_month_year_Horizontal_Velocity_T.xlsx
    format: Microsoft Excel Worksheet (.xlsx)
    variables: 
      - u [mm/s]
      - v [mm/s]
      - T [°C]
    depth interval: variable (1m - 60m)

  - Folder name: Input 
    Files: 
      - data
      - data.mnc
      - data.pkg
      - data.cal
      - data.EXF
      - data.KPP
      - data.diagnostics
      - eedata

  - Folder name: Codes
    Files: 
      - CAL_OPTIONS
      - CPP_EEOPTIONS
      - CPP_OPTIONS
      - DIAG_OPTIONS
      - DIAGNOSTICS_SIZE
      - EXF_OPTIONS
      - GAD_OPTIONS
      - OBCS_OPTIONS
      - packages.conf
      - SIZE
      - swfrac.F

    notes: 'The descrptions of input and code files can be found in https://mitgcm.readthedocs.io/en/latest/'


--- # End of README
