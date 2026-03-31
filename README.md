## Supplemental Experiments

###  [Q4 & L2] Experiment of Random Walk on Cora

*Fig.1: **Various subgraph sampling strategies on Cora.** The experiments are based on 3-layers 64-hidden GCNs, considering four sampling strategies: Scheme I: $\Theta(1/n)$; Scheme II: $\Theta(\log n / n)$; Scheme III: $\Theta(1)$ **(Uniform Sampling)**; and **Random Walk** (incorporating a restart mechanism to prevent entrapment in small isolated subgraphs). Figure (a) illustrates the evolution trends of edge density; Figure (b) illustrates the transfer error of subgraphs relative to the full graph.*

*(The high-resolution figure are available in "Cora_Random_Walk.pdf")*

![Cora_Random_Walk](Cora_Random_Walk.png)



### [Q5] Comparison with Baseline 



*(The high-resolution figure are available in "convergence_comparison.pdf")*

![Comparison with Baseline](convergence_comparison.png)



### [Q6] Downstream Performance

*Fig.3: **Evaluation of transferability on Cora.** Based on 3-layer 64-hidden GCNs, performance of three sampling schemes (Scheme I, II, III) is tested. The subplots respectively display four evaluation metrics: (a) transfer error, (b) cross-entropy loss, (c) accuracy, and (d) Macro-F1 score.*

*( The high-resolution figure are available in "Cora_acc_F1_score.pdf" )*

![Cora_acc_F1_score](Cora_acc_F1_score.png)
