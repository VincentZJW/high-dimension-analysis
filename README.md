# High Dimension Analysis


## 📈 Project Overview

This project involves the application of high-dimensional data analysis techniques to monthly stock return data from 100 NYSE-listed companies between **January 2005 and December 2019**. The primary objective is to identify and interpret the **common latent factors** that drive return co-movement across companies, with a focus on **systematic risk** and **industry-level behaviour**.

---

## 📁 Dataset Description

- **Source**: `SampleA.csv` (provided via Moodle)
- **Observations**: 180 months (2005–2019)
- **Variables**: 1 date column + 100 stock return columns
- **Format**: Each stock is identified by a unique code:
  - **First letter** = industry (e.g., `H` = Finance)
  - **Next 5 digits** = CRSP PERMNO ID
- **Industry codes**:
  - `B` = Mining  
  - `C` = Construction  
  - `D` = Manufacturing  
  - `E` = Transport & Public Utilities  
  - `F` = Wholesale Trade  
  - `G` = Retail Trade  
  - `H` = Finance, Insurance & Real Estate  
  - `I` = Services  