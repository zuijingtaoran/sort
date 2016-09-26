# sort
```
var arr = [1,3,55,23,11,12,6,2,19,15,7]
console.log(arr.sort(function (x, y) {
   
    if (x > y) {
        return -1;
    } if (x < y) {
        return 1;
    }
   
}))
//=======冒泡正排序
var sort=function(array){
var i = 0, len = array.length, j, d; for(; i<len; i++){ 
for(j=0; j<len; j++){ 
console.log(array[i] +'['+i+']_'+ array[j]+'['+j+']    '+array.join(','));
if(array[i] > array[j]){ console.log('_');
d = array[j]; array[j] = array[i]; array[i] = d; 
} 
} 
}
return array;
}
sort([6,3,2,1,4]);
```
打印部分供自己参考
