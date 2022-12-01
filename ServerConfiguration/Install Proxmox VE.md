# Install Proxmox VE

## What is Proxmox VE?

- Proxmox Virtual Environment
- 타입 1 하이퍼바이저
- 리눅스 (데비안 기반) 위에서 구동
- 오픈 소스, 경량

## Proxmox VE 설치하기

- USB 메모리에 [Proxmox VE 설치 이미지](https://www.proxmox.com/en/downloads)를 기록
- BIOS 설정에서 가상화 기술 활성화 (Virtualization Technology)
- 설치 과정에서 국가, 시간, 키맵, 네트워크 IP 정보 등만 입력해주면 간단하게 설치 완료

## Proxmox VE 구성하기

- 구독 레포지토리를 pve-no-subscription로 변경해야 한다.
기본 구독 채널은 pve-enterprise이다.
[링크](https://www.uname.in/61)를 참고하여 동일한 방식으로 진행한다.

![[proxmoxSubscription.png]]

- 이후 구성은 잠시 중단한다. 스토리지 구성에 필요한 물품이 도착하지 않음 :(

도움 준 사람 / 링크:
Bell - [GitHub](https://github.com/DragonString), [GitLab](https://gitlab.bellsoft.net/Bell)
[Proxmox 업데이트 채널 변경](https://www.uname.in/61)
