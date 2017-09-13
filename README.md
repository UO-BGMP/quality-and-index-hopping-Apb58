# Qualiy and Index Swapping:

*File Breakdown:*

1. _Qual_Index_Swp.py_: Python script to filter reads by average quality score and sort reads by Index pairs
2. _Qual_Index_run.srun_: BASH script to run 'Qual_Index_Swp.py" program, including passed in arguments
3. _Qual_Mean_Calc.py_: Python script to calculate mean quality scores by base pair and read (stats)
4. _Qual_Calc_run.srun_: BASH script to run "Qual_Mean_Calc.py"
5. _Qual_Index_out.rmd_: R markdown file with code to generate figures and question answers. *NOTE*, the associated PDF and HTML file should be used for grading; this is just to visualize the R code if you'd like.

6. _Qual_Index_out.pdf/Qual_Index_out.html_: Knit output of RMD, contianing figures -- *Please download PDF* to view figures correctly (git hub seems to cut off some of the graphs!)
7. _Formatted_sorted_indexes.txt_: Text file containing the Read counts by index pair (seen in pdf/html file) that can be used for more friendly viewing. 
