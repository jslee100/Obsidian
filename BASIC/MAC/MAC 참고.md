#### Nextpad++ -> notepad++처럼 사용

#### 프로그램 강제 삭제
 - 1. 터미널에서 해당 위치 접속
 - 2. sudo rm -rf /앱이름.app  

#### 캡처

 - 1. 전체 : Cmd + Shift + 3
 - 2. 부분 : Cmd + Shift + 4
 - 3. 특정 창 : Cmd + Shift + 4 + Space bar
 - 4. 옵션창 : Cmd + Shift + 5

#### 숨김 폴더/파일 표시
 - finder에서 Cmd + Shift + .
 - ~ 경로 이동: cmd + shift + h

#### 마우스 휠 윈도우처럼 설정
 - 왼쪽 위 사과 아이콘 > 시스템 설정 > 왼쪽 메뉴에서 마우스 > 자연스로운 스크롤 비활성화

#### iPhone 알림 해제
 - 왼쪽 위 사과 아이콘 > 시스템 설정 > 알림 > iPhone 알림 > iPhone으로부터의 알림 허용 비활성화

#### !!! vscode !!!
터미널 열기 : ctrl+shift+`
터미널 화면 초기화 : Cmd + K
실제 기기에서 android구동 : npx react-native run-android
android구동 안되면 보통 gradle권한이나 local.properties설정 필요

#### 사용중인 port 강제종료

kill -9 $(lsof -t -i :8080)