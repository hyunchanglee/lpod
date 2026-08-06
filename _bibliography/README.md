# 논문 목록 관리 방법

`papers.bib` 파일 하나만 수정하면 `/publications/` 페이지가 자동으로 갱신됩니다.

## 논문 추가

1. Google Scholar에서 논문 검색 → 인용(따옴표 아이콘) → **BibTeX** 클릭
2. 나오는 텍스트를 복사해서 `papers.bib` 맨 위에 붙여넣기
3. 저장 후 GitHub에 push

## 사용 가능한 추가 필드

| 필드 | 설명 |
| --- | --- |
| `selected = {true}` | 첫 페이지(연구실 소개)의 대표논문 목록에 표시 |
| `bibtex_show = {true}` | BibTeX 보기 버튼 생성 |
| `abbr = {JPP}` | 목록 왼쪽에 표시되는 저널 약칭 배지 |
| `preview = {paper1.png}` | 미리보기 이미지 (`assets/img/publication_preview/` 에 저장) |
| `pdf = {paper1.pdf}` | PDF 링크 (`assets/pdf/` 에 저장하거나 전체 URL) |
| `doi = {10.xxxx/xxxxx}` | DOI 링크 |
| `html`, `video`, `code`, `poster`, `slides` | 각각 해당 버튼 생성 |
| `award = {Best Paper Award}` | 수상 표시 |

## 저자 이름 강조

`_config.yml` 의 `scholar:` 항목에 본인 이름이 등록되어 있으면 목록에서 굵게 표시됩니다.

```yaml
scholar:
  last_name: [Lee, 이]
  first_name: [Hyunchang, H.C., H., 현창]
```

## 정렬

기본은 연도 역순입니다. `@string` 으로 저널 이름을 미리 정의해두면 반복 입력을 줄일 수 있습니다.
