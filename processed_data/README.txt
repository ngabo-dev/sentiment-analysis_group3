Artifacts:
- processed_dataset.csv: cleaned texts (proc) and labels
- X_*_tfidf.npz: TF-IDF sparse features (fit on train)
- tfidf_vectorizer.pkl: use to transform new text
- X_*_seq.npy: padded int sequences for DL
- word_index.json: vocabulary mapping token->id (1..V), 0=PAD
- y_*.npy: labels arrays
- embedding_matrix_glove100.npy: (V+1, 100) matrix, GloVe if available else random
