# myProject2
revert 사용해보기

1.revert 이전 상태
  "commit" : A.txt B.txt C.txt 파일 추가
  "second commit" : D.txt 파일 추가
  "third commit" : E.txt 파일 추가

2. revert 
  $git revert <해당 커밋 번호>
  "revert third" :git revert c8227e29e802648dec3b75c1284ce7f56ec9c6b3 를 이용해서 third commit 이전으로 revert

3. revert 후
  "third commit"이 푸시되기 이전인 상태(A.txt B.txt C.txt D.txt만 레포에 존재, E.txt는 없음)로 돌아감
