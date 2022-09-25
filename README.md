# Javascript Prototypes

Define a method on Array constructor called includesOneOf which accepts an array as a parameter. It will return true or false based on if an array contains one or more than one of the elements provided in the parameter array.
 
 As a result of this we should be able to access something like:
 
 const arr=[1, 2, 3, 4, 5, 6]
 
 arr. includesOneof([2, 8, 10]) ==>true
 
 arr. includesOneof([10, 11, 12])=>false
 
 arr. includesOneof([])=> Always false
 

 
 const arr2 = [{name:'James Bond",code":'OO7"},{name:"Edward Donne",code:"OO1"}]
 
 arr2.includesOneof([{name:"James Bond",code:'OO7'}]) ===> true
 
 arr2.includesOneof([{name:"James Bond",code:'OO7',organization: 'MI6'}]) ===> false
 

 

 const arr3 =[[1,22,33,4],[4,55,6,772]];
 
 arr3.includesOneof([[1,22,33,4]]) ===> true
 
 arr3.includesOneof([[1,33,22,4]]) ===> false
 

 <i>Acceptance criteria</i>
 
 <i>Should compare array and arrays by values</i>
 
 <li>Should handle integer,Decimal,String,Array,Object values</li>
 
 <li>Should handle empty arrays</li>
 
 <li>Arrays and objects should be compared by values</li>
