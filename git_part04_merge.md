# Git Merge

내가 끌어온 저장소가 최신 버전이 아닌 경우,  
즉 내가 pull 을 실행한 후 다른 사람이 push 를 하여 원격 저장소를 업데이트 해버린 경우에는   
push 요청이 거부되어 버립니다.

이런 경우 병합(merge)이라는 작업을 진행하여 다른 사람의 업데이트 이력을 내 저장소에도 갱신 해야합니다.  
만약 병합하지 않은 채로 이력을 덮어쓰게 되면 다른 사람이 push 한 업데이트 내역이 사라져 버리기 때문입니다.

병합 기능은 Git 에서 변경한 부분을 자동으로 통합해 주는 기능입니다.  
그러나 경우에 따라 자동으로 병합할 수 없는 경우도 있습니다.

원격 저장소와 로컬 저장소 양쪽에서 파일의 동일한 부분을 변경한 경우입니다.  
이 경우 두 변경 내용중 어느 쪽을 저장할 것인지 자동으로 판단 할 수 없기 때문에 충돌이 발생합니다.
