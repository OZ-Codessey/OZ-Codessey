#README

도시복합개발사업 후보지 평가를 위한 프롬프트 엔지니어링
프로젝트 개요
본 프로젝트는 생성형 AI를 활용하여 도시복합개발사업 후보지를 평가하고 우선순위를 선정하기 위한 프롬프트 엔지니어링 과제이다.

업무 정의
도시복합개발사업 후보지를 평가하고 우선순위를 선정한다.

적용 기법
* 페르소나(Persona) 설계
* 시스템 프롬프트(System Prompt) 설계
* 사용자 프롬프트(User Prompt) 설계
* Few-shot Learning
* 단계별 추론 유도(Step-by-Step Reasoning), V1-->V2
* Hallucination Verification
* 장기 문맥 유지(Context Retention) 검증(10턴)

평가 기준
평가 항목	가중치
1.법·제도 정합성	30%
2.복합 조건 충족 여부	30%
3.실무적 리스크 진단	20%
4.사업 실현 가능성	20%
최종 선정 모델
ChatGPT (GPT-5.5)
선정 이유
* 정보 부족 시 추가 질문 수행 능력이 우수함
* 출력 형식 준수율이 높음
* 근거 기반 답변 생성 능력이 우수함

저장소 구성
* README.md
* system_prompt.md
* user_prompt.md
* fewshot_examples.md
* step_by_step_reasoning.md
* hallucination_verification.md
* conversation_log.md


















