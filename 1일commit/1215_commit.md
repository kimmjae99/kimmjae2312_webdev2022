# 12/15 **커밋 내용**

---

## 12/15 목**요일**

60번째 커밋

# 너비 우선 탐색

- 시작 정점에 인접한 정점들을 모두 방문한 뒤에 이 정점들에 인접한 방문 안 한 정점들을 모두 방문
- 이 과정을 시작 정점에 연결된 모든 정점들을 방문할 때까지 계속
- 만약 탐색이 종료된 후에 아직 방문 안 한 정점들이 남아 있다면 그 정점들 중 한 정점에서 너비 우선 탐색을 다시 시작
- 정점들을 시작 정점까지의 최단 경로의 길이 순서대로 방문

```c
BFSearch(G)
//입력: 그래프 G=(V,E)
//출력: 방문하는 순서대로 출력된 정점들
1.V에 있는 각 정점을 '방문 안 함'으로 표시
2.각 정점에 대해 다음을 수행 V가 '방문 안 함'이라면 BFS(V)를 호출

BFS(v)
1.v를 '방문한'으로 표시
2.v를 큐의 끛에 추가
3.큐가 비어있지 않은 동안 다음을 수행
		큐의 맨앞에 있는 정점을 끄집어 내어 Elm에 저장
		Elm의 데이터를 출력
		Elm에 인접한 모든 정점에 대해 다음을 수행
			a. W가 '방문 안 함'이라면 W를 '방문 함'으로 표시
			b. W를 큐의 끝에 추가
```

- 인접 목록 그래프 시간 복잡도: | V | + | E |
- 인접 행렬 그래프 시간 복잡도: | V^2