# Effective Java Docs

# Contents
|Chapter|Due Date|
|-------|--------|
|2장 객체 생성과 파괴|24.05.26 ~  24.06.06|
|3장 모든 객체의 공통 메서드|TBC|
|4장 클래스와 인터페이스|TBC|
|5장 제네릭|TBC|
|6장 열거 타입과 애너테이션|TBC|
|7장 람다와 스트림|TBC|
|8장 메서드|TBC|
|9장 일반적인 프로그래밍 원칙|TBC|
|10장 예외|TBC|
|11장 동시성|TBC|
|12장 직렬화|TBC|

# How to contribute docs
## Step 1. Fork Study Repo.
**스터디 진행을 위해 해당 Repo를 자신의 Repo로 Fork한다.**

## Step 2. Create Your Branch

## Step 3. Write Docs
### Directory Tree
```
[폴더 구조]
|- /chapter{n}
|- README.md # Chapter에 대한 Description
|-- /{자신의 Github 아이디}
|--|-- README.md # 아이템들에 대한 Docs 작성
|--|-- /assets # README.md에 들어가는 assets 폴더
|--|--|-- img1.png
|--|--|-- img2.png
|--|-- /src (Optional) # 참고할만한 코드가 있으면 Import
|--|--|--/{package-path}
```
### 작성 규칙
- 해당 Chapter 폴더 하위에 자신의 Github 닉네임 ([참고](./chapter2/README.md#과제-완료-인원)) 으로 폴더를 생성.
- 자신의 Github 닉네임 폴더 하위에 Wiki를 작성하는 `README.md` 파일 작성 
    - Chapter에 대한 모든 내용 작성! 
    - ❌ Item별로 README 파일을 쪼개면 안됨!!
- 자신의 Github 닉네임 폴더 하위에 `assets`폴더에는 Wiki에 들어가는 이미지를 Import
    - ❗ 꼭 이미지의 파일 이름은 `영문`으로 구성되어야 함!! (ex. java-jvm.png)
    - ❗ `README.md` 파일에 이미지를 임베딩할 경우에는 꼭 상대경로로 지정!!
        ``` 
        ![java-jvm](./assets/java-jvm.png) 
        ```
### WiKi Template
- Wiki를 작성하는 `README.md` 파일 작성 시에는 template/README.md를 참고하여 작성!!
- README.md 상단에는 `YAML frontmatter block`을 꼭 달아야 함!!
```
---
sidebar: auto
lang: ko-KR
title: effective-java-chapter1
---
# ITEM 1. 생성자 대신 정적 팩터리 메서드를 고려하라.
## ~~

# ITEM 2. 생성자에 매개변수가 많다면 빌더를 고려하라.
## ~~
```

## Step 4. Create Pull Request
- WiKi 작성을 완료하였다면, PR(Pull Request)를 생성.
- PR을 생성할 때에는 
- 각 아이템들을 공부하다가 이해가 되지 않거나 토론할 내용이 있다면 Comment를 남기기.
## Step 5. Noti Messenger

# To do every weeks

스터디 장은 Project 기준으로 Chapter별로 Issues 생성

## 📜회고 진행방식
- 해당 Comment에 대해서는 자유롭게 답변을 달아 주시면 됩니다.
- 격주로 오프라인 스터디를 진행합니다.
- 한 사람 당 한개씩 아이템 발표를 진행합니다.
- 매주 한 사람당 한 개의 아이템을 준비하여 발표를 진행합니다.
- 발표 자료는 따로 만들 필요 없이 README와 PR의 Comment를 위주로 진행합니다.
- Effective Java에 나오는 예제 코드 외적으로 자신이 생각하는 적절한 예제코드를 작성하기 (Optional).

