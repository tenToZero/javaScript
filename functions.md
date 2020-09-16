function multiply(num) {
  return function(x) {
    return x * num;
  } 
}
const triple = multiply(3);
triple(10); // 30
triple(50); // 150
