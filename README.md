# javascript-coding-challenges

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

   
