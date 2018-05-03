Foreword
========

Purpose
-------
The purpose of this document is to introduce the requirements contained in OMG APP in detail , so that users can confirm the exact requirements of the product and developers can design codes according to the requirements.
The following descriptions will be combined with text descriptions, illustrations, and interface prototypes to describe OMG APP 's function, performance, user interface, external interfaces, and various responses to user operations.
Expected readers of this document are clients (Biologist, Project Manager, developer.


Background
--------
The software to be developed this time is a system for uploading gene expression files and quickly getting differently expressed genes.The project is mainly aimed at helping biological scientists deal with gene expression data more conveniently and quickly.
Through the software, users upload gene expression files on mobile devices. After some calculation and analysis, the software gives back to the user a processed form and scatter plot. Accepting the file, the software will return a table of differentially expressed genes and a scatter plot of these genes whose X-axis is control and Y-axis is treatment. If an invalid gene expression is given, the web application returns a page informing the user to provide the correct format.


Definition
----------

=====	===============================	==========================================================================================================================================================================
Rank	Name/Abbreviation				Definition
=====	===============================	==========================================================================================================================================================================
1		OMG								Oh my gene，the name of the product of this project
2		developer						Designers, programmers, and testers who develop all the products described in this document
3		gene expression files			A text file in txt format which contain some information
4		control sample					A cell sample prepared in its normal condition.
5		treatment sample				A cell sample treated by special chemicals, or in which some genes are altered.
6		differentially expressed genes	The genes which have significantly different expression levels between two samples.
7		up-regulation					A gene is said to be up-regulated if it has higher expression in treatment than in control.
8		down-regulation					A gene is said to be down-regulated if it has lower expression in treatment than in control.
9		T								Treatment 
10		C								Control
11		logFC 							Log fold change of gene expression. log_2 [T/C], where T is the gene expression level from a treatment sample, while C is the gene expression level from acontrol sample.

=====	===============================	==========================================================================================================================================================================



