For liver function assessment, the columns in your table correspond to common Liver Function Tests (LFT). 
Below are the typical normal reference ranges for adults (may vary slightly by lab).


**| Parameter                                   | Normal Range (Adults) | What it Indicates                                                           |**
| ------------------------------------------- | --------------------- | --------------------------------------------------------------------------- |
| **Total Bilirubin**                         | **0.3 – 1.2 mg/dL**   | High levels may indicate liver disease, bile duct obstruction, or hemolysis |
| **Direct Bilirubin (Conjugated)**           | **0 – 0.3 mg/dL**     | Elevated in bile duct obstruction or hepatocellular damage                  |
| **Alkaline Phosphatase (ALP / Alkphos)**    | **44 – 147 IU/L**     | Elevated in bile duct obstruction, liver disease, bone disease              |
| **SGPT (ALT – Alanine Aminotransferase)**   | **7 – 56 U/L**        | Liver cell injury indicator                                                 |
| **SGOT (AST – Aspartate Aminotransferase)** | **10 – 40 U/L**       | Liver, heart, or muscle damage marker                                       |
| **Total Proteins**                          | **6.0 – 8.3 g/dL**    | Indicates liver’s protein synthesis ability                                 |
| **Albumin (ALB)**                           | **3.5 – 5.0 g/dL**    | Low levels suggest chronic liver disease or malnutrition                    |
| **A/G Ratio (Albumin/Globulin)**            | **1.0 – 2.5**         | Lower ratio may indicate liver disease or immune disorders                  |

**Example interpretation patterns (important for datasets)**

**| Pattern                              | Possible Condition                 |**
| ------------------------------------ | ---------------------------------- |
| **High ALT & AST**                   | Hepatitis, liver injury            |
| **High ALP + High Direct Bilirubin** | Bile duct obstruction              |
| **Low Albumin**                      | Chronic liver disease or cirrhosis |
| **AST > ALT (ratio >2)**             | Alcoholic liver disease            |


Typical dataset thresholds used in ML liver datasets

Some healthcare ML datasets (like Indian Liver Patient Dataset) consider risk when roughly:

1. Total Bilirubin > 1.2
2. Direct Bilirubin > 0.3
3. ALT > 56
4. AST > 40
5. ALP > 147
6. Albumin < 3.5
7. A/G ratio < 1
