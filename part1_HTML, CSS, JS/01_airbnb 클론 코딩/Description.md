# Airbnb 클론코딩
##

## CSS flex의 속성
### Item
#### flex-grow
- 할당 가능한 공간의 정도
- 형제 아이템들이 모두 동일한 flex-grow 값 = 동일한 공간
- 형제 아이템들이 다른 flex-grow 값 = 다른공간

#### flex-shrink
- 아이템 크기가 container 보다 클 때 사용
- 설정된 값에 다라 크기가 축소
- flex-shrink: 0 = 줄어들지 않겠다!

#### flex-basis
- 아이템의 초기 크기
- 'auto'가 아닌 `flex-basis`와 `width(direction: column이면 height)` 중 flex-basis가 우선

### Container
#### 방향 flex-direction
- row
- column
- row-reverse
- column-reverse

#### 정렬 justify-content, align-items
- flex-start
- flex-end
- center
- space-between
- space-around