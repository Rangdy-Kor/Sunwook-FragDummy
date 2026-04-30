---
publish: true
---

# RUBIDIAN ULTRABOOK

---

```table-of-contents
```

## HARDWARE

---

### CENTRAL

---

|      제품군      |            모델             |
| :-----------: | :-----------------------: |
| **Main Unit** | Samsung Galaxy Book 6 Pro |
|    **CPU**    |    Intel Core Ultra 3     |
|    **GPU**    |      Intel Arc iGPU       |
|    **RAM**    |       32GB LPDDR5X        |
|    **SSD**    |      1TB NVMe Gen 5       |

### PERIPHERAL

---

|    제품군     |                                모델                                |          비고          |
| :--------: | :--------------------------------------------------------------: | :------------------: |
| **무선 네트워크 모듈** |                   AMD Wi-Fi 7 / Bluetooth 5.4                    |          -           |
|   **디스플레이**    |        16” Dynamic AMOLED 2X Touch 2880x1800 16:10 120Hz         |          -           |
|    **키보드**     | Built-in Full Size Keyboard with Per-Key Backlight & Copilot Key | US International ISO |
|    **마우스**     |                       Logitech MX Master 4                       |          -           |
|   **마우스 패드**   |                    Artisan Hayate Otsu Soft M                    |          -           |

## SOFTWARE

---

### SYSTEM / DRIVER & CONTROL

---

|        분류군        |                                        소프트웨어                                        |    라이선스     |      패키지 원본       | 비고  |
| :---------------: | :---------------------------------------------------------------------------------: | :---------: | :---------------: | :-: |
|     **운영체제**      |                                Microsoft Windows 11                                 | Windows Pro |        OEM        |  -  |
|    **칩셋 드라이버**    | Intel Chipset Driver<br>Intel Management Engine Interface<br>Intel Serial IO Driver |      -      |  Samsung Update   |  -  |
|   **그래픽 드라이버**    |             Intel Arc Graphics Driver<br>Intel Graphics Command Center              |      -      |  Samsung Update   |  -  |
|    **관리 드라이버**    |                       Samsung Settings<br>Samsung Device Care                       |      -      |  Samsung Update   |  -  |
|    **AI 드라이버**    |                         Intel Gaussian & Neural Accelerator                         |      -      |  Samsung Update   |  -  |
|   **사운드 드라이버**    |                        Realtek High Definition Audio Driver                         |      -      |  Samsung Update   |  -  |
|                   |                                   Dolby Atmos SW                                    |      -      |  Samsung Update   |  -  |
| **유선 네트워크 드라이버**  |                       Realtek 2.5G Ethernet Controller Driver                       |      -      |  Samsung Update   |  -  |
| **무선 네트워크 드라이버**  |                    Intel Wi-Fi 7 (BE200) & Bluetooth 5.4 Driver                     |      -      |  Samsung Update   |  -  |
|  **SD 카드 드라이버**   |                         Genesys Logic SD Card Reader Driver                         |      -      |  Samsung Update   |  -  |
| **HID 드라이버 및 제어** |                                    Logi Option+                                     |      -      | Official Homepage |  -  |
|                   |                            Razer Synapse<br>Razer Chroma                            |      -      | Official Homepage |  -  |
|                   |                                Samsung Multi Control                                |      -      |  Samsung Update   |  -  |
|   **프린터 드라이버**    |                                  Epson EcoTank Pro                                  |      -      | Official Homepage |  -  |
|   **NVMe 드라이버**   |                           Samsung Magician & NVMe Driver                            |      -      |  Samsung Update   |  -  |
|  **생체 인식 드라이버**   |                              Goodix Fingerprint Driver                              |      -      |  Samsung Update   |  -  |

### SECURITY / PRIVACY & DATA PROTECTION

---

|         분류군         |             소프트웨어              |            라이선스            |      패키지 원본       |                                                          비고                                                          |
| :-----------------: | :----------------------------: | :------------------------: | :---------------: | :------------------------------------------------------------------------------------------------------------------: |
|  **안티 바이러스 소프트웨어**  |       ESET Home Security       | ESET Home Security Premium |      Winget       |                                       AppCheck 상호 예외 설정<br>WebProtection 비활성화                                        |
|  **안티 랜섬웨어 소프트웨어**  |       CheckMAL AppCheck        |        AppCheck Pro        |      Winget       |                                                    ESET 상호 예외 설정                                                     |
|  **네트워크 보안 소프트웨어**  |         ESET Firewall          | ESET Home Security Premium |      Module       |                                                       ESET 내장                                                        |
|  **네트워크 관제 소프트웨어**  |      SecureMix GlassWire       |     GlassWire Premium      |       Scoop       |                                                     방화벽 기능 비활성화                                                      |
|    **칩입 탐지 시스템**    | ESET Network Attack Protection | ESET Home Security Premium |      Module       |                                                       ESET 내장                                                        |
| **설치형 악성 코드 제거 도구** |          Malwarebytes          |    Malwarebytes Premium    |      Winget       |                                             실시간 보호 비활성화<br>주 1회 자동 전체 검사                                             |
| **포터블 악성 코드 제거 도구** |          Malware Zero          |             -              | Official Homepage |                                                    감염 의심 시 수동 검사                                                     |
|   **블로트웨어 소거 도구**   |             구라제거기              |             -              | Official Homepage |                                                 블로트웨어 설치 의심 시 수동 실행                                                  |
|     **VPN 서비스**     |           ProtonVPN            |       ProtonVPN Plus       |      Winget       | WireGuard UDP 프로토콜<br>Kill Switch Non-Permanent 활성화<br>NetShield 비활성화<br>VPN Accelerator 활성화<br>일부 VPN 차단 사이트 분할 터널링 |
|    **비밀번호 관리자**     |           Bitwarden            |             -              |       Scoop       |                                             Vaultwarden NAS Self-hosting                                             |
|     **컨텐츠 차단기**     |            AdGuard             |      AdGuard Familys       |      Winget       |                WFP 드라이버 모드 기능 사용<br>HTTPS 필터링 활성화<br>EV 인증서 웹사이트 필터링 활성화<br>AdGuard DNS-over-QUIC 사용                 |
|    **클라우드 아카이브**    |             IDrive             |   IDrive Personal 100TB    |      Winget       |                                                       분기 1회 백업                                                       |

### WORKSPACE / OFFICE

---

|      분류군      |           소프트웨어           |             라이선스              |      패키지 원본       |                   비고                    |
| :-----------: | :-----------------------: | :---------------------------: | :---------------: | :-------------------------------------: |
|  **워드프로세서**   |    Microsoft Word 2026    |     Microsoft 365 Premium     |     Official      |                    -                    |
|               |    Hancom Hangul 2024     |          Hancom Docs          |     Homepage      |                    -                    |
|  **프레젠테이션**   | Microsoft PowerPoint 2026 |     Microsoft 365 Premium     | Official Homepage |                    -                    |
|  **스프레드시트**   |   Microsoft Excel 2026    |     Microsoft 365 Premium     | Official Homepage |                    -                    |
|  **PDF 리더**   |     Adobe Acrobat Pro     | Adobe Creative Cloud All Apps | Official Homepage |                    -                    |
|   **간편 메모**   |        Google Keep        |        Google AI Ultra        |    Vivaldi PWA    |                    -                    |
|  **협업 프로젝트**  |          Notion           |          Notion Plus          |       Scoop       |                    -                    |
| **메일 클라이언트**  |          Outlook          |     Microsoft 365 Premium     | Official Homepage |                    -                    |
| **클라우드 스토리지** |          DropBox          |    DropBox Essentials 3TB     |       Scoop       | 파일 공유 & 동기화, 오피스 작업용<br>파일 저장 및 백업은 NAS |
|               |       Google Drive        |        Google AI ULTRA        |      Winget       |   갤러리 동기화, 외부 협업용<br>미디어는 NAS에 추가 백업    |
|  **AI 서비스**   |          ChatGPT          |          ChatGPT Pro          |      Winget       |                    -                    |
|               |          Claude           |          Claude Max           |       Scoop       |                    -                    |
|               |          Gemini           |        Google AI Ultra        |    Vivaldi PWA    |                    -                    |

### CREATIVE / STUDIO

---

|          분류군           |       소프트웨어        |             라이선스              |      패키지 원본       |                 비고                 |
| :--------------------: | :----------------: | :---------------------------: | :---------------: | :--------------------------------: |
|     **데스크탑 퍼블리싱**      |   Adobe InDesign   | Adobe Creative Cloud All Apps | Official Homepage |                 -                  |
|     **비트맵 그래픽 툴**      |  Adobe Photoshop   | Adobe Creative Cloud All Apps | Official Homepage |                 -                  |
|      **벡터 그래픽 툴**      | Adobe Illustrator  | Adobe Creative Cloud All Apps | Official Homepage |                 -                  |
| **영상 편집 / 영상 색상 보정 툴** |  DaVinci Resolve   |    DaVinci Resolve Studio     |      Winget       | XML/EDL 내보내기를 통한 Adobe CC와의 작업물 공유 |
|      **음향 편집 툴**       |   Adobe Audition   | Adobe Creative Cloud All Apps | Official Homepage |                 -                  |
|   **특수 효과 / 모션 그래픽**   | Adobe After Effect | Adobe Creative Cloud All Apps | Official Homepage |                 -                  |
|     **사진 색상 보정 툴**     |  Adobe Lightroom   | Adobe Creative Cloud All Apps | Official Homepage |                 -                  |

### DEV STACK / EDITOR

---

|       분류군        |              소프트웨어               |            라이선스             |      패키지 원본       |                                                                                 비고                                                                                  |
| :--------------: | :------------------------------: | :-------------------------: | :---------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|    **단순 메모장**    |             Notepads             |              -              |       Scoop       |                                                                                  -                                                                                  |
|   **마크다운 편집기**   |              Typora              |         Typora EULA         |       Scoop       |                                                                          단일 파일 마크다운 파일 편집                                                                           |
| **개인 지식 관리 시스템** |             Obsidian             |              -              |       Scoop       | 지식 관리 시스템 구축<br>Self-hosted Live Sync Plugin를 통해 NAS Container 동기화<br>Quartz와 GitHub & Vercel 를 통해 정적 웹 게시<br>Obsidian-Remote NAS Container Package를 통해 외부 환경 웹 액세스 |
|   **텍스트 편집기**    |            Notepad++             |              -              |       Scoop       |                                                                      대용량 텍스트 파일 분석 및 단순 텍스트 수정                                                                      |
|    **코드 에디터**    |        Visual Studio Code        |              -              |       Scoop       |                                                   LaTeX 편집 (LaTeX Workshop Extension)<br>포맷팅 및 스크립팅<br>SSH 원격 접속                                                    |
|   **통합 개발 환경**   |        Visual Studio IDE         | Visual Studio Professional  |      Winget       |                                                             C / C++ | Windows App | Native Programing                                                             |
|                  |         JetBrains Rider          | JetBrains All Products Pack | JetBrains Toolbox |                                                               C# / F# | Game Engine | .NET Backend                                                                |
|                  |       JetBrains RustRover        | JetBrains All Products Pack | JetBrains Toolbox |                                                           Pure Rust | Rust Backend | System Programing                                                            |
|                  | JetBrains IntelliJ IDEA Ultimate | JetBrains All Products Pack | JetBrains Toolbox |                   Java / Kotlin | JVM Backend <br>Pure Python | Python Backend | Data Analysis | AI Model Training<br>JS / TS | Web Frontend                   |
|  **IDE 설치 관리**   |        JetBrains Toolbox         |              -              |      Winget       |                                                                                  -                                                                                  |
|   **LaTeX 엔진**   |             TeX Live             |              -              |       Scoop       |                                                                                  -                                                                                  |
|  **데이터베이스 관리**   |             Navicat              |       Navicat Premium       |       Scoop       |                                                                             종합 설계 및 관리                                                                              |
|                  |    JetBrains IDE 내장 DataGrip     | JetBrains All Products Pack |      Module       |                                                                            개발 단계 조회 및 확인                                                                            |
|   **버전 관리 엔진**   |               Git                |              -              |       Scoop       |                                                                                  -                                                                                  |
| **버전 관리 클라이언트**  |            GitKraken             |        GitKraken Pro        |       Scoop       |                                                                          메인 레포지토리 / 브랜치 관리                                                                          |
|                  |     IDE 내장 및 VS Code 확장 Git      |              -              |      Module       |                                                                        단순 커밋 / 푸시 및 수정 이력 확인                                                                        |
