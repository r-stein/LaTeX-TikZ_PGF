This is a temporary fork of the default LaTeX syntax from https://github.com/sublimehq/Packages .

The purpose of this repository is to enable users to test the changes before creating a PR on the default repository. Afterwards this repository will be deleted.

**Installation (using Package Control)**

1. Press C-shift-p and select *Package Control: Add Repository*
2. Paste `https://github.com/r-stein/LaTeX-TikZ_PGF`
3. As usual: Press C-shift-p and select *Package Control: Install Package* and then select `LaTeX-TikZ_PGF`

Afterwards you can open a LaTeX/TikZ file and select *Tools > Syntax > Open all with current extensions as... > LaTeX (TikZ/PGF)*.

**Cleanup**
If you are done with testing and want cleanup:

1. open *Preferences > Browse Packages* and open the folder *User* and delete the file `LaTeX (TikZ-PGF).sublime-settings` if it exists.
2. Press C-shift-p and write *Package Control: Remove Package* and remove the package and *Package Control: Remove Repository* and remove the repository.



