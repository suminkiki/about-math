# about-math

**개념을 이해하고, 풀이를 설명하고, 시험에서 활용하는 수학.**

중·고등학생 내신·수능 대비 자료와 수학 강의 콘텐츠를 차곡차곡 쌓는 저장소입니다. 개념 정리, 유형별 문제, 서술형 풀이, 시험 대비 세트와 강의 대본을 단원 중심으로 연결합니다.

> 현재는 초기 구조와 작성용 템플릿, 직접 만든 예시 자료가 들어 있습니다. 실제 학교 기출 자료나 완성된 강의 모음은 아직 포함하지 않습니다.

## 자료 찾기

| 필요한 자료 | 위치 |
| --- | --- |
| 전체 자료 목록 | [자료 목록](CATALOG.md) |
| 학년별 개념·문제·해설 | [중등 단원 자료](middle-school/README.md) |
| 고등 과목별 개념·문제·해설 | [고등 단원 자료](high-school/README.md) |
| 수능·모의고사 대비 | [수능 대비](exam-prep/csat/README.md) |
| 중간·기말 대비 | [시험 대비](exam-prep/README.md) |
| 강의 계획·대본·숏폼 | [강의 콘텐츠](lectures/README.md) |
| 작성용 양식 | [템플릿](templates/README.md) |
| 작성·공개 기준 | [기여 가이드](CONTRIBUTING.md) |

## 폴더 구조

```text
about-math/
├── README.md
├── CATALOG.md
├── CONTRIBUTING.md
├── middle-school/              # 재사용하는 단원별 학습 자료
│   ├── grade-1/units/
│   ├── grade-2/units/
│   └── grade-3/units/
├── high-school/               # 교육과정 → 과목 → 단원
│   ├── curriculum-2022/       # 공통수학1·2, 대수, 미적분Ⅰ·Ⅱ 등
│   └── curriculum-2015/       # 수학, 수학Ⅰ·Ⅱ, 미적분 등
├── exam-prep/
│   ├── grade-{1,2,3}/semester-{1,2}/{midterm,final}/ # 중등
│   ├── high-school/grade-{1,2,3}/semester-{1,2}/{midterm,final}/
│   └── csat/{2027,2028}/{topic-practice,mock-analysis,final-review}/
├── lectures/
│   ├── lessons/                # 정규 강의 계획·대본
│   └── shorts/                 # 짧은 개념·오개념 영상
├── assets/                     # 그림·공개용 첨부 자료
└── templates/                  # 단원·문항·시험·강의·숏폼 양식
```

위의 중괄호 표기는 경로를 줄여 쓴 것입니다. 실제 폴더는 각각 생성되어 있습니다. 비어 있는 폴더는 `.gitkeep`으로 유지합니다.

## 첫 자료 추가하기

1. `templates/unit.md`를 `middle-school/grade-1/units/linear-equations/README.md`로 복사합니다.
2. 단원 코드를 `m1-linear-equations`처럼 정하고 개념, 학습 목표, 오개념을 작성합니다.
3. `templates/problem-set.md`를 같은 단원의 `practice.md`로 복사해 문제와 해설을 작성합니다.
4. 강의는 `lectures/lessons/m1-linear-equations/README.md`에 작성하고 단원 자료를 상대 링크로 연결합니다.
5. 시험 대비 세트는 해당 학년·학기·시험 폴더에 추가하고, [자료 목록](CATALOG.md)에 등록합니다.

먼저 [일차방정식 예시](middle-school/grade-1/units/linear-equations/README.md)를 참고해도 좋습니다.

## 고등 자료 추가하기

1. `high-school/curriculum-2022/과목/units/단원명/`에 단원 자료를 작성합니다.
2. 단원 코드는 `h2022-common-math-1-quadratic-functions`처럼 교육과정과 과목을 포함합니다.
3. 내신 세트는 `exam-prep/high-school/`에, 수능 자료는 `exam-prep/csat/수능학년도/`에 둡니다.
4. 강의·숏폼도 같은 단원 코드로 연결하고 자료 목록에 등록합니다.

[이차함수 예시](high-school/curriculum-2022/common-math-1/units/quadratic-functions/README.md)를 참고하세요. 고등학교 과목은 학년에 고정하지 않으며, 교육과정이 다른 자료를 단순히 이름만 바꾸어 재사용하지 않습니다.

## 운영 원칙

- 학년별 단원은 학기와 분리합니다. 실제 시험 범위는 학교·교과서에 따라 확인하여 시험 대비 문서에 기록합니다.
- 난이도는 **기본 / 적용 / 도전**으로 표시합니다. 서술형 여부는 난이도와 별도로 기록합니다.
- 자료 상태는 **초안 / 검토중 / 공개**로 표시합니다. `공개`는 내용 검토 완료를 뜻하며, 이 저장소에 올린 초안도 인터넷에서 열람할 수 있습니다.
- 문제에는 정답뿐 아니라 풀이 근거와 자주 하는 실수를 함께 기록합니다.
- 학생 이름·성적·연락처는 올리지 않습니다. 교재나 시험지의 전체 스캔 대신 직접 만든 문항과 공개 가능한 자료를 사용합니다.

## 이용 및 출처

별도 이용 허락이나 라이선스가 없는 자료의 복제·배포·상업적 이용은 작성자에게 문의해 주세요. 외부 자료는 각 원출처의 이용 조건을 따릅니다. 공개 저장소라는 이유만으로 자유로운 재배포가 허용되는 것은 아닙니다.

## 앞으로 채울 내용

- [ ] 중1~중3 단원별 개념·대표 유형 정리
- [ ] 고등 과목별 개념·그래프 해석·서술형 자료
- [ ] 수능 학년도별 모의고사 분석·파이널 복습
- [ ] 중간·기말 대비 체크리스트 및 실전 세트
- [ ] 서술형 채점 기준과 오답 분석 자료
- [ ] 단원과 연결되는 강의 대본·숏폼 콘텐츠
