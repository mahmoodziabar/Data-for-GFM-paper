# Data-for-GMD-paper
--- # Annotation for Dataset

Title: 'Data for: Basin-scale gyres and mesoscale eddies in large lakes: A novel procedure for their detection and characterization, assessed in Lake Geneva'

Associated Publication: 'S. M. Hamze-Ziabari, U. Lemmin, M. Foroughan, and D. A. Barry (2022). "Basin-scale gyres and mesoscale eddies in large lakes: A novel procedure for their detection and characterization, assessed in Lake Geneva". Submitted to Geoscientific Model Development.'

Description: ' The data include measurements from Acoustic Doppler Current Profilers (ADCP) along with the predefined transects described in the main text.
The three-dimensional model used in this study is based on the MIT General Circulation Model (MITgcm, http://mitgcm.org/, https://doi.org/10.1029/96JC02775). The model confguration and codes are included. 



Files: 
  - name: Field_month_year_Horizontal_Velocity_T.xlsx
    format: Microsoft Excel Worksheet (.xlsx)
    variables: 
      - u [mm/s]
      - v [mm/s]
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
