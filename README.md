тут содержится интерпритатор для языка программирования XS и javadoc к нему. подробности в javadoc. 

проект на языке xs: https://github.com/iv-g-ru/XScmd

ПРИМЕР:
 <pre>
   var[a]
   var[b]
   set[a|10]
   set[b|20]
   +[result|a|b]
   pr[result]
 </pre>

 <pre>
   ::cm sum
       var[result]
       +[result|arg0|arg1]
       pr[result]
   ::end
   sum[1|6]
 </pre>
 
 <pre>
   arr[arr|5]
   arrset[arr|0|42]
   arrget[arr|0|value]
   pr[value]
 </pre>
 
 </pre>
 
(синтаксис настраиваемый, разширяемый, более подробно о настройке и резширении в javadoc)
