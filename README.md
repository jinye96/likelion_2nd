## 자기소개 페이지 만들기
###완성화면
| ![complete](./images/result1.png)| ![complete](./images/result2.png)|
|--------|--------|
|처음 시작 화면 : index.html|자기 소개를 누른 뒤 화면: intro.html|

### 구현 의도
오버워치가 하고 싶은데 컴퓨터는 꾸리고 피방 갈 시간은 없고 피방 갈 돈도 딱히 없고 밥 먹으면서 오버워치 플레이 경기보다가 오버워치 테마로 내 자기소개 홈페이지 만들면 재밌겠다 싶어서 만들었다.
그리고 하나의 페이지로 만들라고 하셨는데 그냥 페이지 두개짜리로 만들려고 한다.
하나는 게임 실행 화면 같은 자기 소개 들어가는 버튼이 있는 화면 하나, 그리고 다른 하나는 내 소개를 담은 페이지이다.
### 오류 내용 + 해결방법
일단 이미지 자체를 배경 안에 넣는 것에서 그림이 확대되면서 글자 신경쓰기도 힘든데 배경도 같이 왔다갔다해서 굉장히 빡쳤었다.
다행히도 어떤 천사가 익스에서는 안돌아가지만 크롬 사파리 오페라에서는 돌아가는 css 방법을 올려놓은 것이 있어서 그 부분을 참고하였다.(https://knulab.com/archives/1185)
그리고 이제 자기소개 창은 어찌저찌 되었는데, 자꾸 그 아래의 영웅갤러리와 전리품상자 배너 정렬이 굉장히 거슬렸다. 그래서 일단 1차적으로 구글 크롬에서 페이지 소스 검사를 눌러서 하나하나 엘리먼트들의 속성을 조정해주고, inline으로도 해봤다가 세로 정렬이 힘들어서 block으로 했더니 이미지가 너무 간격이 크고.... 뭐 이런 저런 일이 있었는데, 결과적으로는 이미지의 크기를 딱 필요한 만큼 설정해주어서 그 남은 여백을 이용해서 스타일 조정을 했더니 나름 자연스럽게 변했다.

### 간단한 소감
웹페이지 디자인은 언제나 재밌다. 옵치하고싶다
### 참고문서
https://knulab.com/archives/1185
어떤 천사씨의 링크, 이 링크로 나의 자기소개 홈페이지의 첫걸음이 완성되었다.
####  2019년 3월 24일
오늘은 git 입력 경로만 다른 폴더로 바꾸어놓고 자야겠다ㅋㅋㅋ
####  2019년 3월 25일
이미지 작업을 했다. 오버워치로 테마를 잡았는데 만들면서도 너무 행복했다
사실 글 채우는 거 귀찮아서 이미지들로만 작업했다. 글쓰기 싫어..
#### 2019년 3월 26일
배경화면 해상도 때문에 해결하려고 새벽 4시에 잤는데 그 고생이 정말 허무하게도 링크 하나로 해결되었다.
역시 과제는 잠을 자고 일어나서 해야 해...
