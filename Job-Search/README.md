# Project 3: Job Search

Given a resume, the model of this project is able to find the best match among thousands of job postings. The program uses the Gensim natural language processing library to first convert the text of the job postings into word vectors and then compute the similarities between words within the vector space. A query document (resume) can also be tokenized and converted to vectors in order to compute its similarities. The query document is then checked against the corpus of job postings and the best matches are returned.
