Algorithm 
Step-by-Step Procedure 
1. 
2. 
3. 
4. 
5. 
6. 
Input Text  
o Accept user input (sentence or word).  
Preprocessing  
o Convert text to lowercase  
o Remove punctuation  
o Tokenize words  
Error Detection  
o Compare each word with a dictionary  
o Identify misspelled words  
Candidate Generation  
o Generate possible corrections using:  
▪ Insertions  
▪ Deletions  
▪ Substitutions  
▪ Transpositions  
Probability Calculation  
o Use word frequency to rank suggestions  
o Choose the most probable word  
Correction Output  
o Replace incorrect words  
o Display corrected sentence  
Logic / Method Used 
• Edit Distance (Levenshtein Distance)  
• Probability-based correction (word frequency)  
• Dictionary lookup  
• NLP techniques  
Model / Technique Applied 
• Rule-based approach  
• Statistical NLP model  
• Optional: N-gram language model  
Process Flow 
User Input → Preprocessing → Error Detection → Candidate Generation  
→ Probability Selection → Corrected Output 
Datasets 
Dataset Description 
The dataset consists of a large collection of correctly spelled words along with their frequency of occurrence. 
Types of Dataset Used 
1. 
2. 
Dictionary Dataset  
o List of valid English words  
o Example: word list file (words.txt)  
Corpus Dataset  
o Large text data (books, articles)  
o Used to calculate word frequency  
Example Dataset 
the 50000 
hello 3000 
world 25000 
python 2000 
project 150
