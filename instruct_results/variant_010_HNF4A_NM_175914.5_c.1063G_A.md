# Variant Analysis Report #10

**Gene:** HNF4A

**Variant:** NM_175914.5:c.1063G>A

---

<think>
Okay, let's tackle this variant interpretation for HNF4A c.1063G>A (p.Gly355Arg). First, I need to go through each of the ACMG/AMP 2015 criteria step by step. 

Starting with the Pathogenic evidence. The first thing is PVS1, which is for loss-of-function variants in genes where LOF is a known disease mechanism. HNF4A is associated with maturity-onset diabetes of the young (MODY), which is typically caused by loss-of-function mutations. However, this is a missense variant, not a LOF like nonsense or frameshift. So PVS1 doesn't apply here. 

Next, PS1: same amino acid change as a known pathogenic variant. The ClinVar entry is Uncertain Significance, so there's no established pathogenic variant with the same change. So PS1 is not met.

PS2: De novo in a patient with no family history. The data here says De novo is N/A, so we can't confirm this. So PS2 is not met.

PS3: Functional studies showing damaging effect. The functional studies are N/A, so no evidence here. PS3 is not met.

PS4: Increased frequency in patients vs controls. The gnomAD data is all None, so no population data to support this. PS4 is not met.

Moving to PM criteria. PM1: located in a hotspot or functional domain. I need to check if Gly355 is in a critical domain. HNF4A has a DNA-binding domain and ligand-binding domain. If Gly355 is in one of these, PM1 might apply. But without specific domain information, I can't be sure. Maybe I should note that it's not in a known hotspot but need more info.

PM2: Absent or very rare in population databases. gnomAD has no data, so this could be a PM2. But since the AF is None, maybe it's not present. However, the absence might be due to lack of data rather than actual absence. But according to ACMG, if it's not present in population databases, that's a PM2. So PM2 might be applicable here.

PM3: Trans in a recessive disease. Not applicable since HNF4A is typically autosomal dominant. So PM3 is not met.

PM4: Change in protein length. This is a missense, so no change in length. PM4 not met.

PM5: Same amino acid with other pathogenic variants. If there are other pathogenic missense variants at this position, PM5 would apply. But since ClinVar is uncertain, and no other variants mentioned, PM5 is not met.

PM6: De novo but not confirmed. Since De novo is N/A, PM6 is not met.

Now, PP criteria. PP1: Co-segregation in family. No family data, so not met.

PP2: Missense in a gene where missense is rare. HNF4A is a gene where missense variants can be pathogenic, but if the gene typically has few missense variants, this might apply. However, without knowing the gene's typical missense rate, it's hard to say. Maybe not enough info here.

PP3: Computational evidence. CADD is 0.997, which is low (CADD >20 is high). REVEL is 0.565, which is below the threshold of 0.5 for pathogenic. So these are not strong indicators. So PP3 is not met.

PP4: Phenotype specificity. If the patient's phenotype is very specific to HNF4A, this could help. But without knowing the patient's phenotype, I can't assess this. So PP4 is not met.

PP5: Classified as pathogenic in a reputable database. ClinVar is Uncertain Significance, so not PP5.

For Benign evidence, BA1: AF >5% in population. Since gnomAD has no data, BA1 is not met.

BS1: Higher frequency than expected. Again, no data, so not applicable.

BS2: Present in healthy adults. No info, so not met.

BS3: Functional studies showing no effect. No functional data, so not met.

BS4: Lack of segregation. No family data, so not met.

BP criteria: BP1: Missense in a gene where LOF is the mechanism. Since HNF4A is LOF, but this is missense, BP1 might apply. However, the variant is missense, so BP1 is not applicable.

BP2: Trans with pathogenic variant. Not applicable.

BP3: In-frame indel in non-functional region. Not applicable.

BP4: Computational evidence for benign. CADD and REVEL are low, but not strong enough. So BP4 is not met.

BP5: Alternative molecular evidence. No data.

BP6: Classified as benign in reputable database. ClinVar is uncertain, so no.

BP7: No splice effect. SpliceAI is N/A, but since it's a missense, no splice effect. So BP7 is met.

Now, compiling the evidence. The only possible pathogenic criteria are PM2 (if applicable) and maybe PM1 if the position is in a functional domain. However, without domain info, PM1 is uncertain. The only supporting evidence is BP7. 

Since there's no strong pathogenic evidence and some benign (BP7), but not enough to meet the criteria for Benign. The ClinVar is Uncertain Significance, so the variant is likely a VUS. The absence in population databases (PM2) might be a weak pathogenic, but without more data, it's not enough. The computational scores are not strong for pathogenic, so the classification would be VUS with low confidence. Need more functional studies or family data to clarify.
</think>

### **ACMG/AMP 2015 기준 체계적 평가**

---

#### **1. 병원성 증거 (Pathogenic Evidence)**

**A. 매우 강력 (PVS1):**  
- **평가:** 미충족  
- **근거:** PVS1은 유전자에서의 LOF 변이(예: nonsense, frameshift 등)에 해당해야 하지만, 이 변이는 **missense**로, LOF 기전이 아닙니다.  
- **강도:** 미충족  

---

**B. 강력 (PS1-PS4):**  
- **PS1:** 미충족 (ClinVar에서 동일한 아미노산 변화의 병원성 변이가 확인되지 않음).  
- **PS2:** 미충족 (De novo 여부 확인 불가).  
- **PS3:** 미충족 (기능 연구 데이터 없음).  
- **PS4:** 미충족 (gnomAD에서 환자군 대비 유병률 증가 데이터 없음).  

---

**C. 중등도 (PM1-PM6):**  
- **PM1:** 미충족 (단백질 기능 도메인 위치 확인 불가).  
- **PM2:** **충족** (gnomAD에서 대립유전자 빈도가 없음 → **PM2**).  
- **PM3:** 미충족 (열성 질환 관련 trans 변이 데이터 없음).  
- **PM4:** 미충족 (단백질 길이 변화 없음).  
- **PM5:** 미충족 (동일 아미노산 위치의 병원성 변이 없음).  
- **PM6:** 미충족 (De novo 여부 확인 불가).  

---

**D. 지지 (PP1-PP5):**  
- **PP1:** 미충족 (가족 분리 데이터 없음).  
- **PP2:** 미충족 (유전자별 missense 빈도 정보 부족).  
- **PP3:** 미충족 (CADD=0.997, REVEL=0.565 → 유해 효과 지지 불충분).  
- **PP4:** 미충족 (환자 표현형/가족력 정보 부족).  
- **PP5:** 미충족 (ClinVar에서 병원성으로 분류되지 않음).  

---

#### **2. 양성 증거 (Benign Evidence)**

**A. 단독 (BA1):**  
- **평가:** 미충족 (gnomAD AF 데이터 없음).  

---

**B. 강력 (BS1-BS4):**  
- **BS1:** 미충족 (유병률/발현율 데이터 부족).  
- **BS2:** 미충족 (건강한 성인에서 관찰 여부 확인 불가).  
- **BS3:** 미충족 (기능 연구 데이터 없음).  
- **BS4:** 미충족 (분리 데이터 없음).  

---

**C. 지지 (BP1-BP7):**  
- **BP1:** 미충족 (missense 변이로, LOF 기전 유전자에 해당하지 않음).  
- **BP2:** 미충족 (trans/cis 관계 데이터 없음).  
- **BP3:** 미충족 (반복 영역 in-frame indel 아님).  
- **BP4:** 미충족 (전산 예측이 유해 효과 지지 불충분).  
- **BP5:** 미충족 (대체 분자적 근거 없음).  
- **BP6:** 미충족 (신뢰할 수 있는 출처에서 양성으로 분류되지 않음).  
- **BP7:** **충족** (SpliceAI 및 보존성 데이터 없음 → **BP7**).  

---

#### **3. 최종 분류**

**적용된 기준 요약:**  
- **병원성:** PM2 (중등도)  
- **양성:** BP7 (지지)  

**분류 규칙:**  
- **VUS (임상적 의미 불명)**: 병원성/양성 기준 모두 충족되지 않음.  

**최종 분류:** **VUS (Variants of Uncertain Significance)**  
**신뢰도:** **낮음**  

**해석 요약:**  
- **HNF4A c.1063G>A (p.Gly355Arg)**는 missense 변이로, LOF 기전 유전자에서의 PVS1 기준 미충족.  
- gnomAD에서 대립유전자 빈도 데이터 없음 (PM2) 및 스플라이스 영향 없음 (BP7)으로, **중등도 병원성 증거**와 **지지 양성 증거**가 각각 1개씩 충족됨.  
- 그러나 병원성/양성 기준 모두 충족되지 않아 **VUS**로 분류.  

**권고사항:**  
- **기능 연구** (예: 유전자 발현, 단백질 기능 분석) 또는 **가계 분리 데이터** 수집이 필요.  
- **환자 표현형** (예: MODY 유형, 혈당 수치 등)과의 연관성 분석을 통해 추가 증거 확보.  

--- 

**참고:**  
- **CADD (0.997)** 및 **REVEL (0.565)**은 유해 효과 지지 불충분.  
- **ClinVar (Uncertain Significance)**는 추가 분석 필요.