Ejercicio 1

function numeros(x) {
  var arr=[]
  for(var i=1; i<=x; i++){
    arr.push(i)
    
  }
  return arr;
}
arr = numeros(255);
console.log(arr);

_________________________________
Ejercicio 2

function pares(x){
  var sum=0;
  for(var i=0; i<=x; i++){
    if( i%2 == 0){
      sum+=i;
    }
   
  }
  return sum;
}
arr=pares(1000);
console.log(arr);

_________________________________
Ejercicio 3

function impares(x){
  var sum=0;
  for(var i=0; i<=x; i++){
    if( i%2 == 1){
      sum+=i;
    }
   
  }
  return sum;
}
arr=impares(5000);
console.log(arr);

_________________________________
Ejercicio 4

function SumArr(x) {
  var sum = 0;
  for(var i=0; i<x.length; i++) {
    sum=sum+x[i]
  }
  return sum;
  
}
a=SumArr([1,2,5]);
console.log(a)

_________________________________
Ejercicio 5

function numeromayor(x) {

  var mayor=x[0]
   
  for(var i=0; i<x.length; i++) {
    if (x[i]>mayor){
      mayor=x[i];
    } 
  } 
  return mayor; 
}
a=numeromayor([-3,3,5,7] )
console.log(a);

_________________________________
Ejercicio 6

function SumArr(x) {
  var sum = 0;
  var prom =0;
  for(var i=0; i<x.length; i++) {
    sum=sum+x[i]
    
  }
  prom=sum/x.length;
  return prom;
  
  
}
a=SumArr([1,3,5,7,20] );
console.log(a)

_________________________________
Ejercicio 7

function impares(x) {
  var arr=[]
  for(var i=1; i<=x; i++){
    if( i%2 == 1){ 
    arr.push(i);
    }
  }
  return arr;
}
arr = impares(50);
console.log(arr);


_________________________________
Ejercicio 8

function mayorquey(x,y) {
  var mayor = [];
   
  for(var i=1; i<x.length; i++) {
    if (x[i]>y){
      mayor.push(x[i]);
    } 
  } 
  return mayor; 
}
a=mayorquey([1,3,5,7],3);
console.log(a);


_________________________________
Ejercicio 9

function cuadrado(x) {

  for(var i=1; i<x.length; i++) {
    x[i] = x[i]*x[i];
    
  } 
  return x; 
}
a=cuadrado([1,5,10,-2]);
console.log(a);


_________________________________
Ejercicio 10

function cuadrado(x) {

  for(var i=0; i<x.length; i++) {
    if(x[i]<0){
       x[i]=0
      
    }
   
  } 
  return x; 
}
a=cuadrado([1,5,10,-2]);
console.log(a);

_________________________________
Ejercicio 11

function a(arr){
  var max = arr[0]
  var min = arr[0]
  var prom = 0
  var sum = 0
  for (var i=0; i<arr.length; i++){
    if(max < arr[i]){
      max = arr[i];
    }
    if(min > arr[i]){
      min = arr[i];
    }    
    sum=(arr[i]+sum);
  }
    var prom = sum/arr.length;
    console.log(max);
    console.log(min);
    console.log(prom);
}
z=a([1,5,10,-2]);


_________________________________
Ejercicio 12

function intercambia(x){
  
  temp = x[x.length-1];
  x[x.length-1] = x[0];
  x[0] = temp;
  return x;  

}

a=intercambia([1,5,10,-2]);
console.log(a);


_________________________________
Ejercicio 13

function reemplazanegativo(x) {

  for(var i=0; i<x.length; i++) {
    if(x[i]<0){
       x[i]="Dojo"
    }
  } 
  return x; 
}
a=reemplazanegativo([-1,-3,2]);
console.log(a);




