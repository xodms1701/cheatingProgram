# cheatingProgram

firebase의 Realtime database로 구현한 안드로이드 채팅프로그램입니다.

# 개요
이 앱은 채팅방 이름과 자신의 이름을 입력한 후에 채팅방에 입장하는 방식입니다.
기존에 있는 채팅방의 이름을 입력하면 기존의 채팅방에 입장하게 되고
기존에 없는 채팅방의 이름을 입력하면 새로운 채팅방에 입장하게 됩니다.
10개단위로 pagination이 되어있고 대화의 진행방식은 위에서 아래로 내려옵니다.
채팅방에 입장했을 때는 채팅의 맨위에서 시작하기때문에 listview를 내려서 밑의 listview를 볼 수 있습니다.

# 테스트 하는 법
1. 기존에 있는 home 채팅방에는 많은 채팅 기록이 있어서 pagination이 제대로 작동하는지 확인할 수 있습니다.
2. 외에는 자유롭게 테스트하셔도 좋습니다.
