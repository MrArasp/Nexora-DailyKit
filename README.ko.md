# NEXORA DAILYKIT

> Windows 10 및 Windows 11용 가벼운 데스크톱 캘린더 및 일일 계획 앱입니다.

**Version:** 1.0.0 — Stable Release

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇨🇳 简体中文](README.zh-CN.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇩🇪 Deutsch](README.de.md) · [🇫🇷 Français](README.fr.md) · [🇷🇺 Русский](README.ru.md)

---

## 소개

NEXORA DAILYKIT은 캘린더, 일일 계획, 작업, Journal, 알림 및 날짜 정보를 하나의 로컬 Windows 앱에 모읍니다. 앱 UI는 현재 English와 Persian만 지원합니다.

---

## 주요 기능

- Gregorian / Persian-Jalali / Islamic
- Daily Information, Tasks, Journal
- Windows 알림 및 사용자 지정 알림 소리
- Desktop Layer 위젯 및 투명도
- System Tray
- 밝게/어둡게/시스템 테마
- 기능별 색상 및 표시 설정
- 자동/수동 백업과 복원
- English/Persian, LTR/RTL
- 로컬 저장 및 About Us

---

## 시스템 요구 사항

- Windows 10 또는 Windows 11
- 앱을 설치하고 실행할 수 있는 Windows 사용자 계정
- 일반적인 캘린더, 작업, Journal, 알림, 백업에는 인터넷 불필요

---

## 다운로드

공개 GitHub 저장소의 **Releases**에서 공식 Windows 버전을 다운로드하십시오. 소스 코드는 별도로 관리됩니다.


---

## 설치

1. Releases에서 최신 Windows 설치 프로그램을 다운로드합니다.
2. 설치 프로그램을 실행합니다.
3. Windows 설치를 완료합니다.
4. **NEXORA DAILYKIT**을 실행합니다.
5. 최초 실행은 English와 Gregorian입니다.
6. Settings에서 변경합니다.


---

# 📖 전체 사용자 가이드

## 1. 첫 실행

기본값은 영어, 그레고리력, 화면 왼쪽 아래 작업 표시줄 위의 위젯, 기본 투명도, 로컬 저장입니다.

<img width="358" height="531" alt="image" src="https://github.com/user-attachments/assets/84d86b90-8e88-4b1a-9407-02536447a5cc" />

## 2. 메인 화면

**Calendar**는 날짜와 월을 표시합니다. **Settings**는 외관, 캘린더, 위젯, 알림, 백업, 언어를 관리합니다. **About Us**는 NEXORA 정보, 링크, 후원, 지갑 복사를 제공합니다. 앱 이름은 항상 **NEXORA DAILYKIT**입니다.


## 3. 캘린더

월 이동, 날짜 선택, Today, 기본 캘린더 변경, 추가 캘린더 표시, 선택 날짜 정보 표시가 가능합니다. 선택한 날짜가 주 강조이며 다른 날짜를 선택하면 오늘의 강조가 약해집니다.

<img width="350" height="422" alt="image" src="https://github.com/user-attachments/assets/44b749a9-e159-4a23-afbc-f98d9e540f6b" />

## 4. 캘린더 시스템

**Gregorian:** 국제 표준. **Persian / Jalali:** 페르시아 태양력. **Islamic:** 이슬람 Hijri. Islamic은 Umm al-Qura 기반이며 현지 월 관측 달력과 약 하루 차이가 날 수 있습니다. Jalali는 지원되는 천문학적 Solar Hijri 계산을 사용합니다.


## 5. 캘린더 표시 설정

**Settings → Calendar**에서 기본/두 번째/세 번째 캘린더, 날짜 형식, 숫자 형식, 주 시작일을 설정합니다. 주 시작일은 자동, 토요일, 일요일, 월요일입니다. 페르시아어 UI에서도 날짜 숫자는 서양/영문 숫자입니다.

<img width="579" height="500" alt="image" src="https://github.com/user-attachments/assets/793455e7-04ff-4c52-b81a-59e4fed96c7a" />

## 6. 일일 정보

날짜를 선택하면 Daily Information이 표시됩니다. **Tasks**는 실행할 항목이고 **Journal**은 해당 날짜의 자유 메모입니다.

<img width="410" height="552" alt="image" src="https://github.com/user-attachments/assets/6e22b24d-5dfc-4a83-8f94-a85bd15dd6b0" />

## 7. 작업

제목, 선택 설명, 선택 시간, 완료 상태를 사용할 수 있습니다. 생성/편집/완료/재개/삭제가 가능합니다. 날짜 선택 → Daily Information → **New Task** → 입력 → 저장. 시간이 있는 작업은 알림 엔진이 처리합니다.

<img width="1048" height="536" alt="image" src="https://github.com/user-attachments/assets/da58064e-4ebc-453a-9875-54de9895afe3" />

## 8. Journal

Journal은 날짜별 메모입니다. 자동 및 수동 저장을 지원하며 일일 기록, 아이디어, 개인 기록, 회의 메모 등에 사용할 수 있습니다.

<img width="362" height="532" alt="image" src="https://github.com/user-attachments/assets/bf6069c8-2e1f-4545-9990-a9034dff6577" />

## 9. 알림

작업에 알림 시간을 지정할 수 있습니다. Windows 알림, 설정된 소리, Snooze, Dismiss를 사용할 수 있습니다. 예약 알림은 앱 시작 시 다시 로드됩니다. Windows 알림 설정과 권한도 영향을 줍니다.

<img width="333" height="112" alt="image" src="https://github.com/user-attachments/assets/d3921005-457d-4c2c-a556-e569efb9fc3a" />

## 10. 알림 설정

**Settings → Reminders**에서 알림 소리, 기본/사용자 지정 소리, Test, Stop Sound, 볼륨, 기본 Snooze를 설정합니다.

<img width="500" height="386" alt="image" src="https://github.com/user-attachments/assets/b316d3a0-a312-4f9a-9586-5eeddd44908c" />

## 11. 데스크톱 위젯

기본 위치는 화면 왼쪽 아래 작업 표시줄 위입니다. 이동, 크기 변경, 표시/숨기기, Windows 시작, Tray로 닫기, 위치 초기화가 가능합니다. Desktop Layer는 **일반 창 뒤**에 있으며 Always-on-top이 아닙니다. 멀티 모니터 위치 복구를 지원합니다.

<img width="338" height="468" alt="image" src="https://github.com/user-attachments/assets/0c6a8a2e-1d6b-42f5-8238-17777e46fcba" />

## 12. 위젯 투명도

20%~100%. 캘린더 조작 중에는 일시적으로 100%가 되고 이후 설정값으로 돌아갑니다. 저장값은 변경되지 않습니다.

<img width="465" height="396" alt="image" src="https://github.com/user-attachments/assets/edfe1014-953f-4d02-bfd5-77685b0286d5" />

## 13. 시스템 트레이

위젯을 닫아도 일반적으로 앱은 종료되지 않습니다. Tray에서 표시, 숨기기, **Exit**를 사용할 수 있으며 완전 종료는 Exit뿐입니다.


## 14. 설정

상단 **Settings**에서 Appearance, Calendar, Widget, Reminders, Backup, Language, About을 관리합니다.

<img width="475" height="186" alt="image" src="https://github.com/user-attachments/assets/d7286baf-4182-465a-8b8f-c7df232f8aba" />

## 15. 외관

**Settings → Appearance**에서 테마, 강조 색상, Calendar/Task/Journal/Reminder 색상, 배경, 텍스트, 글꼴 크기, 밀도를 설정합니다. 밝게/어둡게/시스템 테마와 Preview/Reset을 지원합니다.

<img width="642" height="845" alt="image" src="https://github.com/user-attachments/assets/f8fb00bf-9257-44f0-b741-443e9e258288" />

## 16. 언어

**Settings → Language**. 현재 English와 Persian을 지원합니다. 첫 설치는 English입니다. 페르시아어는 필요한 곳에서 RTL이며 URL과 지갑은 LTR입니다. README 8개 언어는 앱 UI 8개 언어를 의미하지 않습니다.

<img width="387" height="287" alt="image" src="https://github.com/user-attachments/assets/177812f1-8a21-4805-b6f6-0e28cdc4383e" />

## 17. 백업 및 복원

**Settings → Backup**에서 자동 백업, 빈도, 위치, 보존, 수동 백업, Restore를 설정합니다. 빈도는 Daily, Weekly, On exit. 기본 위치는 `Documents/Nexora DailyKit/Backups`입니다. Open Folder는 현재 위치를 열고 Backup Now는 즉시 백업합니다.

<img width="579" height="454" alt="image" src="https://github.com/user-attachments/assets/225b3cf9-f66c-4f25-849b-070693c21082" />

## 18. 복원

복원 전 현재 데이터의 안전 백업을 만듭니다. Settings → Backup → Restore → 백업 선택 → 확인 → 완료 대기. 필요하면 재실행/새로 고침합니다. 복원 중 종료하지 마십시오.


## 19. About Us

공식 링크: Telegram https://t.me/nexora_labs_2026, GitHub https://github.com/MrArasp, Donations https://donito.me/nexora_labs. Network: EVM / USDT BEP20. Wallet: `0x5Bcdef9E0d9030e5cAa73e1D50aC71257EC8304e`. 지갑은 복사용입니다.


## 20. 데이터 저장 및 개인정보

캘린더, 작업, Journal, 알림, 설정, 백업은 PC에 로컬 저장됩니다. 일반 사용에는 NEXORA 계정, 클라우드, 구독, 온라인 동기화가 필요하지 않습니다. 외부 링크를 열 때만 인터넷을 사용합니다. 로컬 데이터 보안은 Windows 계정과 저장 폴더의 보안에도 좌우됩니다.


## 21. 문제 해결

위젯이 사라지면 System Tray 확인. 위치가 잘못되면 Settings → Widget → Reset Position. 알림이 없으면 작업 시간/저장/앱 또는 Tray/Windows 알림/Reminder 설정 확인. 소리가 없으면 Windows/Reminder 볼륨과 선택 소리를 확인하고 Test Sound 사용. 백업 위치는 Settings → Backup → Open Folder. Persian 표시가 필요하면 Language에서 Persian. Islamic 하루 차이는 계산 방식 차이일 수 있습니다.


## 22. 캘린더 기술 참고

Jalali는 지원되는 천문학적 Solar Hijri 계산, Islamic은 Umm al-Qura 데이터를 사용합니다. Islamic은 현지 월 관측 달력이 아니므로 다른 달력과 약 하루 차이가 날 수 있습니다.


## 23. 버전

**NEXORA DAILYKIT 1.0.0**. 이 문서는 안정 버전 1.0.0을 설명합니다. 최신 설치 프로그램과 Release Notes는 공개 저장소에서 확인하십시오.


---

## 피드백

- Telegram: https://t.me/nexora_labs_2026
- GitHub: https://github.com/MrArasp
문제 신고에는 버전과 구체적인 설명을 포함하십시오.

## NEXORA 지원

https://donito.me/nexora_labs

**EVM / USDT BEP20**

`0x5Bcdef9E0d9030e5cAa73e1D50aC71257EC8304e`

## Copyright

© NEXORA. All rights reserved.
NEXORA DAILYKIT은 Windows 데스크톱 앱으로 배포됩니다. 릴리스 및 라이선스 정보는 공개 저장소와 Release 패키지를 확인하십시오.
