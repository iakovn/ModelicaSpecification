<img src="https://github.com/modelica/MA-Logos/raw/master/HighRes/Modelica_Language.svg?sanitize=true" width="250px"/>

# ModelicaSpecification
This repository contains the Modelica Language Specification, hosted at https://github.com/modelica/ModelicaSpecification.
Development is organized within the [Modelica Association Project Language (MAP-Lang)](https://modelica.org/projects) according to the [project rules](https://github.com/modelica/MAP-Lang_ProjectRules/blob/main/MAP-Lang-ProjectRules.md).

## Description

Modelica® is a language for modeling of cyber-physical systems, supporting acausal connection of components governed by mathematical equations to facilitate modeling from first principles.
It provides object-oriented constructs that facilitate reuse of models, and can be used conveniently for modeling complex systems containing, e.g., mechanical, electrical, electronic, magnetic, hydraulic, thermal, control, electric power or process-oriented subcomponents.

## Releases

Version | Link                                                              | Published |
------- | ----------------------------------------------------------------- | --------|
3.6-dev | [Master branch](https://github.com/modelica/ModelicaSpecification/tree/master) [HTML](https://specification.modelica.org/master/) [PDF](https://specification.modelica.org/master/MLS.pdf)| not yet |
3.5 | [3.5 branch](https://github.com/modelica/ModelicaSpecification/tree/maint/3.5) [HTML](https://specification.modelica.org/maint/3.5/MLS.html) [PDF](https://specification.modelica.org/maint/3.5/MLS.pdf)| 2021 |
3.4     | [3.4 branch](https://github.com/modelica/ModelicaSpecification/tree/maint/3.4) [HTML](https://specification.modelica.org/maint/3.4/MLS.html) [PDF](https://modelica.org/documents/ModelicaSpec34.pdf)          | 2017    |
3.3rev1 | [PDF](https://modelica.org/documents/ModelicaSpec33Revision1.pdf) | 2014    |
3.2rev2 | [PDF](https://modelica.org/documents/ModelicaSpec32Revision2.pdf) | 2013    |
3.2rev1 | [PDF](https://modelica.org/documents/ModelicaSpec32Revision1.pdf) | 2012    |
3.3     | [PDF](https://modelica.org/documents/ModelicaSpec33.pdf)          | 2012    |
3.2     | [PDF](https://modelica.org/documents/ModelicaSpec32.pdf)          | 2010    |
3.1     | [PDF](https://modelica.org/documents/ModelicaSpec31.pdf)          | 2009    |
3.0     | [PDF](https://modelica.org/documents/ModelicaSpec30.pdf)          | 2007    |
2.2     | [PDF](https://modelica.org/documents/ModelicaSpec22.pdf)          | 2005    |
2.1     | [PDF](https://modelica.org/documents/ModelicaSpec21.pdf)          | 2004    |
2.0     | [PDF](https://modelica.org/documents/ModelicaSpec20.pdf)          | 2002    |
1.4     | [PDF](https://modelica.org/documents/ModelicaSpec14.pdf)          | 2000    |
1.3     | [PDF](https://modelica.org/documents/ModelicaSpec13norev.pdf)     | 1999    |
1.2     | [PDF](https://modelica.org/documents/modelicaspec12norev.pdf)     | 1999    |
1.1     | [PDF](https://modelica.org/documents/ModelicaSpec11.pdf)          | 1998    |
1.0     | [PDF](https://modelica.org/documents/Modelica1.pdf)               | 1997    |

More Info on released versions: https://www.modelica.org/documents

## Contribution
1. If you find an error and are not certain that you can correct it, first check that it is not already reported and then open an [issue](https://github.com/modelica/ModelicaSpecification/issues) describing it in detail - focusing on why it should be changed.
2. If you are confident that you can correct the issue, fork this repository and create a pull-request and in the pull-request explain the issue and the correction; you will also have to sign a CLA.
3. Significant extensions are handled as Modelica Change Proposals (MCPs). This can start as a simple description of the proposed extension. It will then be worked on to have a rationale explaining how the change help users, and demonstrating that it can be implemented efficiently; and finally a pull-request with the changes.

For more details, see the [Development Process](https://github.com/modelica/ModelicaSpecification/blob/master/RationaleMCP/DevelopmentProcess.md).
A list of MCPs can be found here: [RationaleMCP](https://github.com/modelica/ModelicaSpecification/tree/master/RationaleMCP).

CLA: Contributor's license agreement. (Details to follow.)

How to edit and generate final documents
* Read the [style guide](styleguide.md).
* For online editing you can use www.overleaf.com (details to follow)
* The pdf-documents are generated with pdflatex, which is part of most LaTeX installations, we used http://miktex.org/download
* The HTML-documents are generated with LaTeXML. That is more complicated to install - and can optionally be skipped:
1. First you need perl, we used http://strawberryperl.com/
2. And then the official LaTeXML package (0.8.5 or later): http://dlmf.nist.gov/LaTeXML/get.html#SS4.SSS0.Px1 or https://github.com/brucemiller/LaTeXML
3. The exact commands are in the Makefile

It is also possible to get a preview in the pull request.
There will be a link to the [status check](https://test.openmodelica.org/jenkins/job/ModelicaAssociation/job/ModelicaSpecification/view/change-requests/), which checks that the documents can be generated and gives you an option to download them.
