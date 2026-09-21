# 11th_PE_Mobile_Practice_Mission

UMC-11th Mobile(Flutter) 실습 미션 제출 레포지토리입니다.

## 🚀 앱 실행하고 종료하기

```bash
cd movielog
flutter pub get
flutter run
```

앱을 종료할 때는 터미널에서 `q`를 누르거나 `Ctrl + C`를 누릅니다.

## 🎬 movielog 폴더

MovieLog 앱 미션 프로젝트입니다.

## 🌳 branch 규칙

```bash
├─main
    ├─kasa/main
	...
```

1. `닉네임/main 브랜치`가 기본 브랜치로 pr 보낼 때 root 브랜치(main 브랜치)가 아닌 닉네임/main 브랜치로 올립니다.
2. 매주 실습, 미션은 각자의 닉네임/main 브랜치를 base 브랜치로 삼아 fork한 레포지터리에서 base branch에 pull request를 생성합니다.
3. 교육국장 approve를 받으면, pr을 머지하고 이때, pr 제목은
   `[n주차/닉네임] 미션 제출합니다` 형식으로 작성합니다.

## 🔖 커밋 컨벤션

**예시**

- `mission: 1주차 미션 제출`
- `fix: 프로필 화면 레이아웃 오류 수정`

| Message | 설명                  |
| ------- | --------------------- |
| mission | 미션 수행             |
| fix     | 버그 수정             |
| docs    | 문서 수정             |
| comment | 주석 추가 및 변경     |
| test    | 테스트 코드 추가      |
| rename  | 파일 혹은 폴더명 수정 |
| remove  | 파일 혹은 폴더 삭제   |
| chore   | 기타 변경사항         |
