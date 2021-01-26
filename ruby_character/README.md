## 소개
Roll20에서 루비 문자 입력을 구현해주는 스크립트입니다.

## 사용법

1. roll20 세션방의 대문에 해당하는 페이지에서 [설정]->[API 스크립트]를 선택해 스크립트 수정 페이지로 들어갑니다. (PRO 계정에서만 이 메뉴가 보입니다.)

2. New Script에 [[ ruby_character.js ]](https://github.com/kibkibe/roll20-api-scripts/blob/master/ruby_character/ruby_character.js)의 코드들을 복사해 붙여놓고 [Save Script]로 저장합니다. 

3. 페이지 아래쪽의 API Output Console에 에러 메시지가 표시되지 않는다면 정상적으로 적용된 것입니다. 세션방에서 테스트를 진행할 수 있습니다.

4. 채팅창에 명령어 `!루`나 `!r`을 이용하여 아래와 같은 형식으로 입력해 테스트를 해봅니다.
    
		!루 [아래에 표시될 문자](위에 표시될 문자)

> Roll20에서 링크나 이미지를 삽입할 때와 동일한 [내용](내용) 형식의 마크다운 표기법을 사용합니다.