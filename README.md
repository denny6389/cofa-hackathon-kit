# Cofa Hackathon Kit

180분 실무 해커톤을 위한 작은 공개 준비 저장소다. 기능 단위 승인, 필요한 요구사항 질문, 근거 있는 완료 보고를 돕는다. 시험 문제나 결과물을 보관하는 저장소가 아니다. 사용한 준비 저장소는 **2차 결과 통지까지 공개 상태를 유지**한다. 실제 운영 공지와 제공 환경의 지침이 우선이다.

## 구성

| 파일 | 용도 |
| --- | --- |
| [AGENTS.md](AGENTS.md) | 선택적으로 적용할 작업·승인·검증 원칙 |
| [deep-interview-exam/SKILL.md](skills/deep-interview-exam/SKILL.md) | 불명확한 요구사항만 짧게 확인하는 별도 변형 |
| [deep-interview-exam/LICENSE](skills/deep-interview-exam/LICENSE) | 원본 MIT 라이선스 |
| [verification-before-completion/SKILL.md](skills/verification-before-completion/SKILL.md) | Superpowers의 완료 전 검증 Skill 원문 |
| [verification-before-completion/LICENSE](skills/verification-before-completion/LICENSE) | 원본 MIT 라이선스 |
| [SOURCES.md](SOURCES.md) | 고정 원본 버전·변형 여부·출처 |

## 시험 환경에서 가져오기

1. 참가자가 실제 과제의 README와 기존 AGENTS·운영·관리·안전 지침을 먼저 확인한다.
2. 반입이 허용되면 **제공된 허용 도구로만** 이 공개 저장소를 별도 폴더에 clone 또는 다운로드한다. 예를 들어 터미널과 Git이 허용되는 경우, 시험 Git 루트 밖의 준비 폴더에서 다음 명령을 실행한다.

   ```sh
   git clone https://github.com/denny6389/cofa-hackathon-kit.git
   ```

3. 시험 Git 루트 위에 clone하거나 재초기화하지 않는다. kit 전체를 과제에 복사하거나 기존 AGENTS·관리 파일을 덮어쓰거나 전역 설정을 바꾸지 않는다.
4. 허용된 Codex 세션에서 필요한 kit 문서를 명시적으로 읽게 한다. 과제 지침에 합칠 필요가 있다면, 허용되는 부분만 검토해 기존 규칙을 보존하며 선택적으로 병합한다.

**제공될 CLI의 Skill 탐색·로딩은 아직 시험하지 않았다.** 이 폴더를 clone한다고 자동 설치·발견·호출된다고 보장하지 않는다. 실제 환경의 안내를 따른다. 로더가 확인되지 않으면 허용된 세션에서 파일을 직접 읽도록 요청한다. 이 kit에는 설치 스크립트·의존성·MCP·추가 에이전트가 없다.

## 시작 프롬프트

아래의 경로는 실제 준비 폴더 위치로 바꾼다.

```text
먼저 과제 README와 기존 작업·운영·안전 지침을 읽어줘.
허용되는 범위에서 <준비 폴더>/cofa-hackathon-kit/AGENTS.md와 필요한 Skill을 참고해줘.
요구사항이 명확하면 인터뷰는 생략해줘.
현재 상태와 기존 변경을 확인하고, 첫 기능 하나의 범위·완료 조건·검증 계획을 제안해줘.
내가 그 계획을 승인하면 해당 기능 안에서 구현·테스트·수정을 진행하고,
저장 후 실제 diff와 새 검증 결과, 남은 한계를 보여줘. 다음 기능은 결과 승인 후 진행해줘.
```

## 참가자가 직접 하는 1회 15분 사전 체험

- [ ] 감독 연결과 제공 환경 접속을 확인한다.
- [ ] 제공 Codex의 실행 상태와 허용 모델을 확인한다. 업데이트하지 않는다.
- [ ] 기존 지침과 kit 문서를 읽을 수 있는지, Skill 로딩 방식이 지원되는지 확인한다.
- [ ] 체험에서 허용된 예제로 저장·실행·미리보기·제출 경로를 확인한다.

체험은 참가자가 직접 한 번 진행한다. 이 저장소 제작 과정에서는 실제 체험·시험에 접속하지 않았다. 체험·시험의 비공개 내용을 외부로 내보내거나 준비 저장소로 push하지 않는다. 후속 서술형 6문항(각 5분)은 AI·붙여넣기 없이 직접 작성한다.
