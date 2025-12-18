This work was inspired by the obesity ML challenge presented by CrunchDAO and the Broad Institute.

This project studies how cells become fat cells using gene perturbation data from the Broad Institute obesity machine learning challenge.

Each experiment turns off one gene and measures how the cell changes. Even though many genes are involved, the changes in the cells follow a very simple pattern.

I found that cells only become fat cells after they move in one specific direction in gene expression space. If the cells do not move in this direction, they do not become fat cells.

This direction was found using an unsupervised method, meaning no fat cell labels were used to find it. After finding the direction, I checked how strongly it matched fat cell outcomes and found a very strong relationship.

I also tested many other random directions and showed that none of them worked. This shows that the result is not due to chance and that the direction is required for fat cell formation in this dataset.

The goal of this work is not to build a prediction model. The goal is to understand the basic rule that must be satisfied before fat cells can form.

Video Overview: https://notebooklm.google.com/notebook/4fff7af8-5c25-40a0-92b3-1138e34bc110?artifactId=6d47a496-5f2d-4db9-9e4e-5c5a685134c4
