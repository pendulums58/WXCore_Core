# WXCore_Core

WIXOSS 시뮬레이터([WXCore](https://github.com/pendulums58/WXCore))의 코어 DLL 저장소.
클라이언트가 켤 때마다 이 저장소를 `repositories/WXCore_Core`로 받아 `bin/wxcore.dll`을 쓴다.

- 코어 API 버전(major)과 메시지 스키마가 클라이언트와 맞을 때만 쓰고, 맞지 않으면 클라이언트에 동봉된 코어를 쓴다.
- 코어 API 2.3, 스키마 5 (클라이언트 0.3.0과 함께 빌드). 0.2.2 클라이언트도 이 코어를 쓸 수 있다(API 2.x·스키마 5). 0.2.1 이하는 동봉 코어를 쓴다
