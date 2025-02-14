# soil_profiling_for_DSSAT
IMPORTANT: Publication list at the end of this Readme file.

Soil profile optimisation tool for DSSAT crop growth models (Tested with DSSAT v 4.8.5).

1. The "SPO.zip" file has to be unzipped. 

2. Unzipped "SPO" directory copied to the DSSAT Tools directory "C:\DSSAT48\Tools". 

3. In folder "SPO" ("C:\DSSAT48\Tools\SPO") "SPO_v3.0.exe" executed as Administrator.

4. More detailed instructions can be found in user guidelines v 3.0. This user guideline is not completely finished yet, more details are available in user guidelines v 2.0.


<pre>
├── C:/DSSAT48
│   ├── Genotype
│   ├── Pest
│   ├── Maize
│   ├── Wheat
│   ├── Soil
│   ├── ...	
│   └── Tools
│       ├── GBuild
│       ├── XBuild
│       ├── ...
│       └── SPO_v2
│           ├── ...
│           └── SPO_v2.exe	

After executing "SPO_v2.exe" a working directory "Soil_Profiling_Workspace" is created in "Tools" directory where optimization is conducted and optimization output files saved:

├── C:/DSSAT48
│   ├── Genotype
│   ├── Pest
│   ├── Maize
│   ├── Wheat
│   ├── Soil
│   └── Tools	
│      ├── ...	
│      └── Soil_Profiling_Workspace
│          ├── FiguresSaved
│          ├── SOIL.SOL
│          ├── SOIL_backup.SOL
│          ├── ...
│          ├── *_boxPlot.png	
│          ├── SoilWat.OUT	
│          └── PlantGro.OUT
</pre>

SPO related publications:
1. Generic optimization approach of soil hydraulic parameters for site-specific model applications
    Authors: Jonas Trenz, Emir Memic, William D. Batchlor, Simone Graeff-Hönninger
    Precision Agriculture Journal - Springer 2023 (DOI: 10.1007/s11119-023-10087-9)
   
3. Evaluation of crop model-based marginal net return maximizing nitrogen application rates on site-specific level in maize
    Authors: Memic E., Trenz J., Heshmati S., Graeff H.
    Precision Agriculture Journal – Springer 2024 (DOI: 10.1007/s11119-024-10126-z)
