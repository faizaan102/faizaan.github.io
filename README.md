<html>
 <body>
 <form name="iai">
 <h1>application form for addmission of ITI-2025</h1>
 
 enter student name:<br>
 <input type="text" id="n"><br>
 
 enter student father name:<br>
 <input type="text" id="f"><br>
 
 enter student dob:<br>
 <input type="date" id="d"><br>
 
 enter your photo:<br>
 <input type="file" id="p"><br>
 
 enter your address:<br>
 <textarea rows="4" cols="50">type address here</textarea><br>
 
 enter student mobile no:<br>
 <input type="text" id="m"><br>
 
 enter student e-mail:<br>
 <input type="text" id="e"><br>
 
 enter student uid (aadhar no):<br>
 <input type="text" id="u"><br>
 
 select your gender:<br>
 <input type="radio" value="gender" name="g">Male<br>
 <input type="radio" value="gender" name="g">Female<br>
 
 select your catagory:<br>
 <input type="radio" value="catagory" name="catagory">sheduled cast<br>
 <input type="radio" value="catagory" name="catagory">sheduled tribes<br>
 <input type="radio" value="catagory" name="catagory">other backward cast<br>
 
 select your qualification:<br>
 
 <input type="checkbox" value="sslc">sslc<br>
 <input type="checkbox" value="puc">puc<br>
 <input type="checkbox" value="ITI">ITI<br>
 
 enter student sslc obtained marks:
 <input type="text" id="z"><br>
 
 percentage:<br>
 <input type="text" id="pr"><br>
 <input type="button" value="cal per" onclick="per"><br> 
 
 select your following option:><br>
 <input type="checkbox" id="r" onclick="s()">rural 10% <br>
 <input type="checkbox" id="u" onclick="d()">urban 0% <br>
 
 revised percantage:<input type="text" id="rp"><br>
 select your trade:<br>
 <select id="item" onchange="itm()">
 <option value="copa">copa</option>
 <option value="em">em</option>
 <option value="electrician">electrician</option>
 <option value="fitter">fitter</option>
 <option value="mr ac">mr ac</option>
 
 </select>
 <input type="submit" value="submit">
 
 </form>
 <script>
 function per()
 {
 var z=parseInt(document.iai.z.value);
 var pr=(z/625)*100;
 document.iai.pr.value=pr;
 }
 </script>
 </body>
 </html>
 
