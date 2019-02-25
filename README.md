# iMessage Analysis

This jupyter notebook reads Apple iMessage chat data and AddressBook data and
performs basic analytics and sentiment analysis. This has only been tested on
MacOS Mojave.

## Setup
This program runs as a Jupyter notebook installed via
[Anaconda](https://www.anaconda.com/) (or Miniconda).

1. Install Anaconda (or Miniconda) if it is not already installed.
2. Create and activate this project's environment by running .
`conda env create -f environment.yml; conda activate imessage-analysis`
3. Run `jupyter lab` (or `jupyter notebook` if the classic notebook interface
is preferred). This should open an interface in a browser window.
4. Copy `chat.db` from `~/Library/Messages/chat.db` and `AddressBook-v22.abcddb`
from `~/Library/Application Support/AddressBook/Sources` into the current
directory (select the sources folder with your primary contacts list).
5. Run the full notebook to produce statistics and figures.