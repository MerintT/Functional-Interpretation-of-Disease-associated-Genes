# Functional-Interpretation-of-Disease-associated-Genes
In this project, we create a data analysis pipeline based on a systematic network-based approach to implement a mathematical model defined by Menche, J, et al. This mathematical model helps in determining the relationship between any two disease pairs and helps us identify if there are any functional and biological similarities between the two diseases or phenotypes. In this report, we will demonstrate how this is achieved with the protein-based positions of two diseases in a network. 

Steps involved are 
1.) Obtaining various datasets such as Disease-Associated Gene dataset, Protein Interaction links dataset, Protein-gene mapping, and more. 
2.) Data Preprocessing, where we clean and process it to make it ready for our pipeline creation. 
3.) Network Creation, this is where we create our network by having appropriate nodes and links as per our consideration. 
4.) Network distance calculation, here we calculate the shortest distances between diseases A and B and compare the distances between A-B protein pairs. 
5.) Next, we will compare the values with the results from the paper and the Relative Risk values from the comorbidity dataset 
6.)Observation of disease pair values and phenotype pair values and inference.
