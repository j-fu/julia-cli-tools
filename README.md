JULIA CLI TOOLS
===============
Some useful command line interface tools for Julia

They need the following packages in the global environment:

- ArgParse
- Pluto
- NetworkOptions
- JuliaFormatter
  
## pluto

Script to start or manage pluto notebooks

Examples:

`pluto notebook.jl` starts notebook in the browser

`pluto --update-all` updates packages to the respective newest version and the julia entry to the version of julia calling 

For more info see `pluto --help`.

## jlformat
Script to format Julia code using [JuliaFormatter.jl](https://domluna.github.io/JuliaFormatter.jl/stable/)

Examples:

`jlformat *.jl` formats files on given on the command line

`jlformat src` formats files in the directory `src`.

JuliaFormatter looks for [.JuliaFormatter.toml](https://domluna.github.io/JuliaFormatter.jl/stable/config/) in the location of the file being formatted, and searching up the file tree until a config file is (or isn't) found.



