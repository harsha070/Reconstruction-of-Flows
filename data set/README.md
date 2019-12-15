## Dataset

We are sharing the dataset for further development and research. The dataset has *ANSYS* simulation values of *u*, *v*, *pressure* for R<sub>e</sub> = 10 to R<sub>e</sub> = 1000 for lid driven cavity across 8x8, 16x16, 32x32 and 64x64 mesh resolutions.

They are stored as follows

`{mesh size}/{mesh size}\__{parameter}\__{lid velocity}.txt`

where 
`mesh size` is {8, 16, 32, 64}  
`parameter` is {u, v, pressure}  
`lid velocity` is {0.01, 0.02, 0.03....1.00}

Each `.txt` file has a `n` lines with `n` values in each line. 
