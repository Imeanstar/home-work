------HTML------<br/>
우선 greybox를 정의해주어 상자를 구성한다<br/>
 &nbsp;   - width : 190px로 정의<br/>
 &nbsp;   - height : whitebox가 늘어남에 따라 커져야 하기 때문에 
    자식요소의 크기를 따라가는 auto로 정의<br/>
 &nbsp;   - background : 그라데이션 적용<br/>
<br/>
<br/>
그 안에 relate_site class로 관련/사이트 글자를 넣어주고 색깔을 설정해 준다<br/>
&nbsp;    - relate_site : 각 글자의 공통된 부분 정의<br/>
 &nbsp;   - relate_site1 : 검정 글자에서 여백 정의<br/>
 &nbsp;   - relate_site2 : 주황 글자 색깔 정의<br/>


whitebox class를 div로 만들어주고,
그 안에 whitebox_inside로 내부 내용(목차)를 ul로 채워준다<br/>
[list]이기 때문<br/>
해당 글자들은 모두 링크 이기 때문에 a형식으로 구성해주고,<br/>
각 글자들을 li 형식으로 구성해준다<br/>
 &nbsp;   - whitebox<br/>
 &nbsp;&nbsp;       + transition으로 height, padding bottom,top 수정<br/>
&nbsp;&nbsp;        + hover 되었을 때 크기 변화 해야 하므로 height 변화<br/>
&nbsp;&nbsp;        + whitebox hover되었을 때 list 변화하게 하는 법 모르겠어서
        padding bottom과 top 수정하는 식으로 적용<br/>
 &nbsp;   - whitebox:hover<br/>
 &nbsp;&nbsp;       + 마우스 올라갔을 때 변해야 하므로 hover 적용<br/>


![김민성_3차과제](https://github.com/Imeanstar/home-work/assets/81348938/8384bff7-a6e6-491f-8857-efe208c78998)