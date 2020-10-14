# first_project
my first GitHub project


2015.06.30. 깃허브 처음 가입
2017.07.01. 2년만에 드디어!
2019.10.29. 또 2년이 흘렀네
2020.10.14. 또 1년이 흘렀다

# 분석함수
1.
2. Window Frame 절

`window_frame_clause`는 분석 함수가 평가되는 파티션 내의 **현재 행**을 중심으로 `window frame`을 정의합니다. `window_frame_clause`는 실제 기간 프레임(`ROWS`로 정의됨)과 논리적 기간 프레임(`RANGE`로 정의됨)을 모두 허용합니다.
`OVER` 절에 `ORDER BY` 절은 있지만 `window_frame_clause`는 없는 경우 `ORDER BY`는 암시적으로 `window_frame_clause`를 다음으로 정의합니다

```
RANGE BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW
```

