# CSS_Layout
CSS 배치에 대한 공부 내용

## Position
### 글의 흐름에 상관없이 배치하고 싶을 때
#### static
- Position의 기본값
- 기본적인 글의 흐름

#### relative
- 원래 있어야할 위치를 기준으로 배치
- ex) position: relative; left: 50px; --> 원래 있어야할 위치에서 왼쪽에서 50px 이동

#### absolute
- 가장 가까운 포지셔닝이된 조상 요소를 기준으로 배치

#### fixed
- 브라우저 화면을 기준으로 배치

#### sticky
- staic처럼 배치되다가 설정한 브라우저 화면 위치에 닿으면 fixed로 바뀜
  
## FlexBox
### 일차원으로 배치하는 방법 --> 가로로 배치하거나, 세로로 배치하거나
- 배치할 방법을 정한다. --> flex-direction
- 배치할 위치를 정한다 --> justify-content, align-items
- 요소가 넘칠 때 어떻게 배치할지 --> flex-wrap
- 요소의 간격은 얼마나 줄지 --> gap 
- 크기를 어떻게 늘이거나 줄일지 --> flex-grow, flex-shrink, flex-basis

#### 정렬 방향
- 기본축: 정렬 방향 --> justify-content
- 수직축: 정렬 방향의 수직 방향 --> align-items

#### 요소가 넘칠 경우
flex-wrap: wrap; --> 교차축 방향으로 정렬
## Grid
