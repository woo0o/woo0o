- JSX

```javascript
fucntion App() {
  return hi
}
```


1. class넣을때는 무조건 className을 쓴다
 
```javascript  
  <div className="App"> 
```
    

2. 변수넣을땐 {중괄호} 
    
```javascript 
function App() {
    
    let post = '가제'
    
  return (
    <div>
    <h3>{post}<h3>
    <div>
  );  
}
```
      
      
3. style 넣을땐 style={}
   stlye넣을땐 style={{스타일명:'값'}}
      
중간에 값넣을때 -기호는 자바스크립트가 -(빼기)로 인식하기때문에
font-size > fontSize 처럼 카멜케이스이용해서 고치기
      
      
 
      
 3줄요약 
 1. class넣을때는 무조건 className을 쓴다
 2. 변수넣을땐 {중괄호} 
 3. stlye넣을땐 style={{스타일명:'값'}}

