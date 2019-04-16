#우아한 테크코스 오프라인 코딩테스트 영화예매

## 프로젝트 설명 
* 영화를 예매하고 결과를 보여주는 프로그램을 작성한다.

## 사용 예시

    상영영화목록 1-생일,8000원
    시작시간:2019-04-1612:00 예약가능인원:6
    시작시간:2019-04-1614:40 예약가능인원:6
    … 
    5-돈,10000원
    시작시간:2019-04-1608:00 예약가능인원:3
    시작시간:2019-04-1610:30 예약가능인원:5
    …
    7-파이브피트,9000원 
    시작시간:2019-04-1613: : 예약가능인뤈:4 
    시작시간:2019-04-1615:40 예약가능인원:4 
    …
    8-덤보,9000원
    시작시간:2019-04-1611:30 예약가능인원:2
    시작시간:2019-04-1616:00예약가능인원:3
     
    예약할영화를선택하세요. 
    1 
    1-생일,8000원 
    시작시간:2019-04-1612:00예약가능인원:6
    시작시간:2019-04-1614:40예약가능인원:6 
    시작시간:2019-04-1617:00예약가능인원:6 
    시작시간:2019-04-1619:40예약가능인원:3 
    시작시간:2019-04-1622:00예약가능인원:3
    
    예약할시간표를선택하세요.(첫번째상영시간이1번)
    2
    예약할인원을입력하세요.
    2
    예약을종료하고결제를진행하려면1번,추가예약을진행하려면2번
    1
    예약내역 1-생일,8000원 시작시간:2019-04-1614:40 예약인원:2명
    결제를진행합니다. 
    ##포인트사용금액을입력하세요.포인트가없으면0입력 
    1000
    신용카드는1번,현금은2번
    1
    최종결제한금액은14250원입니다.
    예매를완료했습니다.즐거운영화관람되세요.
    
## 기능 목록 

* 상영하고 있는 영화 목록의 데이터를 받아온다.

* 상영하고 있는 영화 목록의 데이터를 출력한다.

* 예약할 영화에 대한 정보를 사용자에게 입력받는다.<br/>
 -예외 : 예약할 영화의 수는 1~영화의 수 만큼 입력받아야 하며 여러 영화를 입력받을 때 각 영화의 시간차이가 
 1시간 이상이 나게 되면 안된다.
 
* 해당 예매한 영화의 영화 정보를 출력한다.
 
 * 예약할 시간표를 입력받는다. <br/>
 -예외 : 예약할 시간표도 1~시간표의 수만큼 입력받아야 한다.
 
 * 예약할 인원을 입력받는다. <br/>
 -예외 : 예약할 인원도 해당영화의 남은 자리수 만큼 입력받아야 한다.
 
 * 결제 진행 메세지를 입력받는다. <br/>
 -예외 : 1,2 가아니면 모두 예외이다.
 
 * 예약 내역을 출력합니다.
 
 * 포인트 사용금액을 입력받는다. <br/>
 예외 : 포인트 사용금액이 영화의 가격을 초과하면 예외이다.
 
 * 신용카드, 현금 결제수단을 입력받는다. <br/>
 예외 : 1,2 가 아니면 모두 예외이다.
 
 * 최종결제 금액 메세지를 출력한다.
    