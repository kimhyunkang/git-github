# 비개발자를 위한 Git 과 GitHub

## 버전 관리?

* 협업으로 문서를 만들때 누구나 흔히 겪는 상황
  * 발표자료-20160120
  * 발표자료-최종
  * 발표자료-최종 수정 1
  * 발표자료-최종 수정 2
  * 발표자료-진짜 최종
  * 발표자료-진짜 마지막 수정
* 변화를 추적하는 것은 원래 어렵다

## 버전 관리 시스템

* 파일의 변화를 저장하고 추적할 수 있게 해 주는 시스템
* 필요할 경우 예전 버전으로 돌려놓을 수도 있어야
* 쉽게 접할 수 있는 간단한 버전 관리 시스템
  * Google Drive
  * 위키백과

## Google Drive 의 예

![Google Drive Screenshot](google-drive-screenshot.png)

## Git

* 리눅스 개발자 리누스 토르발스가 만든 버전 관리 시스템
* 기존의 버전 관리 시스템들이 무료는 너무 구리고 유료는 라이센스 문제로 리눅스에 사용할 수
  없어 한달만에 직접 짰다고…
* 2005년에 처음 발표한 후 10년만에 세계에서 가장 많이 쓰이는 버전 관리 시스템이 되었음
* 개인적인 의견으로는 컴공과에서 가르치지 않는 기술 중에 개발자에게 가장 유용한 기술입니다

## GitHub

* [www.github.com](https://www.github.com)
* Git 버전 관리 시스템을 웹으로 관리할 수 있게 해주는 서비스
* 전세계 개발자들이 가장 많이 쓰는 협업 도구
* 라이엇게임즈는 GitHub 엔터프라이즈 버전을 사용합니다
* [gh.riotgames.com](https://gh.riotgames.com)

## SourceTree

* [www.sourcetreeapp.com](https://www.sourcetreeapp.com)
* 많이 쓰이는 GUI 기반 Git 관리 툴
* 무료입니다!

## GitHub 저장소를 만들어 봅시다

GitHub 계정을 만들고 New repository 를 클릭

![New Repository](new-repository.png)

이름과 설명을 적고 Create Repository 버튼을 누르면 끝

## 저장소를 내 컴퓨터로 가져오기

모든 저장소에는 고유의 URL 이 생성됩니다

![Clone URL](clone-url.png)

이 저장소의 URL 을 복사하여 내 컴퓨터의 GUI 클라이언트에서 가져오면 저장소를 복제할 수
있습니다

![Clone from SourceTree](sourcetree-clone.png)

## 커밋 해보기

* 아무 파일이나 메모장으로 열어 새로 생성하거나 고쳐 봅니다
* 커밋할 파일을 선택합니다
* 커밋 메시지를 작성한 후 커밋 버튼을 누릅니다

![Commit Screenshot](commit-screenshot.png)
