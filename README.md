# A versioned database for leaf <sup>13</sup>C values from across the world

## How to use this package

#### Install the required packages

```r
install.packages("devtools")
devtools::install_github("ropenscilabs/datastorr")
devtools::install_github("wcornwell/leaf13C")
library(leaf13C)
```
That will install this library

```r
local_data<-leaf13C::get_data()
```
This should download the most recent version of the database on to your computer and load it into R.  

As the database moves forward the version number will change, but access to older versions will be possible through either this R package, the Github Releases page, or the Zenodo DOIs.

### Authors on this project

William K. Cornwell, Ian Wright, Joel Turner, Vincent Maire, Margaret Barbour, Lucas Cernusak, Todd Dawson,
David Ellsworth, Graham Farquhar, Howard Griffiths, Claudia Keitel, Alexander Knohl, Peter Reich,
Dave Williams, Radika Bhaskar, J.H.C. Cornelissen,
Anna Richards, Susanne Schmidt, Fernando Valladares, Christian Körner, Ernst-Detlef Schulze, Nina Buchmann, Louis Santiago

### Please cite

William K. Cornwell, Ian Wright, Joel Turner, Vincent Maire, Margaret Barbour, Lucas Cernusak, Todd Dawson,
David Ellsworth, Graham Farquhar, Howard Griffiths, Claudia Keitel, Alexander Knohl, Peter Reich,
Dave Williams, Radika Bhaskar, J.H.C. Cornelissen, Anna Richards, Susanne Schmidt, Fernando Valladares, Christian Körner, Ernst-Detlef Schulze, Nina Buchmann, Louis Santiago. A global dataset of leaf ∆13C values. DOI: 10.5281/zenodo.569501
