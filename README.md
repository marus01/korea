# 소개
KoELCTRA_base_v3 기반의 한글 감정 분석과 BERT 영어 감정 분석입니다. 
최종 제출본과 Trials 데이터를 포함하고 있습니다.
Trials 버전은 파일명 앞에 Trial 이라고 표기되어 있습니다. 
하위 폴더 생성이 잘안되서 부득이하고 같은 폴더에 올렸습니다. 
한글버전은 3개 모델을 구현하였으며
영어버전은 1개 모델을 구현하였습니다. 



# 실행 환경
1.최종 제출물인 PDW_NSMC_KoELECTRA_base_v3의 경우 그냥 실행하시면 됩니다.
(base v2 모델도 동일하게 그냥 실행하며 됨)


2.PDW_NSMC_bert의 경우 ko_data.csv로 최종 테스트 하였기에 하단의 실행법 참고
1)코랩과 구글 드라이브를 마운트합니다.
2)마운트 된 구글드라이브에 ko_data.csv 파일 삽입합니다.
3)테스트 결과 파일을 csv로 import 하기 위해 구글 드라이브에 경로 및 파일명을 설정합니다. 
실행하시면 됩니다. 

3. PDW_friends_eng__bert의 경우 en_data.csv로 최종 테스트 하였기에 하단의 실행법 참고
1)코랩과 구글 드라이브를 마운트합니다.
2)마운트 된 구글드라이브에 EmotionLines_friends_annotation.tar.gz 파일 삽입합니다.
3)마운트 된 구글드라이브에 en_data.csv 파일 삽입합니다.
테스트 결과 파일을 csv로 import 하기 위해 구글 드라이브에 경로 및 파일명을 설정합니다.

실행하시면 됩니다.
# 참고 소스 코드
https://github.com/deepseasw/bert-naver-movie-review

https://github.com/monologg/KoELECTRA

# 코랩
https://colab.research.google.com/drive/1Sr7NT4bZxyPVFvHVTZs-kw6P8GTbBV-i
