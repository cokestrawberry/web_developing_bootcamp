# web_developing_bootcamp

--- Udemy에서 <100 Days Web Developing Bootcamp Challenge> 강의를 들으면서 진행 결과를 기록하기 위한 문서 ---

2023/01/13

  - 처음 시작하자 마자 git으로 버전 관리를 진행하려고 했는데 git & github 사용법을 익히느라 좀 늦었다.
  - 그러고 나서도 다음달 여행가는거랑 기타 등등 때문에 공부에 신경으 못써서 며칠 더 낭비함
  - 컴활 1급 실기랑 같이 건들고 있는 중이라 솔직히 매일 할 수 있을지는 모르겠지만 잔디밭 관리를 위해서라면 듣고있는 강의가 하나씩 지날때마다 커밋&푸쉬 하면 괜찮을지도..?
  - 일단 오늘은 며칠 밀린거 한번에 들어서 & 알바 면접 전에 시간이 좀 남아서 진행 내용이 많을 듯...


  *** 기억할 내용 ***

  - anchor 요소 스타일링 (마우스 반응 같은거)
  - void 요소 구문 (css 요소 외부 파일화 하기 & link 연결하기)
  - ID 선택자로 선택한 특정 요소들에만 연결하는 방식의 css 코드 적용
  - font 설정
  - Google font 받아와서 내 웹페이지에 적용하기
  - 내 웹페이지에 이미지 추가하기
  - 이미지 스타일링 하기
  - 배경색 / 여백 지정

2023/01/17

  - 또 한동안 개발 공부는 안건드려서 안되겠다 싶어서 카공
  - 부트캠프 과정 중 처음으로 과제 진행(상호 링크 페이지)
  - 강의를 올린 웅진쪽에서 매일매일 수강 이벤트를 하는데, 기간안에 완강 하려면 하루에 3일치 씩은 들어야 할 것 같음
  - 그래봤자 3시간이라 무리는 아닌데.. 중요한건 마음이 꺾이지 않는것..!
  - 작심 하루를 365번 하면 작심 1년이 된다는 생각


  *** 기억할 내용 ***

  - 공유 css 파일
  - 이미지와 css에 대해 각각의 폴더 생성 후 각 폴더별로 소스파일 정리
  - 리스트
  - 부모-자식 관계 & 상속
  - css 상속 모델
    - 상속 (inheritance)
    - 계단식 모델 (css stands for "Casacading" Style Sheets)
    - 우선순위 (ordered with specificity)
  - css 박스 모델
    - 내용 (contents)
    - 테두리 (border)
    - 패딩 (padding)
    - 여백 (margin)
  - html 레이아웃
    - header
    - main
    - footer

2023/01/18

  - 매일 수강 이벤트 2일차
  - 또 사자 메타를 하다가(밀림의 왕 이라는 뜻) 부랴부랴 오늘차 강의를 듣기 시작함
  - 아무렴 어떠냐 해내면 그만이지
  - 오늘은 갱신된 내용을 한번에 커밋했더니 깃허브 잔디밭이 영 푸르지가 않다..
  - '이 맛에 잔디밭 가꾸는구나!'라는 깨달음

  *** 기억할 내용 ***

  - 선택자 & 결합자
    - 선택자
      - Type (h1, p, ...) : element_name
      - ID : #id
      - Group : element_name,element_name
      - Class : .class_name
    - 결합자
      - descendant -> li p -> all p with li as ancestor
      - child -> h2 > p -> only p which are direct child of h2
    - 클래스
      - 요소들을 묶어서 별명(?) 같은걸 부여하는 듯?
      - 그럼 그룹이랑 무슨 차이지..?
        - 그룹은 그냥 여러가지 선택자들을 같이 쓰는거였음 ㅋㅋ
      - 클래스는 ID랑 비교해야 하는데
        ID가 해당 id를 부여받은 한 가지 요소에 적용되는 것이라면,
        클래스는 해당 클래스에 소속된 모든 요소들에 적용됨
  - 블록(레벨) 요소 & 인라인 요소
    - 두 h1 요소
      - 서로 다른줄에 나타남 (자동 행 갈이)
    - 두 anchor (ex : a, img, button, span, ...) 요소
      - 같은 줄에 연결 되어서 나타남
      - 차이가 무엇일까?
    - 블록 요소와 인라인 요소의 차이점
      - 블록 요소는 웹페이지의 모든 너비를 모두 사용함
        - 따라서 각각의 요소마다 다른 줄에 존재함
      - 인라인 요소는 지역적으로 존재 가능
        - 이름 그대로 블록 요소의 한 라인 안에 존재 <- 블록 요소의 text(contents)처럼 취급됨

2023/01/19

  - 매일 수강 이벤트 3일차
  - 별개의 txt파일로 부트캠프 기록을 남기다가 굳이? 하는 마음에 README파일에 합쳐버렸다
  - 매일 매일 작심 1일 중이기는 한데, 그 결심의 범위가 줄어드는 느낌이랄까?(강의 3시간씩 듣자 --> 1시간이라도 듣자)
  - 그래도 일단은 2월 1일 ~ 2월 8일 체코 여행 다녀오기 전까지는 '꾸준히'에 방점을 두고 해야겠다

  *** 기억할 내용 ***

  - 마진 상쇄
    - '수직으로 연결된' 두 요소 사이의 여백(margin) --> 둘 중에서 큰 값으로 설정됨(수평 방향은 두 여백의 합으로 설정됨)
    - 테두리(border)을 기준으로
      - 바깥 부분의 인접 허용치(with other elements) : 여백(margin)
      - 안쪽 부분의 인접 허용치(with own element's region) : 패딩(padding)
    - 약간 피하지방(=margin)과 내장지방(=padding) 같은거라고 이해하면 될듯함
  - "box-shadow"속성
    - box-shadow: x축 오프셋 / y축 오프셋 / 그림자 흐림 정도 / 그림자 색상(rgba - r값 / g값 / b값 / 흐림 정도)
  - span 요소
  - 음수 여백
    - 여러 요소가 겹쳤을때 교통 정리 하는번
      - 겹쳐진 요소들 position 정하기
        - relative로 해놓은 코드를 봐서 따라하긴 했는데 이건 경우에 따라 다를수도 있을 것 같다
        - z-index를 위로 올라오는 요소는 큰 값으로, 밑으로 깔리는 요소는 작은 값으로 설정하면 된다

2023/01/20

  - 매일 수강 이벤트 4일차
  - 사실 오늘은 저녁약속이 있어서 수강 못할 듯 했는데 시간이 미뤄져서 한시간이라도 듣고 가기로 결심
  - 설 연휴 동안에도 꾸준히 해야지
  - 오늘 공부하는 내용은 이전에 배운 내용을 토대로 복습 겸 새 프로젝트 만들기라서 나는 기존에 쌓아놓은 결과물 다듬는 방향으로 진행 할 예정
    - 왜냐면 애초에 배운 기능을 바탕으로 독자적 내용으로 만들어 나가는 중이었기 때문 ㅋㅋ

  *** 기억할 내용 ***

  - 시멘틱 웹
    - 여러가지 강조표시(with css)는 시각장애인이나 robot들에게는 무의미하다
      - em / strong 과 같은 요소들의 사용
    - em : 문장 내에서 특정 문맥을 강조
    - strong : 중요성, 긴급성, 심각성을 강조할때 사용(이 때문에 em보다 더 강한 강조를 의미)
  - section 요소
    - 구조의 명확성을 파악하기 위해 사용
    - 이미 head, body등으로 구분되어 있지만 이는 구조적 기준이기에 그 안에 혼재되어 있는 기능들은 구분하기 어려움
    - 이때 section 요소를 사용하여 특정 동작을 담당하는 부분끼리 나누어 줄 수 있음

2023/01/21

  - 열받아 죽을거 같은 날이지만 할일은 해야지

  *** 기억할 내용 ***

  - 호스팅 & 배포
    - 외부 머신(서버)로 파일을 '배포'하면, 외부 머신이 방문자들에게 파일을 '호스팅'함
    - 즉, 웹사이트가 외부 방문자에게 보여지려면 '배포'되어 '호스팅'되어야 함
    - netlify를 이용해 체험해보기
  - https를 이용해 보안 연결
  - 파비콘
    - 16x16 사이즈의 작은 대표이미지
    - 탭에서 페이지 이름 옆에 표시됨
  - 상대경로 / 절대경로
    - 상대경로는 '현재 위치' 기준
    - 절대경로는 root파일 기준
  - Git과 GitHub를 이용한 버전제어
    - (이건 이미 하고 있는 내용이라 생략)

  2023/01/22

    - 이거 듣는거 까먹었다가 생각나서 부랴부랴 강의 듣기 시작
    - 새로운 세부 프로젝트 시작해서 재분류함
    - 새로운 웹사이트는 여행 기록을 담을 예정(마침 2월에 체코도 가니까...)
    - 일단 오늘은 헤더 위주로 작성함

    *** 기억할 내용 ***

    - 배경 그림과 작업하기
    - flexbox와 그리드 이해하기
    - '단위'들에 대한 이해
    - 랜딩 페이지 구조
      - 헤더 / 메인 / 푸터 의 구분
        - 헤더에는 주로 '네비게이터'를 포함하여 구성
        - 메인에는 주로 페이지를 구성하는 내용들 포함됨
          - 그 안에서는 섹션으로 구분
        - 푸터에는 주로 잉여 정보(저작권 정보/연락망 등) 포함됨

<br>
<br>
<br>

  --- 잠깐 개발과 상관없는 개인적인 일기 ---

  2023/01/25

    - 뭔가 짜게 식었는지 의욕이 뚝 떨어져서 오늘 포함 3일정도 아무것도 안했다
    - 어제와 엇그제는 그래도 컴활 실기 준비라도 조금 했지만 오늘은 진짜 아무것도 안함
    - 정작 설 당일까지도 조금이나 열심히 들었는데 그 다음날부터 푹 퍼져버렸다
    - 왜 갑자기 의욕이 뚝 떨어진건지... 번아웃이라기에는 별로 한건 없어서... 그냥 작심N일 약효가 약해지는 순간이었나 싶다
    - 알바 면접 본곳도 떨어지고
    - 그냥 다음주에 체코 여행 가는거나 빨리 갔으면 좋겠다는 생각이 든다
    - 그리고 그 전에 급 번개로 국내 여행 한군데 가고싶기도 하네
    - 사실 매일 수강 챌린지야 채찍질을 위한 수단으로 도전했던지라 어찌되었든 완강하는게 더 중요하긴 하다
    - 오늘 복학신청 하다가 문제가 생겨서 내일 다시 해야되는데(2023/01/26 00:18 현재 다시 시도 후 성공)
    - 내일 일찍 일어나서 어디 한번 다녀올까

  2023/01/27

    - 위에 저렇게 써 놓은 대로, 26일날 일어나자마자 분리수거 후 ktx를 끊어서 대전에 당일치기로 놀러갔다 옴
    - 대전에 뭐가 있길래? 싶을 수 있지만 꽤 괜찮은 시간이었다
    - 대전 중심가 말고 소제동과 대동 이라고 대전역 근처 동네들을 구경했는데, 서울의 문래동 & 을지로를 보는듯 한 느낌이었다 (+ 집 근처 개미마을)
    - 고양이들이 많아서 좋았음 (나중에 알고보니 재개발 지역이라 길냥이가 많다고 함)
    - 당일날 아침에 눈이 많이 왔는데 대전은 안오나? 라고 생각한 순간 대전에도 눈이 엄청나게 오기 시작했다
    - 점심에 태평소국밥 먹을랬는데 유성온천쪽 까지 가야되서 그냥 근처에 평점 높은 돈가스집에 갔는데, 여기 완전 맛집이었다
    - 요즘 fancy하고 고급 느낌나는 그런 집이 아니라 동네 음식점 같은 분위기였는데, 바삭바삭하고 육즙 가득하고 소스도 맛있고 가격도 저렴했다 (등심,치즈,생선,해쉬브라운,쫄면까지 해서 11,000원)
    - 그렇게 여기서 점심을 먹고 대전의 필수코스인 성심당에 갔다
    - 무슨 강남 클럽처럼 사람들이 줄을 서서 빵을 고르고 있는데, 내가 갔을땐 품절된 빵들도 있었고 (물어보니 새로 나오기까지 두 시간 정도 걸린다고 했다), 결국 맛있어 보이는 한두개만 집어들고 집에 사갈건 다른 지점에서 사야겠다 생각했다
    - 성심당의 도시 답게 근처에 제과 전문 성심당 등등이 있는데, 성심당 문화원? 이라고 카페 겸 문화공간으로 운영하는 곳이 있어서 그곳에서 커피와 함께 빵을 먹었다
    - 역시 빵은 맛있었고, 좀 쉬면서 찍은 사진을 정리하다가 다시 대전역으로 돌아가는 길에 성심당 부띠끄 라고 제과 전문 성심당에서 구움과자 세트와 성심당 대전역점에서 튀소 같은 빵들을 사서 서울로 돌아왔다
    - 또 가고싶다 까지는 아닌데, 그래도 이런식으로 한번 가보기에는 좋았던 것 같다
    - 다음에 이렇게 갑자기 떠나고 싶을때에는 목포를 가봐야겠다 (기차 안에서 ktx잡지를 봤는데 내가 본 issue의 주제가 목포 여행이었음)
    - 어제 오늘 해서 복학 신청도 끝났으니, 내일부터는 체코 가기 전까지 다시 달려봐야지

<br>
<br>
<br>

  2023/01/28

    - 오늘부터는 다시 열심히 해보자구

    *** 진행한 내용 ***

    - 당분간은 프로젝트(여행 기록 페이지 만들기) 진행중이라 새롭게 배우는 내용은 많지 않아서 새롭게 배워 기억할 내용 대신 프로젝트 진행 내역을 위주로 기록할 예정
    - 프로젝트에 flex-box 추가함
    - 배경 이미지 추가
    - 중심 컨텐츠 포지셔닝을 위한 컨테이너 생성
    - 포지셔닝 (이전에 조금 공부해서 위에 정리해놓은 z-position 같은거)
      - static
      - relative
      - absolute (문서 흐름 무시 -> relative로 설정된 최상위 레벨에 상대적 위치)
      - fixed (view-port에 대해 특정 위치에 고정 -> relative to view-port)
      - 문서 흐름
    - % 단위 작업 (부모 요소에 상대적)
      - box-sizing
  
  2023/01/30

    - 어제는 외할아버지/외할머니 같이 식사하러 가느라 못함
    - 출국 2일전이지만 오늘도 한다
    - 현재 하는 프로젝트가 여행에 관한 내용이기 때문에 여행 다녀와서 그 기록으로 만들거라 세부 컨텐츠는 잠시 보류

    *** 진행한 내용 ***

    - 플렉스 컨테이너 구축
    - 플렉스 항목 레이아웃    
    - 첨부될 이미지 크기 사전 조정
      - 강의에 나온대로 너비를 조정했지만 제대로 진행되지 않음 (flex로 설정된 ul의 li속 img 요소 너비를 100%로 설정해도 여백이 남아있음)
      - 그래서 여러가지를 시도해본 결과, 해당 요소의 너비를 100%를 조정하는 것은, 각각에게 배정된 flex요소의 너비중 몇 %를 사용하는지에 대한 설정인것 같았음
      - 생각해보면 오히려 강의 영상이 이상한 것이 img요소의 상위 개체는 li이지 ul이 아니므로, ul에 할당된 너비 기준으로 비율이 정해지지 않는 것이 당연하다
      - 그래서 img가 아닌 li요소의 너비를 100%로 설정하니 의도한대로 ul에게 할당된 너비를 기준으로 하위 요소들의 너비를 지정하게 되었음
        - 강의에 추가 첨부 내용이 있기에 확인하니, justify-content 특성이 빠져있었다고 한다.
        - 위의 내용을 롤백하고 해당 특성을 적용시키니, 의도한 모습으로 요소들이 출력되었다
    - 이미지 동윌 레벨에 위치시키기
      - flex 요소 사용
    - 이미지 간 간격 설정
    - object-fit 특성을 사용하여 이미지의 왜곡 제거
    - css로 선형 그라디언트 적용하기
      - 각도 (사분면에서 -y 기준 반시계)
      - 색상
    - footer에 소셜미디어 링크 아이콘 추가

  2023/02/11

    - 유럽에서 돌아온 후 다시 시작

    *** 진행한 내용 ***

    - places.html 기본 구조 만들기
    - 카드 룩 구조
      - 카드 컨텐츠 만들기
      - 적용할 css 구조 만들기
      - "포지션: 정적" 사용
    - 오버플로우 이해하기

  2023/03/12
  
    - 컴활 실기 시험 보고 복귀
    - 한달동안 직접적인 개발이나 커밋은 멈춰있었지만 다시 시작한다
    - 근데 3년만의 복학이라 학교 공부도 해야되서 예전처럼 매일 하기는 힘들듯...
    - 하지만 중요한건 꺽이지 않는 마음
    - 꾸준히 해서 끝낸다
