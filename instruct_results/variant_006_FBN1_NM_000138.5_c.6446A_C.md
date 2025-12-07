# Variant Analysis Report #6

**Gene:** FBN1

**Variant:** NM_000138.5:c.6446A>C

---

<think>
Okay, let's tackle this variant interpretation for FBN1 c.6446A>C (p.Tyr2149Ser). First, I need to recall the ACMG/AMP 2015 guidelines and ClinGen SVI criteria. The user provided all the necessary data, so I'll go through each section step by step.

Starting with the Pathogenic criteria. PVS1 is for loss-of-function variants in genes where LOF is a known disease mechanism. FBN1 is associated with Marfan syndrome, which is an autosomal dominant disorder. However, the variant here is a missense, not a LOF (nonsense, frameshift, etc.), so PVS1 doesn't apply. So, PVS1 is not met.

Next, PS1: same amino acid change as a known pathogenic variant. The user didn't mention any in ClinVar or HGMD, so PS1 isn't met. PS2 is about de novo variants in patients without family history. The data says De novo is N/A, so no evidence here. PS3 requires functional studies showing damage. The functional studies are N/A, so PS3 isn't met. PS4 is about increased frequency in patients vs controls. The gnomAD data is all None, so no info here. So PS4 isn't met.

Moving to PM criteria. PM1: location in a hotspot or important domain. FBN1 has several domains like the calcium-binding epidermal growth factor-like (cbEGF) domains. Tyr2149 is in the cbEGF domain? I need to check the protein structure. If it's in a critical domain, PM1 might be applicable. But without specific domain information, maybe it's not clear. The user didn't provide that, so maybe PM1 is not met. Alternatively, if the position is in a known functional region, but since it's not specified, I might have to say insufficient data.

PM2: absence from population databases. The gnomAD AF is None, which might mean it's not present or not reported. If it's not present, that's a PM2. But the user wrote "None" for all gnomAD data, which could mean it's not found. So PM2 is met. The strength would be PM2 since it's absent.

PM3: trans in a recessive disease. FBN1 is autosomal dominant, so PM3 doesn't apply. PM4: change in protein length. This is a missense, so no change in length. PM4 not met. PM5: if other pathogenic missenses are at the same position. If there are other pathogenic variants at Tyr2149, then PM5 applies. But since the data doesn't mention that, PM5 is not met. PM6: de novo but not confirmed. The data says De novo is N/A, so PM6 isn't met.

For PP criteria. PP1: co-segregation in families. No data on family segregation, so not met. PP2: missense in a gene where missense is rare. FBN1 is a gene where missense variants are common in Marfan, but if this particular position is a hotspot, maybe. However, without knowing the gene's typical missense frequency, it's hard. The user didn't specify, so maybe PP2 is not met. PP3: computational evidence. CADD is 0.98, which is low (CADD >20 is high), REVEL is 0.869, which is also low (REVEL >0.8 is considered pathogenic). Wait, REVEL's threshold is around 0.8, so 0.869 is just above that. But CADD is low. So maybe some computational evidence, but not strong. So PP3 might be considered as supporting. PP4: phenotype specificity. If the patient's phenotype is very specific to FBN1, but the user didn't provide that info. So PP4 is not met. PP5: classified as pathogenic in a reputable database. ClinVar is -, so no.

Now, the Benign criteria. BA1: allele frequency >5% in population databases. The gnomAD data is None, so not met. BS1: higher frequency than expected. Since it's not present, maybe not applicable. BS2: observed in healthy adults. No data. BS3: functional studies show no effect. No data. BS4: lack of segregation. No data. BP criteria: BP1: missense in a gene where truncating variants cause disease. FBN1 is a gene where truncating variants do cause disease, but this is a missense. So BP1 might not apply. BP2: trans or cis with pathogenic variant. Not applicable. BP3: in-frame indel in non-functional region. Not applicable. BP4: computational evidence of no effect. CADD is low, REVEL is borderline. So maybe BP4 is not met. BP5: alternative molecular evidence. No data. BP6: classified as benign in reputable source. No. BP7: no splice effect. SpliceAI is N/A, but the variant is a missense, so no splice effect. So BP7 is met.

Putting it all together: the only pathogenic criteria met is PM2 (absent in population databases). The PP3 might be considered as some computational evidence, but not strong. The benign criteria include BP7 (no splice effect). However, the computational scores are not strong enough for PP3. Since PM2 is the only pathogenic criterion, and no strong pathogenic criteria, the classification would be VUS. The PM2 is a moderate evidence, but without other criteria, it's not enough to meet the pathogenic or likely pathogenic thresholds. The absence in population databases (PM2) is a moderate evidence, but without other supporting evidence, it's not sufficient. The computational scores are not strong enough for PP3. So the final classification is VUS with low confidence.
</think>

### **1. 병원성 증거 (Pathogenic Evidence)**

#### **A. 매우 강력 (PVS1):**
- **평가:** 미충족  
- **근거:** 변이는 missense 유형이며, LOF (nonsense, frameshift 등) 변이가 아님. FBN1은 autosomal dominant 질환 (Marfan syndrome)의 병인 기전으로 LOF 변이가 알려져 있으나, 이 변이는 LOF가 아님.  
- **강도:** 미충족  

---

#### **B. 강력 (PS1-PS4):**
- **PS1:** 미충족  
  - 근거: ClinVar 및 HGMD에서 동일한 아미노산 변화의 병원성 변이 기록 없음.  
- **PS2:** 미충족  
  - 근거: De novo 여부 확인 불가 (데이터: N/A).  
- **PS3:** 미충족  
  - 근거: 기능 연구 데이터 없음 (in vitro/in vivo: N/A).  
- **PS4:** 미충족  
  - 근거: gnomAD AF (전체/인종별) 데이터 없음.  

---

#### **C. 중등도 (PM1-PM6):**
- **PM1:** 미충족  
  - 근거: 단백질 도메인 위치 정보 부족 (예: cbEGF 도메인 포함 여부 미확인).  
- **PM2:** 충족 (PM2)  
  - 근거: gnomAD AF (전체/인종별) 데이터 없음 → 집단 데이터베이스에서 부재 또는 극히 드묾.  
  - **강도:** PM2 (중등도)  
- **PM3:** 미충족  
  - 근거: FBN1은 autosomal dominant 질환 → PM3 (recessive 질환 관련) 적용 불가.  
- **PM4:** 미충족  
  - 근거: 단백질 길이 변화 없음 (missense).  
- **PM5:** 미충족  
  - 근거: 동일 아미노산 위치의 병원성 미스센스 변이 기록 없음.  
- **PM6:** 미충족  
  - 근거: De novo 여부 확인 불가 (데이터: N/A).  

---

#### **D. 지지 (PP1-PP5):**
- **PP1:** 미충족  
  - 근거: 가계 분리 데이터 없음 (데이터: N/A).  
- **PP2:** 미충족  
  - 근거: FBN1은 missense 변이가 흔한 질환 → PP2 (missense가 드문 유전자) 적용 불가.  
- **PP3:** 미충족  
  - 근거: CADD (0.98) 및 REVEL (0.869) 점수는 중간 수준 (CADD >20, REVEL >0.8: 병원성 기준).  
- **PP4:** 미충족  
  - 근거: 환자 표현형/가족력 정보 부족.  
- **PP5:** 미충족  
  - 근거: ClinVar 등 신뢰할 수 있는 출처에서 병원성 분류 없음.  

---

### **2. 양성 증거 (Benign Evidence)**

#### **A. 단독 (BA1):**
- **평가:** 미충족  
  - 근거: gnomAD AF 데이터 없음 → 대립유전자 빈도 >5% 확인 불가.  

---

#### **B. 강력 (BS1-BS4):**
- **BS1:** 미충족  
  - 근거: gnomAD AF 데이터 없음 → 유병률/발현율 비교 불가.  
- **BS2:** 미충족  
  - 근거: 건강한 성인에서 관찰 여부 확인 불가.  
- **BS3:** 미충족  
  - 근거: 기능 연구 데이터 없음 (in vitro/in vivo: N/A).  
- **BS4:** 미충족  
  - 근거: 환자 분리 데이터 없음 (데이터: N/A).  

---

#### **C. 지지 (BP1-BP7):**
- **BP1:** 미충족  
  - 근거: FBN1은 LOF 변이가 질환을 유발하는 유전자 → missense 변이에 BP1 적용 불가.  
- **BP2:** 미충족  
  - 근거: trans/cis 병원성 변이 관찰 데이터 없음.  
- **BP3:** 미충족  
  - 근거: in-frame indel이 아님.  
- **BP4:** 미충족  
  - 근거: CADD (0.98) 및 REVEL (0.869) 점수는 중간 수준 → 영향 없음 증거 부족.  
- **BP5:** 미충족  
  - 근거: 대체 분자적 근거 데이터 없음.  
- **BP6:** 미충족  
  - 근거: ClinVar 등 신뢰할 수 있는 출처에서 양성 분류 없음.  
- **BP7:** 충족 (BP7)  
  - 근거: SpliceAI (N/A) 및 보존성 (phyloP: N/A) 데이터 없음 → 스플라이스 영향 없음.  

---

### **3. 최종 분류**

#### **적용된 기준 요약:**
- **병원성:** PM2 (중등도)  
- **양성:** BP7 (지지)  

#### **분류 규칙 (ACMG/AMP 2015):**
- **병원성:** 미충족 (PM2 단독으로는 기준 미충족).  
- **병원성 가능:** 미충족 (PM2 + PP3 등 추가 증거 없음).  
- **양성:** 미충족 (BA1, BS1 등 없음).  
- **양성 가능:** 미충족 (BS2, BP4 등 없음).  
- **임상적 의미 불명 (VUS):** 충족 (모든 기준 미충족).  

#### **최종 분류:**
- **분류:** **VUS (Variation of Uncertain Significance)**  
- **신뢰도:** **낮음**  
- **해석 요약:**  
  - FBN1 c.6446A>C (p.Tyr2149Ser)는 missense 변이로, gnomAD 데이터에서 부재 또는 극히 드묾 (PM2). 그러나 단독으로는 병원성 또는 양성으로 분류할 수 없음. 전산 예측 (CADD, REVEL)은 중간 수준으로, 병원성 또는 양성 증거 부족. 추가 분석 필요.  
- **권고사항:**  
  - **가계 분리 분석** 또는 **기능 연구** (예: in vitro 단백질 기능 분석) 수행 필요.  
  - **환자 표현형** 및 **가족력** 정보 추가 수집 필요.  

---

### **결론:**
이 변이는 현재의 증거로는 **임상적 의미 불명 (VUS)**으로 분류되며, 추가 분석이 필요합니다.