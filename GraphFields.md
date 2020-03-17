## COVID19 Contact Tracing Data Structure

Structure of the data is broken into 3 major components
1. The case - which is to indentify the patient or suspected carrier with symptomatic indication or quanrantined with following  data points
   1. CaseID
   2. Symptomatic [Boolean]
   3. Symptoms [Array<String>]
   4. Date of First Symptom [Datetime]
   5. Current Status [String]
   6. Age [Int]
   7. Sex [String]
2. Location:
   1. ID
   2. Name [String]
   3. Designated cluster [Boolean]
3. Contact Duration
   1. Time Start [Datetime]
   2. Time End [Datetime]



















Inspired By: https://nebula-graph.io/en/posts/detect-corona-virus-spreading-with-graph-database/