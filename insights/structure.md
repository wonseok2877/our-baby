# random-question

## 구상

1. database에서 question 중 하나를 랜덤으로 가져와 렌더링. back-end에선 math.random을 이용하고, javascript에선 html상의 h1 요소와 연결해서 렌더링.
2. front에서 answer에 대한 text를 html상의 input 요소에 넣으면, javascript에선 eventListener과 submit이 발동해서 그 텍스트 data를 어딘가로 보낼 수 있게됨. back-end에서 해당 question data와의 공유 id를 설정하여 database에 저장시킴.
3. real-time을 불러와서 같이 저장.
4. 유저 authentification까지 하면 완-벽
