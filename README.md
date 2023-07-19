# javascript-coding-challenges

   > Click :star: if you like the project and follow me on LinkedIn [@RameshKumar](https://www.linkedin.com/in/ramesh-kumar-choudhary/) for more updates.


   ## JavaScript Coding Challenges and Interview Question list available here :-

   >1. Click here for [Javascript Basics Coding](https://github.com/rseetech/javascript-basics) more information.
   >  
   >2. Click here for [Javascript Coding Challenges](https://github.com/rseetech/javascript-coding-challenges) more information.


   ## React Coding Project list available here :-

   >1. Click here for [React Interview Questions & Answers](https://github.com/rseetech/React-interview-questions) more information.
   >
   >2. Click here for [React Routing Axios Search Counter App Using MUI](https://github.com/rseetech/react-routing-axios-search-counter-app-using-mui) more information.
   >
   >3. Click here for [React Routing Pass data Child to Parent](https://github.com/rseetech/react-router-axios-pass-data-child-to-parent) more information.
   >
   >4. Click here for [React Create Tic Tac Toe Game](https://github.com/rseetech/react-create-tic-tac-toe-game) more information.






1. ###
   function charCheck( val1, val2){
 
     let value1 = val1.length;
     let value2 = val2.length;
     
     if(value1 !== value2){
     console.log("not matching")
     return
     }
     
     let char1 = val1.toLowerCase().split('').sort().join('');
     let char2 = val2.toLowerCase().split('').sort().join('');
     
     if(char1 === char2){
     console.log("matching")
     } else {
     console.log("Not matching");
     }
    }
    
    charCheck("Apple","papel");

   
