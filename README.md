# elapsedTime 
## index.html
- HTML tag에 표시된 시간 정보(예: 포스팅 날짜 시간)를 현재 기준으로 경과된 시간으로 변환하여 표시하는 테스트 코드
- sibling 태그를 클릭하면 한 단계 위로 위치를 옮기는 테스트 코드도 포함함

## getSetStyleTest.html
- element의 스타일 속성을 elem.style.left 와 같은 형식으로 읽어 올 수 있는 경우는 inline 스타일 설정, script 설정의 경우만 가능.
- embed, external 스타일의 경우는 window.getComputedStye(elem, null).getPropertyValue(property)형식으로 가져오기 가능함.
