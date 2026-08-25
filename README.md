# ACSIncome Fairness Project

This repository contains the materials for the **Responsible AI (RAI) Class: Auditing & Mitigating Hidden Bias** project. 

Over the course of three weeks, students will evaluate, audit, and mitigate algorithmic bias using the ACSIncome dataset. The project progresses from a baseline fairness audit (Week 1), to a blind data audit of noisy labels (Week 2), and concludes with reference-label evaluation and mitigation strategies (Week 3).

## Final Submission

The final submission is due at the end of **Week 3**. 
You are required to submit a **3-4 page report** summarizing your findings across the three weeks. 
- Please strictly use the [CVPR Paper Template](https://github.com/cvpr-org/author-kit/releases).
- The detailed structure and requirements for the final report can be found at the bottom of the `Week3_Mitigation_Reference_Evaluation.ipynb` notebook.

## Getting Started with Google Colab (Recommended)

To avoid local environment setup issues, we highly recommend using Google Colab to run the Jupyter Notebooks.

**Setup Instructions:**
1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File > Open notebook** and choose the **GitHub** tab.
3. Paste the URL of this repository and open the relevant Week's notebook.
4. **Data Access**: Make sure to upload the necessary CSV files from the `data/` directory of this repository into your Colab environment's `/content/data` folder before running the notebook. You can do this by clicking the "Folder" icon on the left sidebar in Colab and dragging the files in.
5. Alternatively, you can clone the repository directly inside a Colab cell:
   ```python
   !git clone https://github.com/ADE-17/RAI_Project1_Fairness_Project.git
   ```
   and update the `DATA_DIR` path in the notebooks accordingly.
