## Test environments
* local R installation, R 4.5.1
* GitHub Actions (ubuntu-latest):   release, devel, oldrel
* GitHub Actions (windows-latest): release
* Github Actions (macOS-latest): release

## R CMD check results
0 errors | 0 warnings | 0 notes

## Comments
This submission is a patch update correcting a CRAN NOTE related to the explicit specification of the C++ standard (CXX11).
The C++ standard specification has been removed, allowing the default C++17 standard to be used, as recommended by CRAN.
