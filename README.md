# OnlineLibrary

ONLINE LIBRARY




Objective:-

The main objective of Online Library  is to manage where admin can add students and books , can issue and return books and also view the statistics of issued & returned books. The project is totally built at administrative end and thus only admin is guaranteed the access. The purpose of the project is to built an application program to reduce the manual work.




Functional  Requirements:-

Admin:

       o	Can Login

       o	Add Students

       o	Add Books

       o	Issue Books

       o	Return Books

       o	View Statistics

       o	Can Logout








Software Specificatios:-

              Operating System   	 : 	Windows 10/x-64

              Languages  		 : 	java 

              Front End	   	 : 	Swing

              Platform		 : 	NetBeans IDE 8.2

              Backend                             : 	MySQL








Classes of Library:-

               o	Student class-Manages all the information about students.

	                    New Student

               o	Book Class-Manages all the information about books.

	                    New Book

	                    Issue Book

	                    Return Book







Classes and their attributes:-

              o	Student attributes: studentId,name,fatherName,courseName,branchName.

              o	Book attributes: bookIdname,publisher,price,publishYear.

              o	Issue attributes: bookId,studentId,issueDate,dueDate,returnBook.







CLASS DIAGRAM



![](library/classdiagram.png)
























 





ACTIVITY DIAGRAM


![](library/activitydiagram.png)






	



















DATAFLOW DIAGRAM


![](library/dataflowdiagram.png)


























ER DIAGRAM


![](library/erdiag.png)





















	






SEQUENTIAL DIAGRAM


![](library/collaborationdiag.png)
























How Project Works  

When we run the login file,a window will get open.



![](library/loginpage.png)


Write name and password: It must be admin for name and admin for password.
 


![](logindetail.png)



On logging in ,a home page gets open.



![](library/homepage.png)



Click on New Student Button.



![](library/newstudent.png) 



Fill the required details,



![](library/newstudentdetail.png)
 

![](library/addstu.png)

 




Now, click on New Book Button and fill the required details.



![](library/newbook.png) 



![](library/bookadded.png) 



To issue book, click on Issue Book Button. Also , fill the details.   


![](library/issuebook.png)
 


![](ibrary/issued.png)



To return book,click on Return Book Button.


![](library/returned.png)



Click on Statistics Button to view statistics of issued and returned book.



![](library/statstics.png)



To logout,click on Logout button.



