# Project2_Genomicinfo_classify_species

## 1.	Data set
-	출처 : https://dacon.io/competitions/official/236035/data
-	구성 : 해당 페이지의 Dataset Info. 참고
### Dataset Info.
  -	train.csv [파일]<br/>	
                      id : 개체 고유 ID<br/>
  	                  개체정보<br/>
                        -	father : 개체의 가계 고유 번호 (0 : Unknown)<br/>
                        - mother : 개체의 모계 고유 번호 (0 : Unknown)<br/>
                        - gender : 개체 성별 (0 : Unknown, 1 : female, 2 : male)<br/>
                        - trait : 개체 표현형 정보 <br/>
                        - 15개의 SNP 정보 : SNP_01 ~ SNP_15 <br/>
                        - class : 개체의 품종 (A,B,C) <br/>
  <br/>
  
  -	test.csv [파일]	<br/>
  	                id : 개체 샘플 별 고유 ID <br/>
                    개체정보 <br/>
                      - father : 개체의 가계 고유 번호 (0 : Unknown) <br/>
                      - mother : 개체의 모계 고유 번호 (0 : Unknown) <br/>
                      - gender : 개체 성별 (0 : Unknown, 1 : female, 2 : male) <br/>
                      - trait : 개체 표현형 정보 <br/>
                      - 15개의 SNP 정보 : SNP_01 ~ SNP_15 <br/>
  <br/>
  
  -	snp_info.csv [파일]	15개의 SNP 세부 정보 <br/>
                      - name : SNP 명 <br/>
                      - chrom : 염색체 정보 <br/>
                      - cm : Genetic distance <br/>
                      - pos : 각 마커의 유전체상 위치 정보 <br/>
