# Cofa Hackathon Kit

실무 해커톤을 위한 작은 공개 준비 저장소다. 기능 단위 승인, 필요한 요구사항 질문, 근거 있는 완료 보고와 코드 이해를 돕는다. 180분은 기존 안내의 참고값이며 실제 제한 시간은 최신 응시 안내와 타이머를 따른다. 시험 문제나 결과물을 보관하는 저장소가 아니다. 사용한 준비 저장소는 **2차 결과 통지까지 공개 상태를 유지**한다. 실제 운영 공지와 제공 환경의 지침이 우선이다.

## 구성

| 파일 | 용도 |
| --- | --- |
| [AGENTS.md](AGENTS.md) | 선택적으로 적용할 작업·승인·검증 원칙 |
| [docs/COFA-WORKFLOW.md](docs/COFA-WORKFLOW.md) | 참가자의 환경 확인·미리보기·제출 체크리스트 |
| [START-PROMPT.txt](START-PROMPT.txt) | 참가자가 직접 복사해 보내는 시작 프롬프트 |
| [docs/PRACTICE.md](docs/PRACTICE.md) | 시험 전 가상 프로젝트로 진행하는 사람용 코드 이해 연습 |
| [deep-interview-exam/SKILL.md](skills/deep-interview-exam/SKILL.md) | 불명확한 요구사항만 짧게 확인하는 별도 변형 |
| [deep-interview-exam/LICENSE](skills/deep-interview-exam/LICENSE) | 원본 MIT 라이선스 |
| [verification-before-completion/SKILL.md](skills/verification-before-completion/SKILL.md) | Superpowers의 완료 전 검증 Skill 원문 |
| [verification-before-completion/LICENSE](skills/verification-before-completion/LICENSE) | 원본 MIT 라이선스 |
| [SOURCES.md](SOURCES.md) | 고정 원본 버전·변형 여부·출처 |

## 시험 환경에서 가져오기

1. 실제 현재 경로·파일과 과제 README·기존 AGENTS·운영·관리·안전 지침을 먼저 확인한다.
2. 반입이 허용되면 **제공된 허용 도구로만** 이 공개 저장소를 별도 kit 폴더에 clone 또는 다운로드한다. 실제 작업공간이 `/home/user`인 경우 `/home/user/cofa-hackathon-kit`은 예시 경로일 뿐이다. 경로를 추측하지 말고 확인한다. 터미널과 Git이 허용되는 경우, 시험 Git 루트를 덮어쓰지 않는 별도 위치에서 실행한다.

   ```sh
   git clone https://github.com/denny6389/cofa-hackathon-kit.git
   ```

3. 시험 Git 루트를 재초기화하거나 kit 파일을 한 폴더에 풀어 과제 파일과 섞지 않는다. 기존 README·AGENTS·관리 파일을 덮어쓰거나 전역 설정을 바꾸지 않는다. **별도 폴더라고 제출에서 자동 제외되는 것은 아니다.** `uploads`의 역할과 제출 범위는 실제 과제 README·Cofa Helper로 확인한다.
4. clone은 Skill 등록과 다르다. 허용된 Codex 세션에서 필요한 `SKILL.md`를 명시적으로 읽게 하는 방식을 기본으로 한다. 자동 등록·탐색은 검증하지 않았으며 보장하지 않는다. 설치 프로그램은 필요 없다. kit의 AGENTS.md가 형제 폴더의 과제에 자동 적용되는 것도 아니다. 필요한 지침만 명시적으로 읽거나, 허용되는 경우 기존 규칙을 보존하며 선택적으로 병합한다.

이 kit에는 설치 스크립트·의존성·MCP 서버·추가 에이전트가 없다. Cofa 연동을 독립적으로 검증한 kit가 아니다. 비공개 체험 과제·PDF·스크린샷을 공개 재현하거나 시험 자료를 이 저장소로 보내지 않는다. 원본 버전·변형·라이선스는 [SOURCES.md](SOURCES.md)를 확인한다.

## 시작 프롬프트

시작 프롬프트의 본문은 [START-PROMPT.txt](START-PROMPT.txt) 하나로 관리한다. 참가자가 직접 열어 복사하고, `/home/user/cofa-hackathon-kit`을 실제 kit 경로로 바꿔 허용된 Codex 세션에 보낸다. 자동 로드용 지침이 아니다.

흐름은 기능 계획 승인 → 해당 범위의 구현·관련 엣지케이스 검증·필수 문서 갱신 → 주요 기능 설명·짧은 이해 확인과 diff·결과 보고 → 결과 승인 후 다음 기능이다. 이해 질문 때문에 별도 승인 단계를 추가하거나 작은 수정마다 퀴즈를 반복하지 않는다.

## 시험 전 연습

참가자는 [docs/PRACTICE.md](docs/PRACTICE.md)를 직접 열어 가상 프로젝트로 코드 읽기·설명·피드백·재설명을 연습할 수 있다. 실제 시험 자료나 모범답안을 모으는 문서가 아니며, 시험 중 자동으로 읽도록 연결하지 않는다.
