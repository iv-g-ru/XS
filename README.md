ENG: (English language documentation may not be complete. For javadoc, you can use Google Translate.)

This contains an interpreter for the XS programming language and its Javadoc. Details are in Javadoc. The XS documentation is in engxsdoc.txt.

XS project: https://github.com/iv-g-ru/XScmd

Running an XS program without creating your own Java program that uses XS: java -jar "path to XS.jar file" path_to_XS_code path_to_set_of_commands (or 0) arguments_to_XS_program arguments_to_XS_program ...

Syntax for Notepad++: xs.xml (in Notepad++, Syntax > Custom Syntax > Set Custom Syntax > Import)

The compact size of the JAR will also ensure faster startup and JIT compilation. Current size: 48.1 KB (49,274 bytes)

XS programs in silent mode can do anything the operating system command line or any Java program can.

More details about the language's capabilities are available in xsdoc.txt

Instructions for using javaodc.rar: 1- unzip the archive, 2- open the index.html file, 3- congratulations, you've opened Javadoc.

EXAMPLE:
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

(The syntax is customizable and extensible; more details on customization and extensibility are in the Javadoc)



RU:

тут содержится интерпретатор для языка программирования XS и javadoc к нему. подробности в javadoc. документация по языку XS в xsdoc.txt.

проект на языке xs: https://github.com/iv-g-ru/XScmd

запуск программы на XS без создания собственной программы на java используйщей XS: java -jar "путь к фалйу XS.jar" путь_к_XS_коду путь_к_набору_команд(или 0) аргументы_программе_XS аргументы_программе_XS ...

синтаксис для notepad++ : xs.xml (в notepad++ синтаксисы > польз. синтаксис > задать свой синтаксис > импорт)

компактность jar так же обеспечит более высокую скорость запуска, и jit компиляции. вес на текущий момент: 48,1 КБ (49 274 байт)

программы на XS в громком режиме способны выполнять всё что способна выполнять командная строка операционной системы или любая java программа

более подробно о возможностях языка написано в xsdoc.txt 

инструкция по использованию javaodc.rar : 1- распакуйте архив, 2- откройте файл index.html, 3- поздравляю, вы открыли javadoc 

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
