### 💾 Exporting tables using HeidiSQL

---

- CSV 파일을 import 했던 것처럼 export도 가능하다
- JSON, CSV, SQL 등 다양한 형식으로 저장할 수 있다
- 단, 한 번에 최대 `1,000`건만 저장 가능하다
- 해당하는 테이블의 [데이터] 클릭 --> 오른쪽 버튼 눌러 [격자 행 내보내기] 클릭
  - 파일 경로 지정
  - 출력 형식 지정
  - 행 선택(선택한 한개의 행만 저장할지, 1,000개 꽉 채워 저장할지 선택)
  - 필드 구분자 혹은 종결자는 건들지 말고 놔두는것이 좋다
  - CSV 파일로 해당 경로에 잘 저장된 것을 알 수 있다
  - encoding 방식도 설정 가능하다

![111](https://user-images.githubusercontent.com/69948723/106982511-97dd6380-67a7-11eb-9ffa-f338f4f76e8a.png)



- 데이터 row 수가 많지 않을 경우, 빠르게 export 할 수 있는 방법 중 하나인 듯 하다
- 나같이 권한 문제로 INFILE 혹은 OUTFILE을 쓸 수 없는 사람에게 좋은 방법 ✨
- `MySQL Workbench`로도 export가 가능하다는데, 그건 1,000건 이상 될지 시도해봐야겠다