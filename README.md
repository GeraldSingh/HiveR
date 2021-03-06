## How to install HiveR

### To install from Github using R:

````r
install.packages("devtools")
library("devtools")
install_github(repo = "HiveR", username = "bryanhanson", ref = "master")
library("HiveR")
````
If you use `ref = "some_other_branch"` you can get other branches that might be available.  They may or may not pass CRAN checks and thus may not install automatically using the method above.  Check the NEWS file to see what's up.

### From CRAN using R:

````r
chooseCRANmirror() # choose a CRAN mirror
install.packages("HiveR")	
library("HiveR")
````

### To get to the Vignette:

````r
vignette("HiveR")
````
### License Information

HiveR is distributed under the GPL-3 license, as stated in the DESCRIPTION file.  For more info, see the [GPL site.](https://gnu.org/licenses/gpl.html)

Questions?  hanson@depauw.edu