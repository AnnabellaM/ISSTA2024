# ISSTA2024
Artifact for An Extensive Empirical Study of Nondeterministic Behavior in Static Analysis Tools.

This repository contains data for 'An Extensive Empirical Study of Nondeterministic Behavior in Static Analysis Tools' which serves as the conclusion made in the two research questions RQ1 and RQ2, alongside the data generated during the study.
Inside the data directory, there are two sub-directories (rq1 and rq2):
In rq1/ there are:
RQ1_FINAL_RESULTS.csv - Contains 79 distinct results from 6 repositories (SOOT, WALA, DOOP, FlowDroid, DroidSafe, Infer) that fix or report nondeterminism, each result is an issue with ID, tool name, linked issues/commits, two categorizations.
raw_data.zip - Contains the raw commits and issues extracted from 10 repositories (SOOT, DOOP, WALA, FlowDroid, DroidSafe, AmanDroid, TAJS, Code2Flow, PyCG, Infer).
key_words_results.zip - Contains the results extracted by each keyword (concurrency, concurrent, determinism, deterministic, flakiness, flaky) from the raw data.
In rq2/ there are two sub-directories (rq2.1 and rq2.3):
In rq2.1/ there are:
RQ2_AGGREGATE_DATA.csv - Contains the result distributions of each combination of target program, configuration hash, and tool as well as the calculated consistency score.
In rq2.3/ there are:
11 PDF files of each reported issues discussed in RQ2.3, including 3 FLowDorid issues, 2 SOOT issues, 1 issue for DOOP, Infer, Amandroid, PyCG and Code2Flow each. Additionally, there is an email from a FlowDroid developer, serving as a response to the FlowDroid-reported-issue-3. We have tried to anonymize all identifiable information such as IDs, names, or links to maintain confidentiality.

