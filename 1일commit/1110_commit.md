# 11/10 **커밋 내용**

---

## 11/10 목**요일**

40번째 커밋

kaggle : 데이터 엔지니어들의 놀이터, 필수적인 웹사이트

data_f = pd.read_csv(’../input/plant-diary/plant_diary.csv’) → csv파일 읽어오기

plot(data_f, ‘날짜’, ‘잎 너비’, ‘주인’) // 날짜를 x축으로, 잎너비를 y축으로 plot 해라, 주인은 다른 색으로 칠해라

violinplot(data_f, 'owner', 'leaf_length') 바이올린 모양으로 plot해라, data_f를 가지고 x축을 owner, y축을 leaf_length로 해라

전체데이터를 나눠서 담는다 split()

predict() → 예측한다.