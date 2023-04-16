---
layout: default
title: Git 연동
parent: knowledge
has_children: true
nav_order: 6
---

# git 연동
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Gitgub - eclipse 연동 계정

- github과 eclipse 연동을 위한 패스워드 확인 방법

  1. github 웹사이트 접속 후 우측 상단 Settings 정보 선택
    *   ![](./images/git/1.png)
  
  2. 좌측 하단 Developer settings 선택
    *   ![](./images/git/2.png)
  	
  3. Personal access tokens > Tokens (classic) 선택
  	 *    ![](./images/git/3.png)
  
  
## Github - eclipse 저장소 연결
- github 저장소 연결하는 방법
  1. git clone
- 저장소에 프로젝트 올리기
  1. 이클립스 프로젝트 선택 > Team > Share Project
  2. Share Project 팝업에 Repository 선택
      *   ![](./images/git/4.png)
  3. Project가 연결된것으 볼 수 있다.
      *   ![](./images/git/5.png)
      - 이클립스 프로젝트와 github 연결만 된것이지 소스가 올라간 것은 아님
      
## Github - eclipse 저장소 파일 올리기
  1. 로컬 소스 github 저장소에 올리기 
  
     1) 이클립스 > 상단 Window > Show View > Git Staging 
     
     2) Git Staging
        
      Commit and Push 버튼 선택 
      
     	- Unstaged Changes : 수정한 파일을 아직 로컬 데이터베이스에 커밋하지 않은 상태
     	- Staged Changes   : 현재 수정한 파일을 곧 커밋할거라고 표시한 상태
     	- Committed        : 데이터가 로컬 데이터베이스에 안전하게 저장됨
     
      *   ![](./images/git/7.png)
      
     참고) git 세가지 상태
      + remote branch에 올리기 위해서는 네번째로 'Push'를 수행해야함
    
      *   ![](./images/git/6.png)
      
     참고) 파일 변경에 따른 이클립스 아이콘 상태
      
      *   ![](./images/git/8.png)
     
      
## Check out
  1. 로컬 소스 github 저장소에 올리기 
  1. 로컬 소스 github 저장소에 올리기 
  1. 로컬 소스 github 저장소에 올리기 