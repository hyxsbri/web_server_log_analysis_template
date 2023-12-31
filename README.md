# **웹 서버 로그 파일 분석 템플릿**

## Project Outline


> ### 수행 기간: *23.06.05 ~ 23.06.28*

> ### 활용 데이터셋: *access.log(3.5 GB)*
    하버드 데이터버스로부터 본 데이터를 수집했으며, 이란 전자상거래 사이트(zanbil.ir) 로그가 포함되어 있습니다.
    (Zaker, Farzin, 2019, "Online Shopping Store - Web Server Logs", https://doi.org/10.7910/DVN/3QBYB5,
    Harvard Dataverse, V1)

> ### 작업 환경: *Google Colab*

로그 파일을 parquet(고효율 열지향 포맷) 파일로 변환 및 디스크/ 메모리 사용량 최적화 작업,  
응답 크기별 페이지 클러스터링 / Organic traffic(오가닉 트래픽) 분석 템플릿 구성 작업을 수행했습니다.

#### **※ 노트북 파일 내 시각화 결과물 업로드 오류로 인하여 저장소에 별도 업로드 했습니다(fig_show.png / widgets.png).**
