#DO HOW

1. return, render
1. class, component
1. state, props
1. HOOKS //

javascript를 사용할떄 {}를 사용한다.

props, state는 일반 js객체 props는 컴포넌트에 전달됨, state는 컴포넌트 안에서 관리됨.
state를 사용하지 않는다면 function으로 선언
state는 컴포넌트 안에서 관리되기때문에 setState를 사용해야함. 데이터의 취급, this, 함수.

function 컴포넌트는 랜더링된 값들을 고정함

랜더링이란 화면에 그려내는것을 말함

class component에는 render() 매서드가 필수이며
반환하고자 하는 JSX를 반환하면 된다.
lifeCycle을 사용할 수 있다.
props 를 조회 해야 할 때에는 this.props 를 조회하면된다.

component란 리액트로 만들어진 앱을 이루는 최소한의 단위이며 하나하나의 재사용성이 있는 요소들이다.
