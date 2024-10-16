# https-www.codewars.com-users-cubain-ishimwe
program on javascript
  <script>
        //program of The function should return an object with two arrays in it, one for all odd numbers and one for all even numbers.
    function splitOddAndEven(numbers) {
        let odd = [];
        let even = [];
      
        for (let i = 0; i < numbers.length; i++) {
          if (numbers[i] % 2 === 0) {
            // number is even
            even.push(numbers[i]);
          } else {
            // number is not even (=odd)
            odd.push(numbers[i]);
          }
        }
      
        // create an object with the odd and even array in it
        const returnObject = {
          odd,
          even,
        };
      
        return returnObject;
      }

      // task 2: 
      function oddEven(n){
  if (n % 2 == 1) return "odd number";
  else            return "even number";
}

function oldYoung(age){
  if (age < 16)      return "children"
  else if (age < 50) return "young man"   //use "else if" if needed
  else               return "old man"
}
    </script>
