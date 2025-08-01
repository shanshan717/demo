# Ontological dataset of Self-related Studies in Neuroimaging
This dataset, compiled up to August 1, 2025, standardizes metadata extracted from neuroimaging studies that employed self-referential encoding tasks. In total, the dataset includes 136 studies involving 4,694 participants from 17 countries.

## Data Description
Participants (N = 4694, including 2697 females) span a wide age range, from adolescents to the elderly, and include both healthy individuals and patients with psychiatric disorders.

In version 4, we expanded our literature search by using broader and more specific keyword combinations related to self-referential processing. As a result, we added 26 studies focusing on self-referential tasks in psychiatric populations.

## Version History

- **Version 4 (Aug 01, 2025)**: Expanded search terms; added studies involving psychiatric populations.
- **Version 3 (Jan 22, 2024)**: Includes adolescents and elderly, enhanced disease info in the Codebook.
- **Version 2 (Nov 28, 2022)**: Adult population focus, meta-analysis of healthy subjects.
- **Version 1 (Jul 25, 2022)**: Initial operational definitions and article information.
  
## Software Used
- Used Zotero for literature organization and Python(v3.12.11) for analysis (*Versions 4*).
- Used Zotero for literature organization and MATLAB R2021A for analysis (*Versions 3*).
- Used Endnote for literature storage and R and MATLAB R2018B for analysis (*Versions 1 & 2*).

## Related Publication
- Sun Shutting, Wang Nan, Wen Jiahui, et al. Neuroimaging cognitive ontology dataset of self-reference [J/OL]. China Science Data, 2023, 8(3). (2023-07-27).[DOI: 10.11922/11-6035.csd.2022.0047.zh](https://doi.org/10.11922/11-6035.csd.2022.0047.zh)

- Hu, C., Di, X., Eickhoff, S. B., Zhang, M., Peng, K., Guo, H., & Sui, J. (2016). Distinct and common aspects of physical and psychological self-representation in the brain: A meta-analysis of self-bias in facial and self-referential judgements. Neuroscience & Biobehavioral Reviews, 61, 197–207. https://doi.org/10.1016/j.neubiorev.2015.12.003

## Repository Structure

```
.
├── 1_Reference
│ ├── About.txt
│ ├── ...
│ └── 补充材料2:编码手册.pdf
│
├── 2_Literature_Search
│ ├── About.txt
│ ├── Keyword_search.txt
│ └── Literature_Search.docx
│
├── 3_Article_Screen
│ ├── Endnote_files
│ │ ├── 3_1_Self-ref_hcp
│ │ ├── ...
│ │ └── add_Neurosy+Query_0710
│ ├── Literature_neuroQuery.docx
│ ├── Search_flow.png
│ └── self_ref_screen_flow.docx
│
├── 4_Data_Extraction
│ ├── 4_1_Codebook
│ ├── 4_2_Coordinate
│ └── 4_3_Manual
│
├── 5_Analysis
│ ├── 5_1_Database_health
│ │ └── Database_v13
│ └── 5_2_Database_psych
│ │ ├── 手册_自我参照_操作化定义.csv
│ │ ├── ...
│ │ └── Self_Ref_Operationalization.csv
│
├── 6_Reports
│ ├── 6_1_Project_reports [slides]
│ └── 6_2_Preprint
│ 
├── 7_Dataset
│ ├── Ont_Heal_Self_foci_v1
│ └── self_foci_psy
│
├── .gitignore
├── LICENSE
└── README.md (Overall project documentation)

```

## Contact
- Prof. Hu Chuan-Peng (hcp4715@hotmail.com)
- Shan-Shan Zhu (*Version 3 & 4*, zhushanshan0717@gmail.com)
- Shu-Ting Sun (*Version 1 & 2*, sunshuting19@163.com)


## Contributors
- **[2021.11-present]** **Hu Chuan-Peng**:  Project design; data verification and management; manuscript writing and revision.
- **[2023.01-present]** **Shan-shan Zhu**: Data collection and proofreading; data summarization and organization; manuscript writing and revision.
- **[2025.03-present]** **Xue-Yang Zhu**: Data collection and proofreading.
- **[2025.03-present]** **Yan-Xin Li**: Data collection and proofreading.
- **[2025.03-present]** **Zhao-Li Fan**: Data collection and proofreading.
- **[2024.07-2024.11]** **Si-Yu Wu**: Data collection and proofreading.
- **[2023.01-2023.12]** **Jia-Qi Wu**: Data collection and proofreading, summarization and collation.
- **[2023.07-2023.09]** **Ya-Qi Li**: Database collection and proofreading.
- **[2021.11-2022.12]** **Shu-Ting Sun**: Data collection and proofreading, summarization, data analysis, and paper writing and revision.
- **[2021.11-2022.12]** **Nan Wang**: Data collection and proofreading, summarization and collation, and paper writing and revision.
- **[2021.11-2022.07]** **Jia-Hui Wen**: Data collection.
- **[2023.07-2023.11]** **Jian Xiao**: Data collection and proofreading, database verification, data analysis.
