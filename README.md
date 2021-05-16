# NullitOut

## Plan:

* Look at the implementation code (Tue) 
  * https://github.com/shauli-ravfogel/nullspace_projection   
* Find dataset format (Tue)
* Preprocess our data (format it) (Fri)
  * https://www.kaggle.com/assemzhunis/nullitout/
* Run the null it out algo (Sun)
  * https://colab.research.google.com/drive/1zB8SV-c6t-PGindgnZR0P8KO_wpFOVg_?usp=sharing

1. Convert our datase to embeddings: (get_embeddings_based_dataset(comment_text))
 * Fasttext
 * Bert
2. Train toxicity classifier
 * Profession classifier (start with logistic regression) Y_dev is 'toxicity' (0,1)
 * Savethe performance (Acc)
3. Build ethnicity classifier (Gender classifier) and run NIO
 * get_projection_matrix()
 * get accurcy (we need to reduce this)
4. Run toxicity classifier on our new embeddings
 * get performance (we want this to be somewhat the same as before)



* Plot the results (Sun)
* Analysis report (Sun)
* Presentation (Mon)
