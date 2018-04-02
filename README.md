Performance Engineering Lab, UCD
==========================================================

This repository contains tools developed by the research activities of the **Performance Engineering Laboratory** at the [School of Computer Science (University College Dublin)](http://www.csi.ucd.ie).

Tools
----------------------
This repository contains the following tools:

### 1. [LOUPE] (https://github.com/ucd-pel/Tools/tree/master/Loupe) ###

LOUPE is an automated system, developed in Java Standard Edition, that addresses the common usage limitations of source code plagiarism detection tools. LOUPE shields the users from the complexity and burden of properly configure the tools by providing a unified approach to run several different tools  simultaneously  for  multiple  pieces  of  work (including historical data). The system automatically  gathers the tools’outputs, consolidates their relevant information (considering users’ preferences), and  presents a useful data visualization that includes a comparative view of the tools. 

More details about the tool and how it has been used in experiments of plagiarism detection can be found at the following papers:
#### 1.1 A Unified Approach to Automate the Usage of Plagiarism Detection Tools in Programming Courses 
(http://ieeexplore.ieee.org/abstract/document/8085456/)
Please cite as: Portillo-Dominguez, A. O., Ayala-Rivera, V., Murphy, E., & Murphy, J. (2017, August). A unified approach to automate the usage of plagiarism detection tools in programming courses. In 12th International Conference on Computer Science and Education (ICCSE), 2017 (pp. 18-23).

### 2. [THANOS] (https://github.com/ucd-pel/Tools/tree/master/Thanos) ###

THANOS is an automated tool, developed in Java Standard Edition, that allows the execution of a set of widely-used anonymization, pseudonymization, and de-identification  mechanisms that allow processing the data without compromising the confidentiality of individuals, while also trying to retain the utility of the data for a variety of analytical tasks. The selected mechanisms consist in transforming personal data (manipulating or removing attributes) such that it cannot be linked to data subjects (i.e., break the linkage with real world identities).

