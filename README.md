# python_add_image_docx
This module helps in generating python selenium screenshot doc report.
How to use it:

from generate_screen_doc import GenerateScreenDoc

obj =GenerateScreenDoc()
obj.add_image_to_doc(heading="My First Image",image_url="pic/01.PNG")
obj.add_image_to_doc(image_url="pic/02.PNG")
obj.add_image_to_doc(heading="My Third Image",image_url="pic/03.PNG")
obj.add_image_to_doc(heading="My Fourth Image",image_url="pic/04.PNG")
obj.save_doc("./reports/test2.docx")

