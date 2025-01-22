# 마진 상쇄(Margin Collapsing)
- 나열된 두 엘레먼트 사이의 간격을 너무 멀지 않게 유지 하기 위해서 마진이 더 큰 쪽으로 덮어쓰기되는 CSS에서 강제로 수행하는 작업
- margin-top, margin-bottom을 사용하여 상쇄를 막을 수 있다.

# 인라인 요소와 블럭 요소
- 인라인 요소 : 전체 너비를 사용하지 않는다. width, height, margin top/bottom을 설정할 수 없다. ex) <a>, <span>, <img>
- 블럭 요소 : 전체 너비를 사용한다. ex) <div> , <section> , <article> , <nav>, <h1>, <h2> , <p>
- 인라인 블럭 : 인라인 요소처럼 각 요소가 나란히 위치하지만, 블럭 요소처럼 margin 설정을 할 수 있다.