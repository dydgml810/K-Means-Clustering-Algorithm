# K-Means-Clustering-Algorithm
K-Means Clustering Algorithm 파이썬 구현

## 1. K_Means_Algorithm_Steps.ipynb
K-Means Clustering 알고리즘의 단계를 나누어 각 단계를 확인하는 코드
1. 데이터 불러오기
2. 데이터 파악
3. 데이터 시각화
4. 클러스터 개수 k 설정 및 k개의 클러스터에 데이터 랜덤하게 할당

> 4.1. 클러스터 개수 k 설정

> 4.2. k개의 클러스터에 데이터 랜덤 할당

5. 각 클러스터의 평균(centroid)를 구하고, 평가값 계산

> 5.1. 각 클러스터의 평균(centroid) 계산

> 5.2. 각 클러스터 안에 있는 모든 데이터에서 평균(centroid)까지의 거리 합 계산

> 5.3. 평가값 산출

6. 모든 데이터를 k개의 평균(centroid) 중에서 가장 가까운 클러스터로 재할당하여 **새로운 클러스터 해 구성**

7. 클러스터 해의 변화가 있는지 확인

> 7.1. 새로운 클러스터의 평균(centroid) 계산

> 7.2. 이전의 centroids와 새로운 centroids 비교

8. 변화가 있다면 6번으로 다시 돌아가서 반복하고, 변화가 없다면 결과값 출력


## 2. K_Means_Clustering_Algorithm.ipynb
K-Means Clustering 알고리즘을 하나의 kmeans함수로 구현

### 사용된 데이터셋
1. Ruspini
2. Iris

<hr/>

* 파일:
  + dataset
    - glass.txt
    - iris.txt
    - ruspini.txt
    - wine.csv
  + K_Means_Algorithm_Steps.ipynb
  + K_Means_Clustering_Algorithm.ipynb
