The PPI.py code found in the GCN_Cancer Resposity from RicardoRamirez2020 will run all 4 models with some modifications. 
The data is similair for each model but the gene order is the only modification

***PPI Model***
Adj_Filtered_List_0Con.mat for the graph containing the adjancy matrix for String PPI interactions 
GeneData - Block_PPI1.mat

***PPI Model + Singleton***
Adj_Filtered_List_0Con.mat for the graph containing the adjancy matrix for String PPI interactions 
Keep the same Matrix for the singleton graph, The graph will use singleton genes from the added nodes. 
GeneData - Block_PPIA.mat

***Co-Expression***
Adj_Spearman_6P.mat for the Co-expression adjancy matrix for 3866 genes 
GeneData - Block_6P.mat

***Co-Expression + Singleton***
Adj_Spearman_6P.mat for the Co-expression adjancy matrix for 3866 genes 
Keep the same Matrix for the singleton graph, The graph will use singleton genes from the added nodes. 
GeneData - Block_6PA.mat