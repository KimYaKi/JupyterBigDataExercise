Project Name : NewBigDataProject
=============


특성 정리
=============
* MEAN_RR : 모든 RR 간격의 평균 
* MEDIAN_RR : 모든 RR 간격의 중앙값 
* SDRR : 모든 간격의 표준 편차 
* RMSSD : 인접한 RR 간격 간의 차의 제곱의 합 평균의 제곱근 
* SDSD : 인접한 RR 간격 간의 모든 차이 간격의 표준 편차 
* SDRR_RMSSD : SDRR의 비율 
* RMSSD : HR 심박수 (분당 박동수) 
* pNN25 : 인접한 RR 간격의 %가 25ms 이상 차이
* pNN50 : 인접한 RR 간격의 %가 50ms 이상 차이 
* SD1 : 단기 HRV의 푸앵카레 플롯 기술자 
* SD2 : 장기 HRV의 푸앵카레 플롯 기술자 
* 모든 RR 간격의 KURT 첨도
* 모든 RR 간격의 SKEW 비대칭
* MEAN_REL_RR : 모든 상대 RR 간격의 평균 
* MEDIAN_REL_RR : 모든 RR 간격의 중앙값 
* SDRR_REL_RR : 모든 상대 RR 간격의 표준 편차 
* RMSSD_REL_RR : 인접하는 상대 RR 간격의 차의 제곱의 합 평균의 제곱근 
* SDSD_REL_RR : 인접하는 상대 RR 간격 간의 모든 차이 간격의 표준 편차 
* SDRR_RMSSD_REL : RMSSD_REL을 통한 SDRR_REL의 비율 
* KURT_REL_RR : 모든 상대 RR 간격의 첨도 
* SKEW_REL_RR : 모든 상대 RR 간격의 왜곡도 
* VLF : HRV 전력 스펙트럼의 매우 낮은 (0.003Hz - 0.04Hz) 주파수 대역 
* HRV : 파워 스펙트럼의 LF 로우 (0.04Hz - 0.15Hz) 주파수 대역 
* HF : HR 스펙트럼의 HF (0.15Hz - 0.4Hz) 주파수 대역 
* TP : 총 HRV 파워 스펙트럼 
* LF / HF : HF에 대한 LF의 비율 
* HF / LF : HF 대 LF의 비율 
* sampen : RR 신호의 샘플 엔트로피 
* higuci : 히구치 프랙탈 차원

Target Class
=============
* no stress
  > 피실험자는 최대 45 분 동안 필요하다면 작업을 할 수 있지만 최대 작업 시간은 알지 못합니다. 
  
* time_pressure
  > 이 시간 동안 작업을 끝내는 시간은 참가자가 중립 조건을 취한 시간의 2/3로 단축되었습니다.
* interruption
  > 참가자들은 할당 된 작업의 중간에 8 개의 이메일을 받았습니다. 일부 전자 메일은 작업과 관련이 있으며 참가자는 특정 작업을 수행하도록 요청 받았지만 일부 전자 메일은 작업과 관련이 없었습니다.
