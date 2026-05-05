# mco-1.56

### 1. 에임 및 무기 (Combat)
| 기능 | 함수 이름 (Symbol) | 오프셋 (주소) |
|---|---|---|
| **반동 제거 (No Recoil)** | _ZN6Recoil10StopRecoilEv | 02e1f9c8 |
| **반동 로직 제어** | _ZN6Recoil12ProcessShootEv | 02e1fa0c |
| **탄퍼짐 업데이트** | _ZN6Spread6UpdateEfR9GameScene | 02e21074 |
| **탄퍼짐 고정 (No Spread)** | _ZN6Spread14ApplyToShotRayERN7cocos2d3RayE | 02e21240 |
| **타겟 자동 검색 (Aimbot)** | _ZN10PlugObject12SearchTargetEv | 02998e00 |
| **타겟 고정 사격** | _ZN10PlugObject11ShootTargetEf | 0299ab9c |
### 2. 게임 플레이 및 유틸리티 (Gameplay)
| 기능 | 함수 이름 (Symbol) | 오프셋 (주소) |
|---|---|---|
| **리스폰 시간 단축** | _ZNK9GameScene14GetRespawnTimeEv | 026bcd30 |
| **거리 계산 (ESP 활용)** | _ZNK9PPosition12DistanceFromERKS | 027388b0 |
| **카메라 업데이트** | _ZN10GameCamera6UpdateEf | 0291c518 |
### 3. 보상 및 재화 우회 (Economy)
| 기능 | 함수 이름 (Symbol) | 오프셋 (주소) |
|---|---|---|
| **광고 보상 정보 호출** | _ZN9AdManager14ShowRewardInfoEv | 026cf3a4 |
| **보상 획득 가능 체크** | _ZN11GuideSystem20CheckAnyRewardCanGetEv | 02aa8930 |
| **유료 재화 모드 체크** | _ZN10UIBuyCheck17GetEffectCashModeEv | 02ac4900 |
### 4. 보안 및 밴 방지 (Security)
| 기능 | 함수 이름 / 관련 항목 | 오프셋 (주소) |
|---|---|---|
| **보안 모듈 초기화** | XigncodeClientSystem_ZCWAVE_1Initialize | (JNI Entry) |
| **이상 행위 서버 보고** | _ZN11CommonScene8DEBUGLOGESsb | 0275fc90 |
| **제재 패킷 수신** | _ZN11CommonScene12onRecvPacketEiPKcihi | 026870a8 |
| **응답 시간 제한 (Lag)** | WaitReceivePacketTimeLimit | 03738e70 |
