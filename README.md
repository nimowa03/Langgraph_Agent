# 🤖 Langgraph Agent - RAG 구현 학습 프로젝트

LangGraph를 활용한 에이전트 RAG 구현을 학습하는 프로젝트입니다.

## 📚 학습 내용

### 1. LangChain ToolCalling
- Tool Calling 개념 및 구현
- Tavily 웹 검색 도구 사용
- 사용자 정의 도구 만들기
- Few-shot 프롬프팅

### 2. LangGraph StateGraph
- 상태 기반 그래프 구조
- Node, Edge, State 개념
- 조건부 엣지를 통한 분기
- Reducer 패턴

### 3. LangGraph MessageGraph
- 대화 기록 관리
- MessagesState 활용
- Feedback Loop 구현
- 반복적 작업 처리

### 4. ReAct (Reasoning + Acting)
- ReAct 패턴 이해
- ToolNode 사용
- MemorySaver로 대화 유지
- 체크포인터 활용

### 5. Agentic RAG ⭐
- **Adaptive RAG**: 질문 라우팅
- **Self-RAG**: 자기 평가 및 개선
- **CRAG**: 지식 정제
- **Human-in-the-Loop**: 사용자 개입
- **Sub-graph**: 병렬 실행

## 🚀 시작하기

### 1. 필요 패키지 설치

```bash
# pip 사용
pip install -r requirements.txt

# 또는 poetry 사용
poetry install
```

### 2. 환경 변수 설정

`.env` 파일을 생성하고 필요한 API 키를 설정하세요:

```bash
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
GOOGLE_API_KEY=your_google_api_key  # Gemini 사용 시
```

### 3. 학습 순서

1. `PRJ_01_LangChain_ToolCalling.ipynb`
2. `PRJ_02_LangGraph_StateGraph.ipynb`
3. `PRJ_03_LangGraph_MessageGraph.ipynb`
4. `PRJ_04_LangGraph_ReAct_Memory.ipynb`
5. `PRJ_05_LangGraph_AgenticRAG.ipynb`

## 📂 프로젝트 구조

```
Langgraph_Agent/
├── code/                          # 실습 노트북
│   ├── PRJ_01_LangChain_ToolCalling.ipynb
│   ├── PRJ_02_LangGraph_StateGraph.ipynb
│   ├── PRJ_03_LangGraph_MessageGraph.ipynb
│   ├── PRJ_04_LangGraph_ReAct_Memory.ipynb
│   └── PRJ_05_LangGraph_AgenticRAG.ipynb
├── data/                          # 실습 데이터
│   ├── restaurant_menu.txt
│   └── restaurant_wine.txt
├── langgraph_rag_v3_dist.pdf     # 교육 자료
├── requirements.txt               # 패키지 목록
├── pyproject.toml                # Poetry 설정
└── README.md                      # 이 파일
```

## 🔑 필요한 API 키

- **OpenAI API**: GPT 모델 사용
- **Tavily API**: 웹 검색 기능
- **Google API**: Gemini 모델 사용 (선택)
- **Groq API**: 빠른 추론 (선택)

## 📖 참고 자료

- [LangChain 공식 문서](https://python.langchain.com/)
- [LangGraph 공식 문서](https://langchain-ai.github.io/langgraph/)
- **교육 자료**: `langgraph_rag_v3_dist.pdf`

## 👤 학습자

- GitHub: [@nimowa03](https://github.com/nimowa03)

## 📝 라이선스

교육 목적 프로젝트입니다.
