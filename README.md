\# DBT lab



This project generates a random dataset consisting of users and orders. Scripts are written in Python and the project uses \[uv](https://docs.astral.sh/uv/).



\## Usage



```bash

uv run dataset\_users.py -h

\#> usage: User generator \[-h] \[-c COUNT] \[-o {csv,json,jsonline}]



\#> options:

\#>   -h, --help            show this help message and exit

\#>   -c, --count COUNT     Number of users to generate.

\#>   -o, --output {csv,json,jsonline}

\#>                         Output format.

