# GUI-Generalised-Blockmodeling

This repository contains a GUI built in R Shiny to help users access specific functionalities of the R language for statistical computing and some of its packages for blockmodeling and, secondarily, network analysis. The app focuses mainly on the packages ``blockmodeling`` by Aleš Žiberna and
``network`` by Carter Butts.

The app’s many option and east of use make blockmodeling and basic network analysis in R easier to execute and understand than via command line. In fact, the GUI requires no coding experience, allowing researchers and laymen to access visualisations and information about blockmodeling in a simple way. The breadth of network analyses than can be executed is arguably not too extended, but the focus when it comes to computation is here on blockmodeling. Thus making, the app could find an apt use in a graduate class in quantitative methods in social science as well.

The app supports different types of inputs:
|*File type*       |*File type*|*Extension*      |*R function*      |*Package*          |
|:-----------------|:----------|:----------------|:-----------------|:------------------|
|Adjacency matrix  |plain/text |.txt; .csv; .tab |``read.delim()``  |``base``           |
|Edge list         |plain/text |.txt; .csv; .tab |``read.delim()``  |``base``           |
|Incidence matrix  |plain/text |.txt; .csv; .tab |``read.delim()``  |``base``           |
|Pajek matrix      |Pajek      |.mat             |``loadmatrix()``  |``blockmodelling`` |
|Pajek network     |Pajek      |.net             |``loadmatrix()``  |``blockmodelling`` |
