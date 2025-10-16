# 🧠 Measuring Associations between Alcohol and Depression in Pre- and Post-Menopausal Women

## 📘 Overview
This project investigates the relationship between **alcohol use** and **depression** among women, stratified by **menopause status**, using data from the **National Health and Nutrition Examination Survey (NHANES)**.  

The central hypothesis is that **moderate to heavy alcohol use** will be correlated with a **higher prevalence of depression**, and that this association will be **less severe in post-menopausal women** due to reduced hormonal fluctuations.

---

## 🎯 Research Goals
- Quantify the association between alcohol consumption patterns and depression among U.S. women.
- Stratify participants into pre- and post-menopausal subgroups.
- Assess whether menopause modifies the association between alcohol use and depression.
- Explore demographic, socioeconomic, and reproductive factors that may confound or mediate these relationships.

---

## 📊 Data Source
All data are drawn from the **National Health and Nutrition Examination Survey (NHANES)**, a continuous cross-sectional program conducted by the **Centers for Disease Control and Prevention (CDC)**.  
NHANES surveys approximately 5,000 Americans annually and collects detailed information on health, lifestyle, diet, and demographics.

---

## 📁 Data Files

| Dataset | Description | Key Variables |
|----------|--------------|----------------|
| **Demographic Survey** (Years x – x) | Participant demographic and socioeconomic data | `RIDAGEYR` – Age in years at screening<br>`RIAGENDR` – Gender<br>`DMDEDUC2` – Education level (Adults 20+)<br>`DMDMARTZ` – Marital status<br>`RIDEXPRG` – Pregnancy status at exam<br>`INDFMPIR` – Ratio of family income to poverty |
| **Alcohol Survey** (Years x – x) | Alcohol consumption frequency and intensity | `ALQ121` – Past 12 months: frequency of alcoholic beverage consumption<br>`ALQ130` – Average number of alcoholic drinks per day (past 12 months)<br>`ALQ151` – Ever have 4/5 or more drinks every day |
| **Reproductive Health Survey** (Years x – x) | Menstrual and reproductive health status | `RHQ031` – Had regular periods in past 12 months<br>`RHD043` – Reason for not having regular periods |
| **Mental Health - Depression Screener (DPQ_L)** | Self-reported symptoms of depression over the past two weeks | `DPQ010` – Little interest or pleasure in doing things<br>`DPQ020` – Feeling down, depressed, or hopeless<br>`DPQ030` – Trouble sleeping or sleeping too much<br>`DPQ040` – Feeling tired or having little energy<br>`DPQ050` – Poor appetite or overeating<br>`DPQ060` – Feeling bad about yourself<br>`DPQ070` – Trouble concentrating on things<br>`DPQ080` – Moving or speaking slowly or too fast<br>`DPQ090` – Thoughts of being**_**
