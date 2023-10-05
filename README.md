Supporting annotations for telicity of questions and target answers of the NExT-QA test set, as well as answers predicted by SeViLA. 

id: compound of question type + qid + video ID as appears in SeViLA's resulting file test_epochbest.csv;
video, frame_count, width, height: video ID and video parameters as appear in NExT-QA's test.csv;
question, answer, answer phrase, a0-a4: questions and answers as appear in NExT-QA's test.csv;
question structure, question word, conjuction, verb cluster, dependent clause: syntactic structire of the question and its parts; S for subject (noun phrase);
MCA, DCA: telicity labels of the main and dependent clauses of the question, where T - telic, A - atelic, U - undefined, I - irrelevant;
qid, type: question attributes as in NExT-QA's test.csv;
prediction: answer ID predicted by SeViLA as in test_epochbest.csv;
prediction phrase: predicted by SeViLA answer as word sequence; 
prediction aspect: telicity label for prediction phrase;
target: answer ID as gold standard from NExT-QA's test.csv;
target phrase: gold standard answer in words;
target aspect: telicity label for target phrase;
matching: labels Equal/Mismatch to compare prediction and target. 

More details in the article  "The Inherence of Telicity: Unveiling Temporal Reasoning in Video Question Answering". 
