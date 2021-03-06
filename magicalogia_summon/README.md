## 소개
마도서대전 RPG 마기카로기아를 Roll20에서 ORPG로 진행할 때

채팅창에 명령어를 입력하는 방식으로 원형 토큰을 손쉽게 생성할 수 있도록 도와주는 스크립트입니다.
	
## 사용법
**준비1. 원형 덱 만들기 & 이름 설정**

1. 세션방에서 소환에 사용할 원형들을 Card 덱으로 만듭니다.

2. 카드들의 이름을 `'정령','마검'`등 원형의 이름으로 설정하고 덱의 이름은 `archetype`으로 지정합니다.

   이제 스크립트는 archetype 덱을 원형 타입의 저장소로 인식하고 여기에서 아이콘을 불러옵니다.
	   

**준비2. 스크립트 적용하기**
1. roll20 세션방에서 원형을 사용할 페이지에서 GM레이어를 선택합니다.

2. 세션방의 대문에 해당하는 페이지에서 [설정]->[API 스크립트]를 선택해 스크립트 수정 페이지로 들어갑니다. (PRO 계정에서만 이 메뉴가 보입니다.)

3. New Script에 이 코드들을 복사해 붙여놓고 [Save Script]로 저장합니다.

4. 페이지 아래쪽의 API Output Console에 에러 메시지가 표시되지 않는다면 정상적으로 적용된 것입니다. 세션방에서 테스트를 진행할 수 있습니다.

5. 채팅창에` !소환 <특기명>의 <원형타입> <블록숫자>`의 형식으로 입력해 테스트를 해봅니다. (예: `!소환 정적의 정령 2` )
	
## 옵션
- 원하신다면 스크립트 내의 주석을 참고해 토큰의 위치나 크기, 이름 표시여부를 변경하실 수 있습니다.
- 채팅창에 명령어를 모두 입력하는 것이 불편하다면 매크로를 이용하시는 것도 좋습니다.

  아래의 코드로 매크로를 생성한 뒤 실행하면 원형이름과 블록숫자를 입력하는 팝업이 표시됩니다.

	  !소환 ?{원형이름} ?{블록}
	  매크로를 사용할 것인지 채팅창에 바로 입력할 것인지는 사용자가 편의에 따라 선택하면 됩니다.