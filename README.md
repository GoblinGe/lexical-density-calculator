# lexical-density-calculator
lexical density calculator
Lexical Density Calculator
Build 0.0.0.6
Ge Xiaoshuai
School of Foreign Languages, Shandong Agricultural University, 61 Daizong Street, Tai’an City, Shandong Province, China

Help file version 001 (June 12 2016)


INTRODUCTION
Lexical Density Calculator is a freeware for calculating lexical density. It runs on computers with Windows system. It is developed in aardio. 

GETTING STARTED
Simply double click the Lexical Density Calculator icon to launch the program.

CALCULATING LEXICAL DENSITY
Step1: Select the target files you want to analyze, you can do this in two ways:
a)Click on file->open file(s) menu option and select files you want to analyze.
b)Click on file->open dir menu option and select a directory you want to analyze.
Step2:Choose tag set scheme
settings->raw text menu option means the files you chose are untagged texts.
settings->Treetagger tagged text menu option means the files you chose are tagged 	with Treetagger POS tags. 
settings->Treebank tagged text menu option means the files you chose are tagged 	with	Treebank POS 	tags. 
settings->auto-detect menu option means you want the program to determine which 	tag set 	scheme 	is used for each file. This is the default selection. 
Step3: Decide whether numbers are counted as lexical words
settings->count numbers as lexical words menu option allows you to decide whether 	to count numbers as lexical words or not. By default, it is not checked.
Step4:Calculate lexical density for each file.
Click on the “Start” button to calculate lexical density.

SAVING THE RESULTS
file->save result to text menu option allows you to save the results to text files for future analysis.

NOTES:
The results are shown in the listview. The first line contains sums of each column except for lexical density, which is the average of the column.

We recommend using Treetagger tagged texts to conduct the analysis owing to its accuracy. You may use TagAnt to tag your texts.  Caution: The file path of TagAnt.exe should not contain any Chinese characters if you run it on a Chinese version of Windows system. 

Lexical density of a raw text is calculated by the following algorithm: 
lexical density = (1 - (function word number / total word number) )*100

LEGAL MATTER 
Lexical Density Calculator can be used freely for individual use for non-profit research purposes, and freely distributed on the condition that this read me file is attached in an unaltered state. If the software is planned to be used in a group environment, you are required to inform me how the software is to be used, and I will then determine if you can have permission to use it. The software comes on an 'as is' basis, and the author will accept no liability for any damage that may result from using the software.
