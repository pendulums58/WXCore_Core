# WXCore_Core

WIXOSS 시뮬레이터([WXCore](https://github.com/pendulums58/WXCore))의 코어 DLL 저장소.
클라이언트가 켤 때마다 이 저장소를 `repositories/WXCore_Core`로 받아 `bin/wxcore.dll`을 쓴다.

- 코어 API 버전(major)과 메시지 스키마가 클라이언트와 맞을 때만 쓰고, 맞지 않으면 클라이언트에 동봉된 코어를 쓴다.
- 코어 API 1.0, 스키마 2 (클라이언트 0.1.4와 함께 빌드). 0.1.3 이하 클라이언트(스키마 1)는 이 코어를 안 쓰고 동봉 코어를 쓴다
