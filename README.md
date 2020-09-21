# 시작이 반인가.

- `python` code 를 올린다. text로부터 유용한 정보를 추출하기 위한 모듈 제작이 목적이다.
- 입력은 html, 출력은 text info 타입
- text info 타입의 객체는 다음의 attribute를 포함한다.
    - (빈도수 weighted) word tree = numpy 어레이 dtype=str
    - 신빙성 지수값 = [0 ~ 1] dtype=float
    - author = str
    - 저자의 의도 혹은 목적 코드 = ?
- text info 타입의 객체는 다음의 method를 제공한다.
    - 각 attr의 근거 값 출력
    - 모듈 외부에서 관점값을 입력받아 결과를 출력
    - 텍스트를 읽는 목적을 입력받아 목적합리성 지수출력
    
