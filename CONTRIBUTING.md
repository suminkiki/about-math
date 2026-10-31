# 자료 작성 가이드

## 경로와 이름

- 경로는 소문자 영문과 하이픈을 사용하고 본문은 한국어로 작성합니다.
- 단원 코드: `m1-linear-equations`처럼 학년과 주제를 조합합니다. 교과서 단원 번호를 공통 코드로 사용하지 않습니다.
- 단원 경로: `middle-school/grade-1/units/linear-equations/`.
- 시험 파일: `2027-sample-school-set-01.md`. `sample-school`은 가상 예시이며 실제 학교명이나 출처를 의미하지 않습니다.
- 강의 경로: `lectures/lessons/m1-linear-equations/README.md`.
- 이미지: `assets/images/m1-linear-equations/balance-01.png`.
- 한 단원의 개념은 `README.md`, 연습은 `practice.md`, 해설을 분리할 경우 `solutions.md`에 둡니다.

고등 단원은 `high-school/curriculum-2022/과목/units/단원명/`에 두고 `h2022-과목-주제` 코드를 사용합니다. 2015 개정 자료는 `curriculum-2015`와 `h2015`로 구분합니다. 강의와 이미지에도 같은 코드를 사용합니다.

고등 내신은 `exam-prep/high-school/grade-N/semester-N/시험/`, 수능은 `exam-prep/csat/수능학년도/자료유형/`에 둡니다. 시행 연도와 수능 학년도를 구분해 적습니다.

## 작성 흐름

1. 적절한 템플릿을 복사하고 모든 `작성 필요` 항목을 채웁니다.
2. 단원 코드와 대상 학년, 교육과정, 출처, 상태를 기록합니다.
3. 문항 번호와 해설 번호를 맞추고 다른 풀이로 정답을 검산합니다.
4. 서술형에는 배점 합계와 부분점 기준을 제시합니다.
5. 링크·수식·이미지 표시를 확인하고 `CATALOG.md`에 등록합니다.
6. 초안 → 검토중 → 공개 순으로 상태를 갱신합니다.

Markdown 수식은 인라인 `$x+1$`, 별도 줄 `$$...$$`를 사용합니다. 이미지에는 내용을 설명하는 대체 텍스트를 넣습니다.

## 공개 전 확인

- [ ] 계산·조건·정답·해설이 서로 일치한다.
- [ ] 교육과정·교과서별 범위를 확인했다.
- [ ] 외부 문항·그림은 출처와 공개 이용 허락을 확인했다.
- [ ] 학생 개인정보와 비공개 학교 자료가 없다.
- [ ] 상대 링크가 열리며 미작성 항목이 남아 있지 않다.

## 커밋 예시

`docs: initialize about-math learning materials`

`content: add m1 linear equations practice`

`fix: correct solution for question 03`

검토자는 본인 재검토 또는 동료 검토 여부를 문서에 기록합니다. 아직 라이선스를 정하지 않았으므로 저장소 전체에 임의의 오픈소스 라이선스를 추가하지 않습니다.
