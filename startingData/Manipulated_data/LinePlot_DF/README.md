
Pre-TreamentData.csv is a dataframe containing the colunm for "Pre-treatment NT-proBNP (pg/mL)" and "Group" columns
from the NewDF+BMI.csv file. In code it is identified as df1 initially.

Week4Data.csv is a dataframe containing the colunm for "Week 4 NT-proBNP (pg/mL)" and "Group" columns
from the NewDF+BMI.csv file. In code it is identified as df1 initially.

Week8Data.csv is a dataframe containing the colunm for "Week 8t NT-proBNP (pg/mL)" and "Group" columns
from the NewDF+BMI.csv file. In code it is identified as df1 initially.

Pre-TreamentData_TIMEPOINT.csv, Week4Data_TIMEPOINT.csv, and Week8Data_TIMEPOINT.csv are the same as the files listed above but with an
extra column title "Timepoint" that has the dataframe fie title inmputed in that column.
(i.e. if the file says Pre-TreamentData_TIMEPOINT.csv then there is a new timepoitn column which is filled with "Pre-Treament")

Merged_TimpointData.csv is the merging of the dataframes contained in Pre-TreamentData_TIMEPOINT.csv, Week4Data_TIMEPOINT.csv, and Week8Data_TIMEPOINT.csv

Merged_TimpointData_cleaned.csv is the cleaned version to which all NaN values are replaced with 0 integer.

Merged_TimpointData_Final.csv is the dataframe that was used to construct Figure4_NT-proBNP_conc_over_time_lineplot.pdf
