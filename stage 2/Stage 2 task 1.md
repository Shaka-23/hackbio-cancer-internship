**Stage 02 Task**

**Hackbio internship: Drug discovery**

**_Author_**

 Ntsieni Midalo Shaka<sup>1</sup>

The p53 protein, encoded by the TP53 gene, is a vital tumor suppressor that maintains genomic integrity. It contains several key domains: the transactivation domain, initiating transcription of target genes; the DNA-binding domain, responsible for DNA interaction; the tetramerization domain, crucial for tetramer formation; and the regulatory domain, which modulates p53's activity \[1]. These domains enable p53 to regulate the cell cycle, repair DNA, and trigger apoptosis in response to severe damage \[7]. Mutations in TP53 are found in over 50% of human cancers, primarily affecting the DNA-binding domain, impairing p53's ability to bind DNA and activate its targets \[5]. Consequently, cells with defective p53 bypass normal growth controls, promoting tumor progression. Restoring p53 function or targeting its pathways is a major focus in cancer therapy research \[9].

Method:

Swiss-Model is a web-based tool that predicts protein structures by aligning target sequences with experimental templates \[8]. In contrast, AlphaFold uses deep learning, predicting structures based on neural networks trained on large datasets of protein structures \[2].&#x20;

 Results:

This section presents the comparative analysis for 1TUP comparing predicted models to PDB crystal structures.

 !\[1TUP structure]\(https\://github.com/user-attachments/assets/a9aedd95-96c7-4eff-99e8-a2529f92d434)

Fig 1: P53 1TUP protein 3D structure with four chains viewed in PDB database

\- Domain Coverage: Swiss-Model focuses on the DNA-binding domain as seen in figure 2a, while AlphaFold2 predicts all domains \[6] as seen in figure 2b

!\[swiss model structure]\(https\://github.com/user-attachments/assets/573aec4c-90c7-48f0-bad9-9880e4dfe0be)

Figure 2a shows the swiss model structure of 1TUP 

!\[Alphafold]\(https\://github.com/user-attachments/assets/13fc8693-7147-45a4-ab92-4c911b1a98f9)

Figure 2b: This figure depits all domains of the 1TUP protein using alphafold2

\- Modelling: Swiss-Model produced a structure with 95.83% of residues in favored regions of the Ramachandran plot and a MolProbity score of 1.52, indicating structural reliability \[3,4]. AlphaFold2, though confident about the main structure, showed uncertainty in flexible regions \[2].

 

 !\[swissmodel]\(https\://github.com/user-attachments/assets/36cbf530-f0be-4051-8a10-5fc6c884742b)

Figure 3: The above figure shows the Molprobity and the ramachandran favoured 

\- Structural Accuracy: Swiss-Model’s high RMSD of 12.781 Å suggests lower accuracy, while AlphaFold achieved a much lower RMSD of 0.0476 Å, indicating high similarity to the native structure \[2].

!\[pymol]\(https\://github.com/user-attachments/assets/de974d42-ec59-4916-b4f3-dc064b14fba5)

Figure 4: The above figure depicts the RMSD of different structures showing relatedness to the native structure.

Conclusion:

Swiss-Model provides reliable predictions for well-characterized proteins using experimental templates. AlphaFold, however, excels where templates are unavailable, producing more accurate results, as demonstrated in the p53 model, where AlphaFold's lower RMSD indicated a closer match to the native structure.

 

References:

1\. Joerger, A. C., & Fersht, A. R. (2008). Structural biology of the tumor suppressor p53. _Annual Review of Biochemistry_, 77, 557-582.

2\. Jumper, J., et al. (2021). Highly accurate protein structure prediction with AlphaFold. _Nature_, 596(7873), 583-589.

3\. Lovell, S. C., et al. (2003). Structure validation by Cα geometry: ϕ, ψ and Cβ deviation. _Proteins_, 50(3), 437-450.

4\. MolProbity: Structure validation tool. (_http\://molprobity.biochem.duke.edu_).

5\. Olivier, M., et al. (2010). TP53 mutations in human cancers: Origins, consequences, and clinical use. _Cold Spring Harbor Perspectives in Biology_, 2(1), a001008.

6\. Tunyasuvunakool, K., et al. (2021). Protein structure prediction for the human proteome. _Nature_, 596(7873), 590-596.

7\. Vogelstein, B., et al. (2000). Surfing the p53 network. _Nature_, 408(6810), 307-310.

8\. Waterhouse, A., et al. (2018). SWISS-MODEL: Homology modelling of protein structures and complexes. _Nucleic Acids Research_, 46(W1), W296-W303.

9\. Wiman, K. G. (2010). Restoration of wild-type p53 function in human cancer. _Advances in Cancer Research_, 107, 317-332.
