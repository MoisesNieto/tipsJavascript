# tipsJavascript


### Primer tips eliminar valores repetidos de un array usando el array methods ***filter*** 
~~~
  const array = [12, 34, 56, 12, 54, 54];
  
  let newArray = array.filter((element , index, array)=>{
    return index === array.indexOf(element)
  });
  
  
 
~~~

### segundo  tips eliminar valores repetidos de un array usando el Objeto  ***Set*** 

~~~
  const  array = [12, 34, 56, 12, 54, 54];
 
  let newArray = Array.from (new Set (array))
~~~
