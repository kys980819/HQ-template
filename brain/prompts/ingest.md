# Ingest Prompt (벤더 중립 원본)

```text
inbox\ 에 새로 들어온 자료를 ingest 해줘.

- inbox 원본은 절대 수정·이동·삭제하지 않는다 (불변)
- 내용을 읽고 brain\01-Wiki\sources\ 에 요약 문서를 만든다 (BRAIN.md 8장 문서 포맷)
- 반복해서 쓸 개념은 wiki\concepts\ 에, 의사결정이 필요한 내용은 wiki\decisions\ 에 연결
- 취업 공고면 추가로: 20-기업분석\회사명.md 생성([[템플릿-기업분석]]) + 지원현황.md에 한 줄 추가
- 저장 5필터(BRAIN.md 5장)를 통과하는 것만 저장
- 끝나면 brain\index.md 와 brain\log.md 를 갱신하고, 처리한 파일 목록을 보고
```
