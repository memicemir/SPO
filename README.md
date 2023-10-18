# soil_profiling_for_DSSAT
Soil profile optimisation tool for DSSAT crop growth models.

1. The "SPO_v2.7z" file from "SPO_windows_runnable" has to be unzipped (with 7-zip). 

2. Unzipped "SPO_v2" directory copied to the DSSAT Tools directory "C:\DSSAT48\Tools". 

3. In folder "SPO_v2" ("C:\DSSAT48\Tools\SPO_v2")  ->SPO_v2.exe<- executed as Administrator.

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
1. Generic optimization approach of soil hydraulic parameters for site-specific model applications.
    Authors: Jonas Trenz, Emir Memic, William D. Batchelor, Simone Graeff-Honninger (under revision at Precision Agriculture Journal - Springer)
    This publication is very IMPORTANT and should be read before using SPO.
   
3. Evaluation of crop model-based marginal net return maximising nitrogen application rates on site-specific level in maize
    Authors: Emir Memic, Jonas Trenz, Sara Heshmati, Simone Graeff-Honninger (conference contribution to ECPA23 Bologna, Itally, 2023)
    DOI 10.3920/978-90-8686-947-3_98
