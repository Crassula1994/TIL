<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css" />

<div style="font-style: 'Pretendard'">

# 💻 【GIT-001】 Git Installation

<br />

## 💠 목차

-   <span style="font-weight: 500; font-size: 1.2em">A. [깃과 깃허브](#-a-깃과-깃허브)</span>
-   <span style="font-weight: 500; font-size: 1.2em">C. [깃 초기 설정](#-c-깃-초기-설정)</span>

<br />

## 💠 A. 깃과 깃허브

-   <span style="color: #FFFFFF; background-color: #1848D9; font-weight: 700; font-size: 1.2em">&nbsp;&nbsp;깃(Git)&nbsp;&nbsp;</span>
    -   리눅스(Linux)를 창시한 리누스 토르발스(Linus Torvalds)가 2005년 개발한 <span style="font-weight: 700">분산형 버전 관리 시스템(DVCS; Distributed Version Control System)</span>
    -   소프트웨어 개발 과정에서 문서, 설계도, 소스 코드, 파일 등의 변경 내역, 즉 버전(Version)을 추적 · 보존 · 관리하는 소프트웨어

<br />

-   <span style="font-weight: 700; font-size: 1.2em">깃을 사용하는 이유</span>
    -   안정성
        -   깃은 분산형 버전 관리 시스템으로서, 중앙 서버의 데이터가 유실되어도 손쉽게 복구 가능
        -   네트워크 문제가 있어도 독립적으로 개발 가능
    -   효율성
        -   대부분의 작업을 로컬에서 처리하기 때문에 속도가 빠름
        -   변경 이력이 많더라도 변경된 내용만 처리하므로 메모리 효율성 확보
    -   데이터 무결성
        -   모든 변경 사항을 추적하며, 각각의 변경 사항은 고유한 해시 값으로 식별하여 변경 이력을 안전하게 관리
        -   병렬 개발 지원

<br />

## 💠 C. 깃 초기 설정

-   깃 사용자(User) 이메일 및 계정 설정

    ```bash
    git config --global user.email "example@example.com"
    git config --global user.name "John Doe"
    ```

</div>
