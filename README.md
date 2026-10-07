# fromshim 마켓플레이스

[English](README.en.md)

fromshim 제품을 한곳에서 설치하는 Claude Code 플러그인 카탈로그다.

## 설치

```
/plugin marketplace add fromshim/marketplace
/plugin install korean-tone@fromshim
/plugin install git-graph@fromshim
```

## 제품

| 이름 | 설명 | 저장소 |
| --- | --- | --- |
| korean-tone | 모든 한국어 답변을 자연스럽게 다듬는다. default·easy·mz 모드와 문서 린터 훅이 함께 설치된다. | [fromshim/korean-tone](https://github.com/fromshim/korean-tone) |
| git-graph | 터미널 옆 패널에 지금 저장소의 git 그래프를 실시간으로 그린다. | [fromshim/git-graph](https://github.com/fromshim/git-graph) |

각 제품은 자기 저장소에서 개발한다. 이슈와 릴리스도 그쪽에 남긴다. 이 저장소는 목록만 가진다.

## korean-tone을 먼저 쓰던 분께

예전에는 `fromshim/korean-tone` 저장소 자체가 `fromshim`이라는 이름의 마켓플레이스였다. 지금 그 저장소의 마켓플레이스 이름은 `korean-tone`으로 바뀌었다. 아래 순서로 옮긴다.

```
/plugin marketplace remove fromshim
/plugin marketplace add fromshim/marketplace
```

필요하면 `/plugin install korean-tone@fromshim`으로 다시 설치한다.
