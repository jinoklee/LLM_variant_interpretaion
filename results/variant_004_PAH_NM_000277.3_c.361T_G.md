# Variant Analysis Report #4

**Gene:** PAH

**Variant:** NM_000277.3:c.361T>G

---

<think>
Okay, let's tackle this variant interpretation using the ACMG/AMP 2015 guidelines and ClinGen SVI recommendations. The variant in question is PAH c.361T>G (p.Phe121Val). 

First, I need to go through each of the ACMG/AMP criteria step by step. Let's start with PVS1, which is about loss of function in a gene where LOF variants are known to cause disease. PAH is the gene for phenylalanine hydroxylase, and mutations here cause phenylketonuria (PKU). However, this is a missense variant, not a LOF. So PVS1 doesn't apply here.

Next, PS1-4. PS1 is about the presence in a disease-specific database. ClinVar lists this as Likely_pathogenic, which is a strong indicator. PS1 is met. PS2 would be a de novo occurrence, but the data here says De novo is N/A, so that's not applicable. PS3 is about segregation in families, but again, family data is N/A. PS4 is about functional studies, which are also N/A here. So PS1 is the only applicable here.

Now PM1-6. PM1 is about population frequency. The gnomAD data is all None, which suggests it's not present in the population. That's a PM1. PM2 is about conservation, but phyloP is N/A. PM3 is about a known pathogenic variant in the same residue, but I don't see that mentioned. PM4 is about predicted effect, which includes CADD and REVEL. Both are high (CADD 0.99, REVEL 0.99), so that's PM4. PM5 is about a variant in a gene where LOF is known to cause disease, but again, this is missense. PM6 is about a variant in a critical domain, but the position (Phe121) might be in a functional domain. I need to check if Phe121 is in a critical region. Since PAH is a tetramer, maybe the active site or dimerization domain. If it's in a critical region, that would support PM6. But without specific info, I might not be able to confirm that. So maybe PM6 is uncertain.

PP1-5. PP1 is about a variant in a gene where LOF is known to cause disease, but again, this is missense. PP2 is about a variant in a gene where LOF is known, but same issue. PP3 is about functional studies, which are N/A. PP4 is about other evidence, but not applicable. PP5 is about a variant in a gene with a known pathogenic variant, but I don't have that info here. So PP criteria might not apply.

BA1 is about a variant in a gene where LOF is known to cause disease, but again, this is missense. So BA1 doesn't apply.

BS1-4. BS1 is about population frequency, but since gnomAD is None, that's not applicable. BS2 is about a variant in a gene where LOF is known, but again, this is missense. BS3 is about a variant in a gene where LOF is known, but same issue. BS4 is about a variant in a gene where LOF is known, but again, not applicable. So BS criteria might not apply here.

BP1-7. BP1 is about a variant in a gene where LOF is known, but again, this is missense. BP2 is about a variant in a gene where LOF is known, same issue. BP3 is about a variant in a gene where LOF is known, but again, not applicable. BP4 is about a variant in a gene where LOF is known, but same. BP5 is about a variant in a gene where LOF is known, but again, not applicable. BP6 is about a variant in a gene where LOF is known, but same. BP7 is about a variant in a gene where LOF is known, but again, not applicable. So BP criteria don't apply here.

Now, considering ClinGen SVI for PS3/BS3 and PVS1. Since the variant is missense, PVS1 doesn't apply. PS3 would require segregation data, which is N/A. So PS3 isn't applicable. BS3 would be if the variant is in a region that's not known to be pathogenic, but since the variant is in a gene where LOF is known, but this is missense, maybe not. However, the high CADD and REVEL scores support pathogenicity.

Putting it all together: PS1 (ClinVar Likely_pathogenic), PM1 (absent in population), PM4 (high prediction scores). The absence in population (PM1) and high prediction (PM4) along with ClinVar (PS1) would support a likely pathogenic classification. However, since there's no functional data or segregation, it's not definitive. But given the strong PS1 and PM1/PM4, the classification would be Likely Pathogenic.
</think>

### **ACMG/AMP 2015 기준 평가 및 변이 해석**

#### **1. PVS1 (Loss of Function in a Gene with LOF Disease Association)**
- **적용 여부**: **불적용**  
- **근거**: PAH 유전자는 phenylketonuria (PKU)의 원인 유전자로, LOF 변이가 질병을 유발합니다. 그러나 이 변이는 **missense** 유형으로, LOF가 아닙니다. 따라서 PVS1 기준은 해당되지 않습니다.

---

#### **2. PS1-4 (Population Frequency, Segregation, Functional Studies, etc.)**
- **PS1 (Disease-Specific Database)**:  
  - **적용 여부**: **적용**  
  - **근거**: ClinVar에서 **Likely_pathogenic**으로 분류되어 있습니다. 이는 질병 관련 데이터베이스에서의 강력한 증거로, PS1 기준을 충족합니다.  
- **PS2 (De novo Occurrence)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 가계 분리 및 de novo 데이터가 제공되지 않았습니다.  
- **PS3 (Segregation in Families)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 가계 분리 데이터가 제공되지 않았습니다.  
- **PS4 (Functional Studies)**:  
  - **적용 여부**: **불적용**  
  - **근거**: in vitro/in vivo 기능 연구 데이터가 제공되지 않았습니다.

---

#### **3. PM1-6 (Population Frequency, Conservation, Predicted Effect, etc.)**
- **PM1 (Population Frequency)**:  
  - **적용 여부**: **적용**  
  - **근거**: gnomAD AF (전체, popmax, 동형접합) 모두 **None**으로, 일반 인구에서의 빈도가 매우 낮거나 관찰되지 않았습니다. 이는 PM1 기준을 충족합니다.  
- **PM2 (Conservation)**:  
  - **적용 여부**: **불적용**  
  - **근거**: phyloP 보존성 데이터가 제공되지 않았습니다.  
- **PM3 (Known Pathogenic Variant in Same Residue)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 동일한 아미노산 위치에서의 알려진 병리적 변이가 제공되지 않았습니다.  
- **PM4 (Predicted Effect)**:  
  - **적용 여부**: **적용**  
  - **근거**: CADD (0.99)와 REVEL (0.99) 점수가 모두 **높은 예측 경로성**을 나타냅니다. 이는 PM4 기준을 충족합니다.  
- **PM5 (Critical Domain)**:  
  - **적용 여부**: **불확실**  
  - **근거**: Phe121이 PAH 단백질의 **활성 부위** 또는 **다имер화 영역**에 위치하는지에 대한 정보가 부족합니다. 추가 분석이 필요합니다.  
- **PM6 (Known Pathogenic Variant in Same Gene)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 동일 유전자에서의 알려진 병리적 변이와의 연관성 데이터가 제공되지 않았습니다.

---

#### **4. PP1-5 (Prior Disease Association, Functional Studies, etc.)**
- **PP1 (Gene-Disease Association)**:  
  - **적용 여부**: **적용**  
  - **근거**: PAH 유전자는 PKU의 원인 유전자로, 질병과의 강한 연관성이 있습니다.  
- **PP2 (De novo Occurrence in Disease)**:  
  - **적용 여부**: **불적용**  
  - **근거**: de novo 데이터가 제공되지 않았습니다.  
- **PP3 (Functional Studies)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 기능 연구 데이터가 제공되지 않았습니다.  
- **PP4 (Other Evidence)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 추가 증거가 제공되지 않았습니다.  
- **PP5 (Known Pathogenic Variant in Same Gene)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 동일 유전자에서의 알려진 병리적 변이와의 연관성 데이터가 제공되지 않았습니다.

---

#### **5. BA1 (Benign Allele Frequency)**  
- **적용 여부**: **불적용**  
- **근거**: gnomAD에서의 빈도가 제공되지 않았으며, 병리적 변이로 분류되었으므로 BA1 기준은 해당되지 않습니다.

---

#### **6. BS1-4 (Benign Evidence, Population Frequency, etc.)**  
- **BS1 (Population Frequency)**:  
  - **적용 여부**: **불적용**  
  - **근거**: gnomAD에서의 빈도가 제공되지 않았으며, PM1 기준을 충족합니다.  
- **BS2 (Known Benign Variant in Same Residue)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 동일 아미노산 위치에서의 알려진 양성 변이가 제공되지 않았습니다.  
- **BS3 (Known Benign Variant in Same Gene)**:  
  - **적용 여부**: **불적용**  
  - **근거**: 동일 유전자에서의 알려진 양성 변이와의 연관성 데이터가 제공되지 않았습니다.  
- **BS4 (Population Frequency in Controls)**:  
  - **적용 여부**: **불적용**  
  - **근거**: gnomAD에서의 빈도가 제공되지 않았습니다.

---

#### **7. BP1-7 (Benign Prior Evidence, etc.)**  
- **적용 여부**: **불적용**  
- **근거**: BP 기준은 병리적 변이에 대한 증거가 부족한 경우에 적용되며, 현재 데이터는 병리성에 대한 강력한 증거를 보입니다.

---

### **ClinGen SVI 권고안 적용**
- **PS3/BS3**:  
  - PS3 (가계 분리 데이터)와 BS3 (비병리적 변이와의 연관성)는 모두 **데이터 부족**으로 인해 적용되지 않았습니다.  
- **PVS1 강도 조절**:  
  - PVS1은 missense 변이에 해당하지 않으므로, 강도 조절이 필요 없습니다.

---

### **최종 분류 및 해석**
- **분류**: **Likely Pathogenic (병원성 가능)**  
- **신뢰도**: **높음**  
- **근거**:  
  1. **PS1 (ClinVar: Likely_pathogenic)**: 질병 관련 데이터베이스에서의 강력한 증거.  
  2. **PM1 (gnomAD 빈도 None)**: 일반 인구에서의 빈도가 매우 낮거나 관찰되지 않음.  
  3. **PM4 (CADD 0.99, REVEL 0.99)**: 고도로 예측된 병리적 효과.  
  4. **PP1 (PAH 유전자의 질병 연관성)**: PKU와의 강한 연관성.  

- **주의 사항**:  
  - 기능 연구 데이터 (in vitro/in vivo) 및 가계 분리 데이터가 부족하여, **확정적 병리성**으로 분류하기에는 증거가 부족합니다.  
  - Phe121의 기능적 중요성에 대한 추가 분석이 필요할 수 있습니다.

---

### **결론**
이 변이 (PAH c.361T>G, p.Phe121Val)는 **Likely Pathogenic**으로 분류되며, PKU의 원인 유전자 PAH에서의 **고도로 예측된 병리적 효과**와 **인구 빈도 부족**, **ClinVar의 병리성 분류**를 바탕으로 합니다. 그러나 추가 기능 연구 및 가계 분리 데이터가 필요합니다.