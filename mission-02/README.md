해당 HTML 구성은
우선 그림자 영역(shadow)와 그 안에 있는 main(orange_box)가 중심입니다

    shadow
    (position:relative를 주고 top과 left 속성을 이용하여  css에서 구현)
    (position:relative는 굳이 주지 않아도 구현에 문제는 없으나, relative없이 static상태이면 좌측상단에 붙게되어 보기에 좋지않음.)

    orange_box
    (linear-gradient를 통해 배경의 그라데이션 색을 표현
    position:relative, top, left를 통해 shadow를 구현)


main(orange_box)안에는
login - 로그인 글자를 출력
main_box - 흰 색 박스를 출력
하는 span과 div로 구성되어있습니다.

    main_box
    ()
    
    login
    (position:relative를 통해 위치 설정)


main_box 는
upper_box와 lower_box로 나눠져있으며
해당 구분은 흰 박스 안의 회색 선으로 구분됩니다.

    upper_box
    (css에는 해당 내용 없음
    편한 구분을 위해 설정해 둔 class)

    lower_box
    (relative를 주고 left로 위치 설정)


upper_box는 로그인form을 내재하고있기 때문에
fieldset으로 1차적으로 묶어주었으며,
filedset의 서식을 지우기위해 fornone이라는 class의 css로 서식을 제거했습니다.

    fornone
    (border,margin,padding을 모두 없애줌으로써 서식 삭제
    upper과 lower box 구분을 위해
    border-bottom 삽입
    relative속성 주고 left로 위치 설정)


upper_box는 IDandPW 와 login_button 으로 구분되어있습니다.
이름처럼 IDandPW는 ID와 PW를 입력하는 칸을 위한 공간이며
login_button은 로그인 버튼을 위한 공간입니다.

    IDandPW
    (float로 왼쪽으로 이동)

    login_button
    (float로 오른쪽으로 이동
    padding과 border 없애줌
    )

IDandPW는 bowforID와 boxforPW로 구분되어있으며
각 box는 text와 box를 위한 공간으로 구분되어있습니다

![login](https://github.com/Imeanstar/home-work/assets/81348938/f1c17365-d9af-44a1-bdc2-28c7d92b7c5c)