해당 HTML 구성은
우선 그림자 영역(shadow)와 그 안에 있는 main(orange_box)가 중심입니다

main(orange_box)안에는
login - 로그인 글자를 출력
main_box - 흰 색 박스를 출력
하는 span과 div로 구성되어있습니다.

main_box 는
upper_box와 lower_box로 나눠져있으며
해당 구분은 흰 박스 안의 회색 선으로 구분됩니다.

upper_box는 로그인form을 내재하고있기 때문에
fieldset으로 1차적으로 묶어주었으며,
filedset의 서식을 지우기위해 fornone이라는 class의 css로 서식을 제거했습니다.

upper_box는 IDandPW 와 login_button 으로 구분되어있습니다.
이름처럼 IDandPW는 ID와 PW를 입력하는 칸을 위한 공간이며
login_button은 로그인 버튼을 위한 공간입니다.

IDandPW는 bowforID와 boxforPW로 구분되어있으며
각 box는 text와 box를 위한 공간으로 구분되어있습니다