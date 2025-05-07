## ✅Commit Convention

| 타입 | 설명 |
| --- | --- |
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `docs` | 문서 수정 (README, 주석 등) |
| `style` | 코드 포맷팅, 세미콜론 누락 등 기능 변화 없는 수정 |
| `refactor` | 코드 리팩토링 (기능 변화 없음) |
| `test` | 테스트 코드 추가 및 수정 |
| `chore` | 빌드 업무, 패키지 매니저 설정 등 기타 변경사항 |
| `perf` | 성능 향상 관련 코드 변경 |
| `ci` | CI 설정 수정 |
| `build` | 빌드 시스템 변경 (webpack, npm 등) |
| `revert` | 이전 커밋 되돌리기 |

### 🧾 Commit Message Example

```bash
feat: 회원가입 API 추가
fix: 토큰 갱신 오류 수정
docs: README에 커밋 컨벤션 추가
style: 코드 들여쓰기 정리
refactor: 중복 로직 제거
test: 로그인 유닛 테스트 작성
chore: eslint 설정 추가
perf: 이미지 로딩 속도 개선
ci: GitHub Actions 배포 워크플로 수정
build: webpack 설정 수정
revert: feat: 회원가입 API 추가 커밋 되돌림
```

## 💡 PR Convention

| 아이콘 | 코드 | 설명 |
| --- | --- | --- |
| ✨ | `:sparkles:` | 새로운 기능 추가 |
| 💄 | `:lipstick:` | UI/스타일 관련 파일 수정 |
| 🐛 | `:bug:` | 버그 수정 |
| 📝 | `:memo:` | 문서 작성 또는 수정 (예: README, Wiki 등) |
| 🎨 | `:art:` | 코드의 구조/형태 개선 |
| ⚡️ | `:zap:` | 성능 개선 |
| 🔥 | `:fire:` | 불필요한 코드/파일 삭제 |
| 🚑 | `:ambulance:` | 긴급 수정 (핫픽스 등) |
| ⏪ | `:rewind:` | 변경 내용 되돌리기 |
| 🔀 | `:twisted_rightwards_arrows:` | 브랜치 병합 |
| 💡 | `:bulb:` | 주석 추가/수정 |
| 🗃 | `:card_file_box:` | 데이터베이스 관련 작업 |
| 🔧 | `:wrench:` | 설정 파일 수정 |
| ✅ | `:white_check_mark:` | 테스트 코드 추가/수정 |
| 📦 | `:package:` | 패키지/라이브러리 관련 변경 |

### 💬 PR 제목 예시: 
```text
✨ 로그인 기능 구현
🐛 토큰 갱신 오류 수정
```
