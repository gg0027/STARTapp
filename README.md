# START App 

The START App: 
A Web-Based RNAseq Analysis 
and Visualization Resource

The app is hosted on Shinyapps.io here:
<https://kcvi.shinyapps.io/START/>

To run this app locally on your machine, download R or RStudio and run the commands:
```

install.packages(c("reshape2","ggplot2","ggthemes","gplots","ggvis","dplyr","tidyr","DT",
                   "RColorBrewer","pheatmap","shinyBS","plotly"))
## try http:// if https:// URLs are not supported
source("https://bioconductor.org/biocLite.R")
biocLite(c("limma","edgeR"))
shiny::runGitHub("STARTapp", "jminnier")

```

Jonathan Nelson, Jiri Sklenar, Anthony Barnes, Jessica Minnier.
*The Knight Cardiovascular Institute, Oregon Health & Science University, Portland, OR 97239-3098, USA.*

# Instructions

Instructions can be found here: <https://github.com/jminnier/STARTapp/blob/master/instructions/Instructions.pdf> 


# Licensing

This shiny code is licensed under the GPLv3. Please see the file LICENSE.txt for
information.

    START Shiny App for analysis and visualization of transcriptome data.
    Copyright (C) 2014-2016  Jessica Minnier

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

    You may contact the author of this code, Jessica Minnier, at <minnier@ohsu.edu>
