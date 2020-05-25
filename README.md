# nctiles-testcases

[![DOI](https://zenodo.org/badge/221528479.svg)](https://zenodo.org/badge/latestdoi/221528479) 

Test cases for the `nctiles` pipelines in [NCTiles.jl](https://github.com/gaelforget/NCTiles.jl) and [gcmfaces/nctiles](https://github.com/MITgcm/gcmfaces) + sample output from the `gcmfaces` original pipeline (in `diags_nctiles/`).


- `README` global attribute example
- `available_diagnostics.log` example
- `grid_float32/` model grid example (binary, llc90 grid)
- `diags/` model output example (binary, llc90 grid)
- `diags_interp/` regular grid example (binary, 720x360)
- `diags_nctiles/` sample output from `gcmfaces/nctiles`
	- `FeT.0062.nc` (netcdf, one tile; `29-May-2018` vintage)
	- `MXLDEPTH.0011.nc` (netcdf, one tile; `01-Apr-2016` vintage)
