# soil_profiling_for_DSSAT
Soil profile optimisation tool for DSSAT crop growth models.

1. The "SPO_v1.7z" file from "SPO_windows_runnable" has to be unzipped (with 7-zip). 

2. Unzipped "SPO_v1" directory copied to the DSSAT Tools directory "C:\DSSAT48\Tools".

3. In folder "SPO_v1" ("C:\DSSAT48\Tools\SPO_v1")  ->SPO_v1.exe<- executed as Administrator.

4. More detailed instructions can be found in user guidelines!


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
│       └── SPO_v1
│           ├── ...
│           └── SPO_v1.exe	

After executing "SPO_v1.exe" a working directory "Soil_Profiling_Workspace" is created where optimization is conducted and optimization output files saved:

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
