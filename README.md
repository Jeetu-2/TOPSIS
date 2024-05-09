# TOPSIS


# Choosing models
I selected following pre-Trained models from hugging face:
1. "facebook/bart-base",
2. "allenai/longformer-base-4096",
3. "google/electra-small-discriminator",
4. "microsoft/mpnet-base",
5. "squeezebert/squeezebert-uncased",
6. "deepset/sentence_bert",
7. "vinai/phobert-base",
8. "bert-base-uncased",
9. "roberta-base",
10. "distilbert-base-uncased",
11. "sentence-transformers/paraphrase-MiniLM-L6-v2"

    
# Choosing Parameters
I selected following parameters for text-sentence similarity:
1. Cosine Similarity
2. Euclidean Distance
3. Manhattan Distance
4. Minkowski Distance
5. Correlation Coefficient

   
# Evaluating Model and Normalization
1. Evaluate models and create a DataFrame with parameter values for each model.
2. Normalize parameter values to a common scale.
3. Assume equal weights for simplicity.
4. Multiply normalized parameter values with criteria weights.
5. Identify the maximum and minimum values for each criterion.
6. Calculate the distance of each model from positive and negative ideal solutions.

   
# Ranking on the basis of TOPSIS score
1. Calculate the TOPSIS scores for each model.
2. Rank models based on their TOPSIS scores in descending order.
3. Save the ranked results to a CSV file named "Results.csv".

   
# I have selected "sentence-transformers/paraphrase-MiniLM-L6-v2" as best pre-trained model because of highest TOPSIS-Score (1.78760890209212)
