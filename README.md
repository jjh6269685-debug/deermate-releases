# 디어메이트 (Deermate)

Windows 데스크톱 펫의 공식 배포 저장소입니다. 이 저장소에는 배포 파일과 사용자용 안내만 보관합니다.

## 다운로드

[최신 Deermate.exe 받기](https://github.com/jjh6269685-debug/deermate-releases/releases/latest/download/Deermate.exe)

Windows x64 단일 포터블 EXE입니다. 기존 실행 중인 디어메이트를 종료하고, 쓰기 가능한 사용자 폴더에 저장해서 실행하세요. 자동 업데이트 주소가 없는 기존 버전은 이 EXE로 한 번 수동 교체해야 합니다.

## 업데이트

실행 후 백그라운드에서 새 버전을 확인하고 패치노트를 보여줍니다. 사용자가 **업데이트**를 선택하면 다운로드·검증·종료·교체·재실행합니다. 설정에서 자동 확인을 끌 수 있으며 수동 확인은 계속 사용할 수 있습니다.

고정 파일명은 `Deermate.exe`, `SHA256.txt`입니다. 공식 저장소 URL, 정확한 파일명, 다운로드 크기, SHA-256과 GitHub Asset digest를 확인합니다. 검증에 실패하면 설치하지 않습니다. 교체 실패 시 백업 복원을 시도하며 사용자 캐릭터·대화·설정을 프로그램과 분리합니다.

공개 Release의 파일과 태그는 불변성 보호를 사용합니다. 현재 EXE는 Authenticode 서명 인증서가 없어 서명되지 않았습니다. 체크섬은 파일 무결성 검사이며 Windows 코드 서명을 대신하지 않습니다. 백신/SmartScreen 보호를 끄지 마세요.

## 배포 파일

- `Deermate.exe`: Windows x64 앱
- `SHA256.txt`: EXE의 SHA-256
- `build-provenance.json`: 빌드의 버전·소스 커밋·파일 해시 기록. 이 JSON 자체는 서명된 빌드 증명서가 아닙니다.

GitHub의 자동 생성 Source code 압축에는 이 배포 저장소의 안내 문서만 포함되며 앱 소스는 포함되지 않습니다.
