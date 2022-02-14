# hello git

## git 명령어 요약

- clone: 원격 저장소 복사
- add: 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브) 를 만들 수 있다.
- push: 원격 저장조에 커밋을 업로드한다.

## 파일의 내용 되돌리기

- 특정파일의 내용을 마지막 커밋으로 돌리고 싶다면 해당 파일 선택 후 '코드 뭉치 버리기' 선택
## 브랜치 변경하기

- branch: 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용한다.
- checkout: 특정 branch(혹은 commit)로 돌아가고 싶을 때 사용
- Sourcetree의 checkout: branch 이름을 더블클릭하는 것만으로 checkout 가능

## 병합하기 1

- Head branch에 변경사항이 없고 병합 대상 branch가 head로부터 시작된 경우
- 아주 쉽게 병합 가능 = fast-forward

## 병합하기 2

- Head branch에 추가적인 commit이 생기는 경우 병합이 필요해진다.
- 충돌이 난다.

## 충돌 2

- 중요중요
