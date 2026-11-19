<div align="center">
    <h1>token-pet</h1>
    <p>Claude Code 사용량을 알려 주는 도트 펫</p>
    <p>
        <a href="https://github.com/kjadlkg/token-pet-releases/releases/latest"><img src="https://img.shields.io/github/v/release/kjadlkg/token-pet-releases" alt="최신 버전"></a>
        <a href="https://github.com/kjadlkg/token-pet-releases/releases"><img src="https://img.shields.io/github/downloads/kjadlkg/token-pet-releases/total?label=downloads" alt="다운로드 수"></a>
        <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-blue" alt="Windows 10, 11">
    </p>
    <p>
        <a href="https://github.com/kjadlkg/token-pet-releases/releases/latest"><b>최신 버전 받기</b></a>
        &nbsp;·&nbsp;
        <a href="https://github.com/kjadlkg/token-pet-releases/issues">버그 제보</a>
    </p>
</div>

화면 아래에 사는 도트 펫 크로냥이 Claude Code의 5시간 한도와 주간 한도를 말풍선으로 알려 줍니다. 세션마다 병아리가 한 마리씩 나타나고, 입력을 기다리는 세션은 머리 위 `!`로 표시합니다.

## 사용법

Windows 10, 11에서 동작하고 설치 없이 실행합니다.

1. [최신 버전 받기](https://github.com/kjadlkg/token-pet-releases/releases/latest)에서 `token-pet.exe`를 내려받습니다.
2. 받은 파일을 실행합니다.
3. 크로냥을 우클릭하고 **사용량 연결**을 누릅니다.

이제 Claude Code를 쓰면 사용량이 표시됩니다. 모든 설정은 **크로냥을 우클릭**하면 나오는 메뉴에 있습니다.

> [!TIP]
> 처음 실행할 때 "알 수 없는 게시자" 경고가 뜨면 **추가 정보**를 누른 다음 **실행**을 누릅니다.

## 기능

| 기능 | 하는 일 |
|---|---|
| **사용량 확인** | 5시간 한도와 주간 한도를 말풍선으로 알려 줍니다. 크로냥을 누르면 자세한 패널이 열립니다. |
| **세션 친구** | Claude Code 세션마다 병아리가 한 마리씩 나타납니다. 일하는 중인지 쉬는 중인지 모습으로 알 수 있습니다. |
| **입력 대기 알림** | 세션이 입력을 기다리면 병아리 머리 위에 `!`가 뜹니다. 누르면 그 창이 앞으로 나옵니다. |
| **키우기** | 세션이 일한 시간만큼 크로냥의 레벨이 오르고, 같이 일한 날이 "함께 N일"로 쌓입니다. 패널 맨 아래 줄에서 볼 수 있습니다. |
| **쓰다듬기** | 버튼을 누르지 않고 크로냥 위에서 마우스를 좌우로 문지르면 골골거리며 하트가 뜹니다. 하루에 한 칸씩 친밀도 하트가 찹니다. |
| **꾸미기** | 스킨, 말풍선 모양, 계절마다 바뀌는 바닥 장식, 울타리를 고릅니다. 겨울에는 눈이 내립니다. |
| **기간 한정 스킨** | 할로윈, 12월, 생일 주간에는 그 기간의 스킨으로 저절로 갈아입습니다. 할로윈과 12월에는 바닥, 울타리, 말풍선도 함께 바뀝니다. 기간이 끝나면 전에 쓰던 것으로 돌아옵니다. |
| **자리 옮기기** | 크로냥을 잡아서 원하는 곳에 내려놓습니다. 어느 모니터에 둘지도 고를 수 있습니다. |

## 업데이트

| 종류 | 받는 방법 |
|---|---|
| **스킨** | 자동으로 받아 옵니다. 새 스킨은 메뉴의 "스킨"에 저절로 추가됩니다. |
| **새 버전** | 크로냥이 말풍선으로 알려 줍니다. 메뉴 맨 위의 "새 버전 받기"로 새 파일을 받아 실행합니다. 쓰던 파일은 새 버전이 휴지통으로 옮깁니다. |

스킨을 자동으로 받지 않으려면 메뉴에서 "새 스킨 자동으로 받기"를 끕니다. 레벨과 하트가 필요 없으면 메뉴에서 "키우기"를 끕니다.

## 개인정보

> [!NOTE]
> token-pet이 인터넷으로 하는 일은 두 가지뿐입니다.
>
> - 이 저장소의 스킨 목록(`skins.json`)을 받아 옵니다.
> - 사용량을 연결했는데 상태줄 값이 오지 않으면(VS Code 확장 등) PC에 있는 Claude Code 로그인으로 Anthropic에 사용량을 조회합니다. 로그인 정보는 Anthropic으로만 보냅니다.
>
> 그 밖에는 PC 정보나 사용량을 **어디로도 보내지 않습니다.**

## 삭제

1. 우클릭 메뉴에서 **사용량 연결 해제**를 누릅니다.
2. **종료**를 누릅니다.
3. `token-pet.exe`를 지웁니다.
