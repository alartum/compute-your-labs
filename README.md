# compute-your-labs
**CYL[Compute Your Labs]** is a program that allows you to automatize writing reports in physics. It takes array of data and a formula as input and counts the error of calculation. Then it writes the report into .pdf file and sends to my email (the last feature is just to add some fun). You can call it with --help key to receive some info.

##File info
Filename | Purpose
------------ | -------------
lab_info | The formula, data and data error should be put here. Just follow the example.
mail/header | Header of the e-mail to be sent.
mail/message | Text of the e-mail.
comments.txt | You can put comments here to be put into the report while computing the derivative.
derivatives.txt | Standard derivatives are stored here. You can add more if you want. 
format.tex | *LaTex* formatting is stored here. Change this file to get other style.
help.txt | *Must* be in the same directory as binary for correct work

##Required Packages
* *xdot* to view graphs 
* *ssmtp* to send e-mail
* *qpdfview* to view the output
* any Tex compiler (*TexMaker*  was used)
