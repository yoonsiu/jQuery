# 내컴에서만 버전 관리 

1. git init : 최초에 한번만
2. 작업
3. git add .
    // 로그인
    3-1. git config --global user.email "example@naver.com"
    3-1. git config --global user.name  "example"
    // 해제 
    3-1. git config --global --unset user.email 
    3-1. git config --global --unset user.name  
4. git commit -m "설명"

5. git status
6. git log

# github.com에서 버전관리
// 배포는 아니고 naver에 file 업로드하듯이 온라인상 업로드

1. git branch -M  main
2. git remote  add  origin 깃url 
3. git push -u origin main
  3-1. 인증 token을 입력하세요. 
 