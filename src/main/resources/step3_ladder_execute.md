### 기능 수정사항
- 사다리 실행 결과를 출력해야 한다.
- 개인별 이름을 입력하면 개인별 결과를 출력하고, "all"을 입력하면 전체 참여자의 실행 결과를 출력한다.
### TODO
-[x] 실행 결과를 입력하세요. (결과는 쉼표(,)로 구분하세요) / 결과를 보고 싶은 사람은?
  - InputView
-[x] 결과를 출력한다. 
  - OutputView
  
-[x] 위치를 정의한다
  - Position <br>
  - x축 오른쪽 이동하면 +1 왼쪽이동하면 -1 그대로면 0
  - y축 +1
  - 예) 최대길이3,참여자수4인경우 <br>
    [0,0] [1,0] [2,0] [3,0]<br>
    [0,1] [1,1] [2,1] [3,1]<br>
    [0,2] [1,2] [2,2] [3,2]<br>
    [0,3] [1,3] [2,3] [3,3]<br>
<br>  
-[x] Participant 참여자 a,b,c,d 생성시 position 지정하는 기능을 추가한다
  - a 참여자는 0,0 에 있다.
  - b 참여자는 1,0 에 있다.
  - c 참여자는 2,0 에 있다.
  - d 참여자는 3,0 에 있다.
  
- [x] 사다리 라인 이동을 위해 해당 포인트에 라인이 있는지 없는지 체크한다
  - Point

- [x] 해당 위치에서 왼쪽/오른쪽/pass 로 이동한 위치를 구하기위한 방향을 정의한다 
  - Direction

-[x] 입력한 결과값을 저장한다. 최대길이~참여자수 
  - ExecuteResult  
-[x] 입력한결과와 사다리결과를 조합하여 참여자의 결과 값을 업데이트한다
  - LadderResult

