# Variant Analysis Report #13

**Gene:** GP9

**Variant:** NM_000174.5:c.488C>A

---

<think>
Okay, let's tackle this variant interpretation. The user provided a missense variant in GP9: c.488C>A (p.Ala163Asp). I need to apply the ACMG/AMP 2015 guidelines and ClinGen SVI recommendations. Let me start by recalling the criteria.

First, check PVS1. PVS1 is for variants in a critical splice site, but this is a missense, so PVS1 doesn't apply. Next, PS1-4. PS1 is for a variant in a known pathogenic variant, but I don't see any info on that here. PS2 is for a variant in a gene where all pathogenic variants are missense, but GP9's role isn't clear. PS3 is for segregation in families, but there's no family data. PS4 is for functional studies, which are also not available. So PS criteria don't apply.

Now PM1-6. PM1 is for population frequency. The gnomAD AF is 5.888e-05, which is very low. But the popmax is 0.000998, which is higher. Wait, the popmax is the maximum AF in any population. So maybe the variant is rare but present in some populations. However, the overall AF is still very low. PM1 might be applicable if the frequency is below the population-specific threshold. But I need to check if the popmax is considered. Since the overall AF is low, PM1 could be considered as a moderate evidence.

PM2 is for conservation. The phyloP score is N/A, so can't use that. PM3 is for a variant in a gene where all pathogenic variants are missense, but again, not sure about GP9's role. PM4 is for a variant in a gene with a known functional domain. The position is p.Ala163. I need to check if this is in a functional domain. If the protein is involved in platelet function, maybe, but without more info, it's hard to say. PM5 is for a variant in a gene where the same amino acid change is known to be pathogenic. Not mentioned here. PM6 is for a variant in a gene with a known functional impact. Again, not enough data.

PP1-5. PP1 is for de novo in a patient with the disease. No de novo info. PP2 is for a variant in a gene where the majority of pathogenic variants are missense. If GP9 is such a gene, but I don't know. PP3 is for functional studies, which are N/A. PP4 is for a variant in a gene with a known role in the disease. If GP9 is related to the patient's condition, but the user didn't specify the disease. PP5 is for a variant in a gene with a known association. Not enough info.

BA1 is for a variant in a gene with a known pathogenic variant. Not applicable here. BS1 is for population frequency. The AF is low, but popmax is higher. Maybe BS1 doesn't apply. BS2 is for a variant in a gene where the majority of variants are benign. Not sure. BS3 is for a variant in a gene with a known benign variant. ClinVar says Likely_benign, so that's a BS3. BS4 is for a variant in a gene where the same change is known to be benign. ClinVar's Likely_benign would support that.

BP1-7. BP1 is for population frequency. The AF is low, so maybe not. BP2 is for a variant in a gene where the majority of variants are benign. If ClinVar has Likely_benign, that's a BP2. BP3 is for a variant in a gene with a known benign variant. Again, ClinVar's entry. BP4 is for a variant in a gene with a known benign variant. BP5 is for a variant in a gene with a known benign variant. BP6 is for a variant in a gene with a known benign variant. BP7 is for a variant in a gene with a known benign variant. So multiple BP criteria apply here.

Now, ClinGen SVI for PS3/BS3. Since there's no family data, PS3 isn't applicable. BS3 is for a variant in a database with a benign classification, which ClinVar's Likely_benign supports.

Putting it all together: PM1 (low frequency), BS3 (ClinVar), and BP2/BP3/BP4/BP5/BP6/BP7 (ClinVar's benign classification). The CADD and REVEL scores are low, which might support benign. No evidence for pathogenic. So the classification would be Benign or Likely Benign. But since ClinVar is Likely_benign, and the population frequency is low but not extremely, maybe the final classification is Likely Benign with moderate confidence.
</think>

### ACMG/AMP 2015 기준 및 ClinGen SVI 권고안에 따른 변이 해석

#### **1. 변이 정보 요약**
- **유전자**: GP9  
- **변이**: NM_000174.5:c.488C>A (p.Ala163Asp)  
- **유형**: Missense  
- **기능 영역**: 알라닌 (Ala) → 아스파라긴산 (Asp)  
- **집단 빈도**:  
  - gnomAD 전체 빈도 (AF): 5.88833e-05 (0.0059%)  
  - gnomAD popmax (최대 인구군 빈도): 0.000998839 (0.0999%)  
  - gnomAD 동형접합: 0.0  

---

### **2. ACMG/AMP 2015 기준 평가**

#### **PVS1 (Pathogenic Variant in Splice Site)**  
- **적용 여부**: **불가능**  
- **근거**: 이 변이는 스플라이스 사이트에 위치하지 않으며, **missense** 변이로 분류됨.  
- **결론**: PVS1 기준 충족 X.

---

#### **PS1-4 (Pathogenic Supporting Evidence)**  
- **PS1 (Known Pathogenic Variant)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 알려진 병리적 변이와 동일한 위치/유형이 제공되지 않음.  
- **PS2 (Missense in Gene with All Pathogenic Variants as Missense)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자의 병리적 변이 유형에 대한 데이터 부족.  
- **PS3 (Segregation in Family)**:  
  - **적용 여부**: **불가능**  
  - **근거**: 가계 분리 데이터 없음.  
- **PS4 (Functional Studies)**:  
  - **적용 여부**: **불가능**  
  - **근거**: in vitro/in vivo 기능 연구 데이터 없음.  

- **결론**: PS 기준 충족 X.

---

#### **PM1-6 (Moderate Evidence for Pathogenicity)**  
- **PM1 (Population Frequency)**:  
  - **적용 여부**: **가능** (Moderate)  
  - **근거**:  
    - gnomAD 전체 빈도: **5.888e-05** (0.0059%) → 매우 낮은 빈도.  
    - popmax 빈도: **0.0009988** (0.0999%) → 특정 인구군에서의 빈도는 낮으나, 전체 빈도는 극히 낮음.  
    - **ClinGen SVI 권고안**:  
      - **PS3/BS3 강도 조절**: PS3 (가계 분리) 및 BS3 (데이터베이스 분류)는 적용 불가능.  
      - **PM1 강도**: gnomAD AF < 0.0001 (1e-4) → **Moderate** (PM1).  
- **PM2 (Conservation)**:  
  - **적용 여부**: **불가능**  
  - **근거**: phyloP 보존성 데이터 없음.  
- **PM3 (Missense in Gene with All Pathogenic Variants as Missense)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자의 병리적 변이 유형에 대한 데이터 부족.  
- **PM4 (Functional Domain)**:  
  - **적용 여부**: **불가능**  
  - **근거**: 단백질 기능 영역 (예: GPI-anchored domain)에 대한 정보 부족.  
- **PM5 (Same Amino Acid Change in Pathogenic Variants)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 변화의 병리적 변이 기록 없음.  
- **PM6 (Known Functional Impact)**:  
  - **적용 여부**: **불가능**  
  - **근거**: 기능적 영향에 대한 데이터 없음.  

- **결론**: **PM1 (Moderate)** → 병리성 가능성을 약간 지원.

---

#### **PP1-5 (Supporting Evidence for Benignity)**  
- **PP1 (De Novo in Affected Individual)**:  
  - **적용 여부**: **불가능**  
  - **근거**: de novo 데이터 없음.  
- **PP2 (Missense in Gene with Most Pathogenic Variants as Missense)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자의 병리적 변이 유형에 대한 데이터 부족.  
- **PP3 (Functional Studies)**:  
  - **적용 여부**: **불가능**  
  - **근거**: 기능 연구 데이터 없음.  
- **PP4 (Known Role in Disease)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자의 질병 관련 역할에 대한 정보 부족.  
- **PP5 (Known Benign Variant)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 변화의 양성 변이 기록 없음.  

- **결론**: PP 기준 충족 X.

---

#### **BA1 (Benign Allele in Database)**  
- **적용 여부**: **불가능**  
- **근거**: HGMD 데이터 없음.  

---

#### **BS1-4 (Benign Supporting Evidence)**  
- **BS1 (Population Frequency)**:  
  - **적용 여부**: **가능** (Moderate)  
  - **근거**:  
    - gnomAD 전체 빈도: **5.888e-05** (0.0059%) → 매우 낮은 빈도.  
    - **ClinGen SVI 권고안**:  
      - **BS1 강도**: gnomAD AF < 0.0001 (1e-4) → **Moderate** (BS1).  
- **BS2 (Missense in Gene with Most Variants Benign)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자의 변이 유형 분포에 대한 데이터 부족.  
- **BS3 (ClinVar Classification)**:  
  - **적용 여부**: **가능** (Strong)  
  - **근거**:  
    - **ClinVar**: **Likely_benign** (변이 분류).  
    - **ClinGen SVI 권고안**:  
      - **BS3 강도**: ClinVar의 **Likely_benign** 분류 → **Strong** (BS3).  
- **BS4 (Same Amino Acid Change in Benign Variants)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 변화의 양성 변이 기록 없음.  

- **결론**: **BS1 (Moderate)**, **BS3 (Strong)** → 양성 가능성을 강력히 지원.

---

#### **BP1-7 (Benign Supporting Evidence)**  
- **BP1 (Population Frequency)**:  
  - **적용 여부**: **가능** (Moderate)  
  - **근거**: gnomAD AF < 0.0001 (1e-4) → **Moderate** (BP1).  
- **BP2 (Missense in Gene with Most Variants Benign)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자의 변이 유형 분포에 대한 데이터 부족.  
- **BP3 (Known Benign Variant in Same Gene)**:  
  - **적용 여부**: **가능** (Moderate)  
  - **근거**: ClinVar의 **Likely_benign** 분류 → **Moderate** (BP3).  
- **BP4 (Known Benign Variant in Same Amino Acid Position)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 위치의 양성 변이 기록 없음.  
- **BP5 (Known Benign Variant in Same Gene and Amino Acid)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 변화의 양성 변이 기록 없음.  
- **BP6 (Known Benign Variant in Same Gene and Amino Acid)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 변화의 양성 변이 기록 없음.  
- **BP7 (Known Benign Variant in Same Gene and Amino Acid)**:  
  - **적용 여부**: **불가능**  
  - **근거**: GP9 유전자에서 동일한 아미노산 변화의 양성 변이 기록 없음.  

- **결론**: **BP1 (Moderate)**, **BP3 (Moderate)** → 양성 가능성을 약간 지원.

---

### **3. 종합 평가 및 최종 분류**

#### **증거 요약**
- **병리성 지원 (Pathogenic)**:  
  - PM1 (Moderate)  
- **양성 지원 (Benign)**:  
  - BS1 (Moderate), BS3 (Strong), BP1 (Moderate), BP3 (Moderate)  
  - ClinVar의 **Likely_benign** 분류  

#### **전산 예측**  
- **CADD**: 0.9677 (낮은 병리성 가능성)  
- **REVEL**: 0.564 (낮은 병리성 가능성)  

#### **최종 분류**
- **분류**: **Likely Benign**  
- **신뢰도**: **Moderate**  
- **임상적 해석**:  
  - 이 변이는 **gnomAD**에서 극히 낮은 빈도를 보이며, **ClinVar**에서 **Likely_benign**으로 분류됨.  
  - 전산 예측 (CADD, REVEL)도 병리성 가능성을 낮게 평가.  
  - 가계 분리, 기능 연구, 동일한 아미노산 변화의 병리적 변이 기록 등이 없어 병리성 증거 부족.  
  - **ClinGen SVI 권고안**에 따라, **BS3 (ClinVar 분류)**와 **PM1 (낮은 빈도)**를 고려하여 **Likely Benign**으로 분류됨.

---

### **4. 결론**
이 변이 (NM_000174.5:c.488C>A, p.Ala163Asp)는 **Likely Benign**으로 분류되며, **Moderate 신뢰도**로 임상적 해석됨. 추가적인 가계 분리 데이터 또는 기능 연구가 필요할 수 있으나, 현재 증거는 병리성보다는 양성 가능성을 더 강하게 지지함.