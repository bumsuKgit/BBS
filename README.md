# BBS(게시판)
2024-11-06</br>
쉬고있다가 응원을 받아서 갑자기 열정이 끌어올라 지금 만들고 있는거 올려보려고 깃허브 들어와봄<img width="35" alt="팀즈 하이파이브 아이콘" src="https://github.com/user-attachments/assets/af1ffe2d-7c13-46d0-8f60-67502a128664"></br>

깃허브써볼겸 </br>
프로젝트올리것도 해볼겸</br>
개발공부 안한지 너무 오래돼서</br>
유튜브 보면서 내가 만들고 싶은 거 만들어봄</br>
물론 시작은 아직 그냥 평범한 게시판이지만</br>
html도 다시 다뤄보고 sql도 써보고 java도 써보려고 만드는중</br>
</br>
일단은 남들 다 하는 CRUD게시판이 되겠지만</br>
마지막에는 서버도 추가해서 한번 어디서든 내 웹사이트 들어갈 수 있게 해보고싶음(아직확정아님 이건)</br>
</br>
이 홈페이지의 최종 목적지는</br>
저녁식사 초대용 홈페이지를 만드는게 목적임</br>
남들 다 하는 평범한 CRUD지만 사진업로드 기능을 추가하고 싶음</br>
근데 너무 오랫동안 개발을 멀리했고 코드를 그냥 영상보면서 따라하는 수준이라 막상 만들어도 그냥 복사 붙혀넣기 같은 느낌이 될 것 같음</br>
그래도 똑같은 페이지를 수십번 만들다 보면 자연스럽게 코드를 이해하게 되지않을까? 해서 그냥 만들고 싶은거 만들자</br>
가 되었음</br>
</br>
영상 따라하면서도 생긴오류 일단 정리</br>
update기능을 추가했는데 NULLPOINT오류가나옴 근데 해결법을 모르겠음</br>
그러다가 어디서 오류가 났는지 모르겠어서 syso를 붙혀서 오류나는곳을 찾아봤는데</br>
Bbs bbs = new BbsDAO().getBbs(bbsID); 여기서 bbsID가 null값이 돼서 문제가 생김</br>
물론 이 코드조차 완벽하게 이해못함 아직</br>
여기까지...</br>
