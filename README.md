#DO HOW

1. () {} []
2. return, render
3. class, component
4. state, props
5. HOOKS
6. Function 과 Class의 차이는 무엇일까요?

기존에 isLoading: true였다가 여기서 isLoading false로 바뀌면 React에서는 무슨일이 일어나나요?

await 했다가 isLoading: false로 바뀌면 container에 isLoding: false의 값, 즉 데이터를 화면에 출력해줍니다

---

여기서 async await는 왜 사용하는 것 일까요?

그리고 getMovies = async () => {
로 시작하는 것과
async function getMovies() {

}
로 하는 것의 차이는?

async await을 사용하는 이유는 axios로 불러오는 데이터를 비동기형식을 불러올때 데이터를 기다려줘야 하기 때문입니다.
일반 함수는 자신이 종속된 객체를 this로 가리키며, 화살표 함수는 자신이 종속된 인스턴스를 가리킵니다.

---

Function 과 Class의 차이는 무엇일까요?

Function문은 동적인 데이터를 다루는 state를 사용할 수 없습니다 그렇기에 컴포넌트 초기 마운트가 약간 더 빠르며 메모리 자원을 덜 사용하니 데이터를 다루는 컴포넌트를 사용할때 더욱 유용할듯 하며, state를 사용하지 못하니 좀 더 하위 컴포넌트를 작성할 때 사용하는것이 맞지 않을까 예상이 되고 return문을 이용하여 내부코드를 반환하며 React HOOK을 지원합니다.

Class문은 state를 사용할 수 있으며 함수가 아니기에 render() 함수를 사용하여 내부코드를 반환합니다 또한 lifeCycle 관련 기능을 사용할 수 있습니다 위에서 앞서 말한 맥락과 비슷하게 lifeCycle이 사용이 가능합니다.
