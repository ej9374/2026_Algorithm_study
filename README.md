# 알고리즘 및 코딩 테스트 문제 풀이
2026년도 상반기 알고리즘 공부 및 코딩 테스트 준비를 위한 스터디입니다.
코딩테스트 문제는 [링크](https://github.com/tony9402/baekjoon) 를 참고하고자 합니다.

## 📂 리포지토리 구조 (Folder Structure)
**주차별(Week)**로 폴더를 나누고 그 안에 **문제별** 폴더를 만듭니다.

```text
algorithm_study/
 ├── Week01/                   # 이번 주차 폴더
 │    ├── [BOJ] A+B/           # [출처] 문제이름
 │    │    ├── Eunji.java      # 본인 이름.확장자
 │    │    └── Subin.cpp
 │    └── [PGS] 기능개발/
 │         ├── Eunji.java
 │         └── Subin.cpp
 ├── Week02/
 └── README.md
```

## 🌿 브랜치 규칙 (Branch Naming)
브랜치 생성 시 아래 규칙을 꼭 지켜주세요! (하이픈 - 필수) 
- 규칙: `Week-주차-이름`
- 예시: `Week-01-Eunji`

## 💬 커밋 메시지 규칙 (Commit Message)
- 규칙: `[사이트] 문제이름 / 난이도 / 이름`
- 예시: `[BOJ] 토마토 / Gold 5 / Eunji`
- 예시: `[PGS] 입국심사 / Lv 3 / Friend`

<br>

## 🔄 진행 루틴 (Workflow)
### 1. 이슈 생성 (Monday) 📅
매주 월요일에 New Issue를 생성하여 이번 주 풀 문제를 공지합니다.
- 제목: `[Week N] 날짜 ~ 날짜 스터디 목표`
- 내용: 문제 링크, 마감일, 벌칙 등

### 2. 문제 풀이 (Tue ~ Fri) 💻
- 브랜치 규칙에 맞게 브랜치를 생성합니다. `Week-01-Eunji`
- 문제 풀고 `git commit`, `git push`

### 3. PR 및 코드 리뷰 (Saturday) 🔍
- Compare & pull request 클릭
- PR 템플릿 내용을 채우고 Reviewers에 상대방 태그
- 서로의 코드에 피드백(Comment) 남기기

### 4. Merge (Sunday) ✅
- 리뷰 반영 후 Merge pull request
- 해당 주차 Issue Close

