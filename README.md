🔬 JKQC — Jammy Key for Quantum Chemistry

JKQC is a lightweight toolkit that helps automate common tasks in
computational and quantum chemistry.
It provides convenient utilities for reading, filtering, analysing, and
processing output files from ORCA, Gaussian (G16), xTB, MRCC, CREST, and
related tools.

------------------------------------------------------------------------

📦 Installation

From PyPI

    pip install JKQC

From source

    git clone https://github.com/kubeckaj/JKQC.git
    cd JKQC

    python -m venv .venv
    source .venv/bin/activate
    pip install -e .

------------------------------------------------------------------------

🚀 Quick Usage

Command line

    jkqc --help

In Python

    from jkqc.read_files import read_files
    from jkqc.arguments import arguments

    args = arguments()
    data = read_files(args.input_folder)

------------------------------------------------------------------------

✨ Features

-   Readers for ORCA, G16, xTB, MRCC, CREST output files
-   Filtering, sorting, grouping, and clustering tools
-   Structure alignment and conformer selection
-   Thermodynamics and post-processing utilities
-   Functions for batch and high-throughput QC workflows

------------------------------------------------------------------------

🧭 Requirements

-   Python 3.9–3.10
-   NumPy, SciPy, Pandas, ASE, LapJV
-   Optional: RDKit

------------------------------------------------------------------------

📄 License

Released under the GPL-3.0 license.

------------------------------------------------------------------------

🤝 Contributing

Contributions, feature suggestions, and bug reports are welcome—please
open an issue or a pull request on GitHub.
