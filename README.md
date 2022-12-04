# Exploratory-Data-Analysis-with-Spark-RDD
Performing a simple EDA on the 2021 Clinical Trial data from clinicaltrial.gov to gain some insight on the data.
The data:
We will be using clinical trial datasets in this work and combining the information with a list of pharmaceutical
companies and condition hierarchy information.

Problem statements:
As a data analyst/data scientist whose client wishes to gain further insight into clinical trials. I have been tasked with answering these questions, using visualisations where that would support my conclusions.
1. The number of distinct studies in the dataset.
2. List all the types (as contained in the Type column) of studies in the dataset along with
the frequencies of each type. These should be ordered from most frequent to least frequent.
3. The top 5 conditions (from Conditions) with their frequencies.
4. Each condition can be mapped to one or more hierarchy codes. The client wishes to know the 5
most frequent roots (i.e., the sequence of letters and numbers before the first full stop) after this is
done.
5. Find the 10 most common sponsors that are not pharmaceutical companies, along with the number
of clinical trials they have sponsored. For a basic implementation, we assume that the parent company column contains all possible pharmaceutical companies.
6. Plot the number of completed studies each month in a given year {for the submission dataset, the year
is 2021.
