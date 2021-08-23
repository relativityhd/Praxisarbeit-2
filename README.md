# DHBW Latex Template

Updated Version of the DHBW Latex Template

fork from <https://git.dhbw-stuttgart.de/wi-lab/latex-template>

## Installation (only necessary if using VSCode)

The basic modules are:

1. [Install LaTex](https://www.tug.org/texlive/)
2. [Install ChkTex](https://www.nongnu.org/chktex/)
3. [Install latexindent.pl](https://latexindentpl.readthedocs.io/en/latest/sec-introduction.html)
4. Install recommended extensions

However, for different OS installation may become difficult...

### MacOS

1. Install MacTex

   ```sh
   brew install mactex-no-gui
   ```

2. [Install ChkTex](http://download.savannah.gnu.org/releases/chktex/chktex-1.7.6.tar.gz)
   Download and unzip file

   ```sh
   sh ~/Downloads/chktex-1.7.6/install-sh
   ```

3. Install sup-dependencies for `latexindent.pl`, the script automatically installs with MacTex

   ```sh
   brew install perl
   brew install cpanm

   cpanm YAML::Tiny
   cpanm File::HomeDir
   cpanm Unicode::GCString
   ```

## Usage (VSCode)

This project automatically builds on save to `/out/`. You can find the resulting PDF under `/out/main.pdf`. Please make usage of the Latex-Workshop extension via the `TEX icon on the activity bar (left side). You can manually build the project there, clear junk files and a lot more.

## Usage (Overleaf)

TODO: make Overleaf support
