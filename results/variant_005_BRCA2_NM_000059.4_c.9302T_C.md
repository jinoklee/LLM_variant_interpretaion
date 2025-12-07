# Variant Analysis Report #5

**Gene:** BRCA2

**Variant:** NM_000059.4:c.9302T>C

---

<think>
Okay, let's tackle this variant interpretation for BRCA2 c.9302T>C. First, I need to recall the ACMG/AMP 2015 guidelines and the ClinGen SVI recommendations. The user wants a systematic evaluation of each criterion. Let me start by breaking down the information provided.

The variant is a missense in BRCA2, changing Leucine to Proline at position 3101. The population data from gnomAD is all "None," which might mean it's not present in the database or not reported. ClinVar has conflicting classifications, which is a red flag. HGMD doesn't have it. Computational predictions: CADD is 0.998, which is very low, and REVEL is 0.788, which is also low. SpliceAI and phyloP are N/A. Functional studies are missing. Family segregation and de novo data are not available. Patient-control studies are also N/A.

Now, applying the ACMG/AMP criteria. Let's go through each category.

PVS1: This is for loss of function variants in genes where LOF is a known mechanism. BRCA2 is a tumor suppressor, and LOF variants are pathogenic. However, this is a missense, not a LOF. So PVS1 doesn't apply here.

PS1-4: PS1 is presence in disease, but since it's not in ClinVar or HGMD, maybe not. PS2 is segregation in families, but no data. PS3 is functional studies, which are N/A. PS4 is population frequency. Since gnomAD AF is None, but if it's not present, that might support pathogenicity. However, the absence in population databases could be due to low frequency or not being reported. But without specific data, it's hard to say. Maybe PS4 is not applicable here.

PM1-6: PM1 is population frequency. If the variant is absent in gnomAD, that could be a PM1. But the user says "None" for AF, which might mean it's not present. However, sometimes "None" could mean it's not in the database, but if it's a rare variant, it might not be captured. Need to check if the absence is significant. PM2 is in silico prediction. CADD and REVEL are both low, which would not support PM2. PM3 is functional studies, which are N/A. PM4 is segregation, which is N/A. PM5 is de novo, which is N/A. PM6 is other evidence, which is not applicable here.

PP1-5: PP1 is segregation, which is N/A. PP2 is de novo, which is N/A. PP3 is functional studies, which are N/A. PP4 is population frequency. If the variant is absent in gnomAD, that might support PP4. But again, the absence could be due to low frequency. PP5 is other evidence, which is not applicable.

BA1: This is for variants in a gene where LOF is a known mechanism. But again, this is a missense, not LOF. So BA1 doesn't apply.

BS1-4: BS1 is population frequency. If the variant is not present in gnomAD, that might be a BS1. But if it's a rare variant, absence might not be a strong argument. However, since it's not in ClinVar or HGMD, that could be a BS1. BS2 is in silico prediction. Since CADD and REVEL are low, that would support BS2. BS3 is functional studies, which are N/A. BS4 is other evidence, which is not applicable.

BP1-7: BP1 is population frequency. If the variant is not in gnomAD, that might be a BP1. But again, the absence could be due to low frequency. BP2 is in silico prediction. Since the predictions are low, that would support BP2. BP3 is functional studies, which are N/A. BP4 is other evidence, which is not applicable. BP5 is de novo, which is N/A. BP6 is segregation, which is N/A. BP7 is other evidence, which is not applicable.

Now, considering ClinGen SVI recommendations for PS3/BS3 and PVS1. Since the variant is missense, PVS1 doesn't apply. For PS3, since there's no functional data, it's not applicable. For BS3, if the variant is not in ClinVar or HGMD, that might be a BS3. However, the user mentioned ClinVar has conflicting classifications, which complicates things.

Putting it all together: The main points are the absence in population databases (PM1/PP4/BS1), conflicting ClinVar classifications (BS3), and low in silico predictions (BS2). However, the lack of functional data and segregation data makes it hard to confirm pathogenicity. The conflicting classifications in ClinVar might indicate uncertainty. Since there's no strong evidence for pathogenicity (like segregation or functional studies), and the in silico predictions are not strong, the variant might be classified as VUS. But the absence in population databases could be a PM1, but without more data, it's uncertain. The conflicting ClinVar might suggest that some experts think it's pathogenic, but others don't. So the final classification might be VUS with low confidence.
</think>

### **BRCA2 c.9302T>C (p.Leu3101Pro) 변이 해석 (ACMG/AMP 2015 기준 및 ClinGen SVI 권고안 적용)**

---

#### **1. 변이 정보 요약**
- **유전자**: BRCA2  
- **변이**: NM_000059.4:c.9302T>C (NP_000050.3:p.Leu3101Pro)  
- **유형**: Missense  
- **기능 영향**: Leucine (hydrophobic) → Proline (helix-breaker)  
- **집단 데이터**: gnomAD AF (전체/인종 최대) = None, 동형접합 = None  
- **데이터베이스**: ClinVar = Conflicting_classifications_of_pathogenicity, HGMD = Not available  
- **전산 예측**: CADD = 0.998 (낮음), REVEL = 0.788 (낮음), SpliceAI = N/A, phyloP = N/A  
- **기능 연구**: In vitro/in vivo = N/A  
- **가계 분리/De novo**: N/A  

---

#### **2. ACMG/AMP 2015 기준 평가**

| **기준** | **충족 여부** | **근거 및 설명** |
|----------|----------------|------------------|
| **PVS1** | ❌ | **Loss-of-function (LOF)** 변이가 아니므로 적용 불가. BRCA2는 LOF 기전이 알려진 유전자이지만, 이 변이는 missense로 LOF 기전을 직접적으로 지원하지 않음. |
| **PS1** | ❌ | 질병 관련 집단에서의 빈도 증거 없음 (gnomAD AF = None, ClinVar = Conflicting). |
| **PS2** | ❌ | 가계 분리 데이터 없음. |
| **PS3** | ❌ | 기능 연구 데이터 없음 (in vitro/in vivo = N/A). |
| **PS4** | ⚠️ | **Population frequency**: gnomAD AF = None → **PM1** (Population frequency) 기준에 해당. 하지만 "None"은 데이터 부재일 수 있으므로 **PS4**는 적용 불가. **PM1**은 적용 가능 (변이가 일반 인구에서 관찰되지 않음). |
| **PM1** | ✅ | **Population frequency**: gnomAD AF = None → **PM1** (Population frequency) 충족. |
| **PM2** | ❌ | **In silico prediction**: CADD (0.998), REVEL (0.788) → **낮은 예측 강도** (CADD < 10, REVEL < 0.75). **PM2** (In silico prediction) 충족 불가. |
| **PM3** | ❌ | 기능 연구 데이터 없음. |
| **PM4** | ❌ | 가계 분리 데이터 없음. |
| **PM5** | ❌ | De novo 데이터 없음. |
| **PM6** | ❌ | 기타 증거 없음. |
| **PP1** | ❌ | 가계 분리 데이터 없음. |
| **PP2** | ❌ | De novo 데이터 없음. |
| **PP3** | ❌ | 기능 연구 데이터 없음. |
| **PP4** | ⚠️ | **Population frequency**: gnomAD AF = None → **PP4** (Population frequency) 기준에 해당. 하지만 "None"은 데이터 부재일 수 있으므로 **PP4**는 적용 불가. **PM1**과 동일한 근거로 **PP4**는 부적절. |
| **PP5** | ❌ | 기타 증거 없음. |
| **BA1** | ❌ | LOF 기전이 아닌 missense 변이이므로 적용 불가. |
| **BS1** | ⚠️ | **Population frequency**: gnomAD AF = None → **BS1** (Population frequency) 기준에 해당. 하지만 "None"은 데이터 부재일 수 있으므로 **BS1**은 부적절. **PM1**과 동일한 근거로 **BS1**은 부적절. |
| **BS2** | ✅ | **In silico prediction**: CADD (0.998), REVEL (0.788) → **낮은 예측 강도** (CADD < 10, REVEL < 0.75) → **BS2** (In silico prediction) 충족. |
| **BS3** | ✅ | **ClinVar**: Conflicting_classifications_of_pathogenicity → **BS3** (Conflicting interpretations in ClinVar) 충족. |
| **BS4** | ❌ | 기타 증거 없음. |
| **BP1** | ⚠️ | **Population frequency**: gnomAD AF = None → **BP1** (Population frequency) 기준에 해당. 하지만 "None"은 데이터 부재일 수 있으므로 **BP1**은 부적절. **PM1**과 동일한 근거로 **BP1**은 부적절. |
| **BP2** | ✅ | **In silico prediction**: CADD (0.998), REVEL (0.788) → **낮은 예측 강도** (CADD < 10, REVEL < 0.75) → **BP2** (In silico prediction) 충족. |
| **BP3** | ❌ | 기능 연구 데이터 없음. |
| **BP4** | ❌ | 기타 증거 없음. |
| **BP5** | ❌ | De novo 데이터 없음. |
| **BP6** | ❌ | 가계 분리 데이터 없음. |
| **BP7** | ❌ | 기타 증거 없음. |

---

#### **3. ClinGen SVI 권고안 적용**
- **PS3/BS3**: 기능 연구 데이터 없음 → **PS3/BS3** 적용 불가.  
- **PVS1 강도 조절**: PVS1 적용 불가 (missense 변이).  

---

#### **4. 최종 분류 및 신뢰도 평가**
- **Pathogenicity Evidence**:  
  - **PM1** (Population frequency) → **Weak support** (gnomAD AF = None).  
  - **BS2** (In silico prediction) → **Strong evidence against pathogenicity** (CADD/REVEL 낮음).  
  - **BS3** (ClinVar Conflicting) → **Moderate evidence against pathogenicity**.  
  - **BP2** (In silico prediction) → **Strong evidence against pathogenicity**.  

- **Pathogenicity Likelihood**:  
  - **PM1** (Weak support) + **BS2/BS3/BP2** (Strong evidence against) → **No strong evidence for pathogenicity**.  
  - **ClinVar Conflicting** → **Uncertainty in classification**.  

- **최종 분류**: **VUS (Variants of Uncertain Significance)**  
  - **신뢰도**: **Low confidence** (부족한 증거로 인해 분류 불확실).  
  - **임상적 해석**:  
    - BRCA2는 유방암/난소암과 관련된 중요한 유전자이지만, 이 변이는 missense로 기능적 영향이 불확실.  
    - gnomAD에서 관찰되지 않음 (PM1)은 pathogenicity를 약간 지원하지만, in silico 예측 (BS2/BP2)과 ClinVar의 Conflicting 분류 (BS3)는 pathogenicity를 강하게 반박.  
    - 추가 연구 (기능적 분석, 가계 분리, 대규모 집단 데이터)가 필요.  

---

#### **5. 결론**
- **분류**: **VUS (Variants of Uncertain Significance)**  
- **신뢰도**: **Low confidence**  
- **추천**:  
  - **기능적 분석** (in vitro/in vivo) 수행.  
  - **가계 분리 연구** 또는 **대규모 집단 데이터** (exome/genome sequencing) 추가 분석.  
  - **ClinVar**에 추가 분류 요청 또는 **HGMD** 등 다른 데이터베이스에서의 확인 필요.  

--- 

**참고**: 이 해석은 ACMG/AMP 2015 기준과 ClinGen SVI 권고안을 기반으로 하며, 추가 증거가 있을 경우 재평가가 필요합니다.