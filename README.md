# Resume Matching

## Goal

In this project, I wanted to create a model that would be capable of, if given a resume, matching the resume to the closest available job at the company. For example, if someone was a recent graduate, they would ideally be matched and suggested jobs that were more entry level. Another example is, if someone has experience in Python and Azure, they would be recommended jobs that work with both ; however, if they only had experience with R and AWS, they would not be recommended the same job.

## Data
The data was obtained by webscraping Linkedin and other job posting websites in order to get job descriptions, education preferences, information about the company, etc.

## Methods Used

Doc 2 Vec was used in order to summarize the documents as it performed the best when compared to other methods such as RNNs or LSTMs. After creating vectors for each document, we will be able to compare a resume or bio to a matching job description.
