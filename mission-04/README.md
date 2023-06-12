이번 과제의 코드는 크게 세 부분으로 나뉜다.<br/>
1. upperbox<br/>
2. middleline<br/>
3. lowerbox 이다<br/>
<br/>
upperbox의 경우 float를 이용하여 "새소식"과 "더보기"를 배치하였다.<br/>
<br/>
middleline의 경우 박스를 얇게 만들고 그라데이션을 주어 시안과 같이 배치하였다.<br/><br/>

lowerbox의 경우 크게 두 상자로 묶었는데,<br/>
좌측 그림이 있는 상자와, 우측 설명이 있는 상자 이다.<br/>
우선 lowerbox에 display:grid를 주어 우선적으로 좌측상자와 우측상자를 배치하였다.<br/>
이후 picture class에서 다시 display:grid를 주어 자식 요소들을 grid로 묶어 주었고, 배치하였다.<br/>
또한 art class에서 display:grid를 주어 자식요소들을 grid로 묶고, 시안의 크기에 맞춰 배치하였다.<br/>
<br/><br/>

--------스크린샷--------<br/>
![image](https://github.com/Imeanstar/home-work/assets/81348938/81e125d5-ec9a-407c-ac8c-e442e298edba)