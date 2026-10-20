# 휴먼 보고서 번역 — 업데이트 배포

휴먼 보고서 번역 전용 수정판의 업데이트 파일을 배포하는 저장소입니다.

**2.0.0·2.0.1 사용자는 프로그램을 종료한 뒤 [최신 릴리스](https://github.com/Hyoungmin-jacob/human-report-translator-updates/releases/latest)의 Update EXE를 한 번 직접 실행해 주세요.** 이전 버전의 GitHub 주소 이동 처리 오류를 2.0.2에서 수정했습니다. 기존 프로그램을 삭제할 필요는 없습니다.

이후에는 프로그램에서 **업데이트 확인 → 업데이트 다운로드 → 다시 시작하여 설치**를 선택하면 됩니다. 로그인 후 번역 화면에서 한 번 자동 확인하며, 새 버전은 상단 배너에 표시됩니다. 계속 켜 둔 상태에서는 업데이트 확인을 눌러 다시 확인하세요.

전용 업데이트 주소가 기본으로 포함됩니다. 2.0.2 이상을 설치한 뒤에도 기존에 저장한 빈 주소나 다른 주소가 남아 있다면 아래 주소를 ‘전용 업데이트 연결 설정’에 저장하세요.

```text
https://github.com/Hyoungmin-jacob/human-report-translator-updates/releases/latest/download/latest.json
```

릴리스에는 계정 정보가 없는 `HumanReportTranslator-Update-<version>.exe`와 서명된 버전 안내 `latest.json`만 게시합니다. 프로그램은 업데이트 서명·버전·파일 크기·해시를 확인한 후 설치합니다.

개인 단어집과 연결설정은 업데이트 후에도 유지됩니다. 최초 설치용 계정 포함 Setup, API 키, 로그인 비밀번호, 개인 단어집 및 업데이트 서명 개인키는 이 저장소에 게시하지 않습니다.

제공받은 기존 프로그램을 바탕으로 보완한 수정판입니다. 원본 구성요소의 출처와 라이선스는 설치 폴더의 `THIRD_PARTY_PROVENANCE.txt` 및 라이선스 파일에서 확인할 수 있습니다.
