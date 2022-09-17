<h2>Kawethra.js v3.0.0</h2>
<h3>Yeni Eklenenler!</h3>
<li>click, double click ve hover Özellikleri eklendi</li>
<li>Kullanım Basitleştirildi</li>
<h2>Documention (JS SIDE)</h2>
<table style='width:100%'>
 <tr>
   <th>Özellik</th>
   <th>Örnek</th>
   <th>Kullanım</th>
 </tr>
 <tr>
   <td>CSS</td>
   <td>kw.css.property("query","value");</td>
   <td>kw.css.background("body","red");</td>
 </tr>
 <tr>
   <td>Hide</td>
   <td>kw.hide("query","delay");</td>
   <td>kw.hide(".class",3000);</td>  
 </tr>
 <tr>
   <td>Show</td>
   <td>kw.show("query","delay");</td>
   <td>kw.show(".class",3000);</td>  
 </tr>
 <tr>
  <th>Theme</td>
  <td>kw.theme.theme</td>
  <td>kw.theme.dark</td>
</tr>
<tr>
  <th>Onload</th>
  <td>kw.onload(`function`)</td>
  <td>kw.onload(`<br>
    alert("Example")<br>
   `) </td>
</tr>
<tr>
 <th>HTML Lang</th>
  <td>setLang()</td>
  <td>kw.api.onload(`<br>
    setLang()<br>
   `) </td>
</tr>
</table>
<h2></h2>
<h3>Documention (HTML SIDE)</h3>
<table>
 <tr>
   <th>Özellik</th>
   <th>Örnek</th>
   <th>Kullanım</th>
 </tr>
 <tr>
   <td>click</td>
   <td><\button click="">Click me!<\/button></td>
   <td><\button click="alert('FRICK YEAHHHH'">Click me!<\/button></td>
 </tr>
  <tr>
   <td>dblclick</td>
   <td><\button dblclick="">Double Click me!<\/button></td>
   <td><\button dblclick="alert('FRICK YEAHHHH'">Double Click me!<\/button></td>
 </tr>
  <tr>
   <td>hover</td>
   <td><\button hover="">hover me!<\/button></td>
   <td><\button hover="alert('FRICK YEAHHHH'">hover me!<\/button></td>
 </tr>
   <tr>
  <th>Outo Change theme</th>
  <td>chanceTheme()</td>
   <td>
    <script><br>
    kw.api.onload(`<br>
    chanceTheme()<br>
   `) <br>
     </script><br>
     < body theme="dark"></body>
     </td>
</tr>
</table>
