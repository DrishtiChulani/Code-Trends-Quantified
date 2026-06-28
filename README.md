## Code Trends, Quantified: Mapping the Programming Language Ecosystem

**BA820: Unsupervised Machine Learning | Team 14** <br><br>
**Contributors:** 
1. **Vishesh Goyal** (*BackBencher2424*)
2. **Drishti Chulani** (*DrishtiChulani*)
3. **Arshdeep Singh Oberoi** (*arshdeep-gif*)
4. **Ahrar Karim** (*ahrar11*)

---

###  Project Motivation:
As Business Analytics students, we work with Python daily but realized we were only seeing a fraction of the full programming landscape. This project emerged from wanting to look beyond the hype, by using data analysis to understand the actual ecosystem rather than just the noise. We're mapping the scale of languages that exist, from historical systems to modern releases, and using that data to separate genuine industry impact from marketing noise. 
The goal is straightforward: to identify which languages actually matter and spot emerging trends worth paying attention to. Major stakeholders would be Chief Technology Offiers(CTOs), Product Managers, School Educators, Mentors and Students.

---

###  The Data
This project utilizes a comprehensive metadata repository of over **4,000 programming languages**. This dataset is unique because it treats mathematical notations, ancient numeral systems, and modern syntax as a single continuous lineage of human logic.

#### Data Structure & Composition
* **Scope:** 4,303 entries with 49 technical, community, and economic features.
* **Feature Categories:** * **Technical:** Syntax patterns (assignment operators, comment tokens), file types, and case sensitivity.
    * **Social:** GitHub stars, forks, Wikipedia daily views, and language rank.
    * **Economic:** Job postings (where HTTP and SQL currently lead) and estimated user populations.
      
---

###  Research Questions

#### 1. The Market Discovery
* **Focus:**  Do programming languages naturally cluster into distinct groups based on shared technical features (syntax patterns, file types) and community signals (GitHub activity, Wikipedia view)

#### 2. Economic Strategy
* **Focus** Can we segment programming languages into distinct "Market Archetypes": specifically "Hype Driven" (high GitHub stars/subscribers, low job counts) vs. "Silent" (low social hype, high job counts and user estimates)

#### 3. Risk Mitigation
* **Focus:** Can we detect "Ghost Languages" technologies with significant cultural visibility (high Wikipedia views and rankings) but virtually no real employment ecosystem?

#### 4. Success Pillars Optimization
* **Focus:** Among the 49 technical metadata features we have (syntax patterns, file types, naming conventions), which ones actually predict how long a language survives and remains relevant in the long run?

---

###  Planned Analysis
* **Preprocessing:** Log-transforming skewed community metrics and handling high-missingness technical columns.
* **Clustering:** Applying **K-Means** and **Hierarchical Clustering** to define market segments and technical lineages.
* **Dimensionality Reduction:** Using **Principal Component Analysis (PCA)** to simplify the feature space and identify core variance.

---

###  Repository Structure
* `data/`: Raw and processed versions of the PLDB dataset.
* `notebooks/`: 
    * `EDA_Primary_Dataset.ipynb`: Comprehensive exploratory analysis and visualizations.
* `reports/`: Documentation for project milestones and the final proposal.


