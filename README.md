# python_add_image_docx
<p>
This module helps in generating python selenium screenshot doc report.
 <ul>
   <li>Name : Saikiran Mekala </li>
   <li>Email : mskvarma2020@gmail.com </li>
   <li>Mobile : 9951456791 </li>
 </ul>  
</p>
<br/>
<p>
 <strong>Pre Requirements :</strong> 
<ol>
 <li>Install python-docx module by running below command</li>
 <li>pip install python-docx</li>
</ol>

</p> 
<strong>How to use it :</strong>
<pre>
from generate_screen_doc import GenerateScreenDoc

obj = GenerateScreenDoc()
obj.add_image_to_doc(heading="My First Image",image_url="pic/01.PNG")
obj.add_image_to_doc(image_url="pic/02.PNG")
obj.add_image_to_doc(heading="My Third Image",image_url="pic/03.PNG")
obj.add_image_to_doc(heading="My Fourth Image",image_url="pic/04.PNG")
obj.save_doc("./reports/test.docx")
</pre>
 <br/>
<strong>Output:</strong>
<p>
See test2.docx in repository
<br/>
 (OR)
 <br/>
<a href="https://github.com/saikiranvarma91/python_add_image_docx/raw/main/test.docx" title="Generate Docx" target="_blank"> 
 Click Me. 
 </a> 
</p>
