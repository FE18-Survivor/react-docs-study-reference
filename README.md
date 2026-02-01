# React 공식 문서 스터디 (Reference)

## Overview

- 도구 : React 공식 문서 [Reference](https://react.dev/reference/react) (v19.2 기준)
- 일정 : 매주 화, 금 오전 10시
- 진행 방식
  - 정해진 분량을 각자 읽고 스터디 전까지 push
  - 스터디 당일 랜덤으로 선정된 발표자가 공식 문서 또는 정리한 문서를 바탕으로 발표 및 Q&A 진행

## 파일 작성 방법

- 주차 별로 `name/week-nn` branch를 만들어서 markdown file에 내용을 정리한 뒤 PR을 생성합니다.
- Markdown file 이름은 `name.md`로 합니다.
- 이미지를 사용하고 싶은 경우, `name` 폴더를 만들고 그 아래 `index.md` 파일에 내용을 정리합니다.
- 예시
  ```
  week-01
  ㄴ README.md
  ㄴ name1.md
  ㄴ name2.md
  week-02
  ㄴ README.md
  ㄴ name1
    ㄴ index.md
    ㄴ some-image.png
    ㄴ ...
  ㄴ name2.md
  ```

## 저장소 활용 방법

- 각자 스터디 전날까지 `name/week-nn` branch를 `main` branch로 병합하는 PR을 생성합니다.
- 다른 스터디원들은 자율적으로 PR에서 의견을 나눕니다.
- 스터디 당일 랜덤으로 선정된 발표자가 정리한 내용을 바탕으로 발표 및 Q&A를 진행합니다.
- 원하는 경우 다른 스티디원이 올린 PR을 함께 읽어보며 토론합니다.
- 스터디 준비 중에 생기는 질문은 'Discussion'에 남기고 자유롭게 토론합니다.

## History

|        Week        |                                                                  Subjects                                                                   |    Date    |
| :----------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :--------: |
| [01-1](./week-01/) |                                     [useActionState](https://react.dev/reference/react/useActionState)                                      | 2026.01.06 |
| [02-1](./week-02/) |                                        [useCallback](https://react.dev/reference/react/useCallback)                                         | 2026.01.14 |
| [02-2](./week-02/) |                                         [useContext](https://react.dev/reference/react/useContext)                                          | 2026.01.16 |
| [03-1](./week-03/) | [useDebugValue](https://react.dev/reference/react/useDebugValue)<br> [useDeferredValue](https://react.dev/reference/react/useDeferredValue) | 2026.01.20 |
| [03-2](./week-03/) |                                          [useEffect](https://react.dev/reference/react/useEffect)                                           | 2026.01.23 |
| [04-1](./week-04/) |           [useEffectEvent](https://react.dev/reference/react/useEffectEvent)<br> [useId](https://react.dev/reference/react/useId)           | 2026.01.27 |
| [04-2](./week-04/) |                                    [useLayoutEffect](https://react.dev/reference/react/useLayoutEffect)                                     | 2026.01.30 |
| [04-2](./week-05/) |                                            [useMemo](https://react.dev/reference/react/useMemo)                                             | 2026.02.03 |
