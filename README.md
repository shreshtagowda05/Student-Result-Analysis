Student Result Analysis


At first we will create a virtual environment.
The first library that we will be creating is streamlit.

And then we have to install the pandas.

And then we will install streamlit option menu

Student.py

After installing all the applications. We will create a file name called student.py

And in that page we will do page configuration at the first.
We will add a page title as student result analysis of the website.
As well as we will add an heading called student result analysis. 

Now our streamlit page is ready by setting layout and page configuration.

SIDEBAR

Now we will make changes in sidebar.

And we will take the header and upload dataset.(By writing the function)
By this we created a space in sidebar where we can upload the files of the data set.

And now we need to make an option menu. And in that we can add options 
	◦	Raw data
	◦	Student result
	◦	Topper
	◦	Search student
	◦	Subject analysis
	◦	Pass/fail
	◦	Pivot table

And we will also put icons for the above options.

Next we will make sure the file exist or not Soo by adding a if condition we will get a warning message if the file is not existed.


Read Data

We will create a data frame in which it will make sure to read the uploaded file.

We will take the if statement which makes if selected data is raw data we will get a sub header as a raw data.

And then when we upload a file. The raw data will be displayed. 

After this

Student results

We will make sure the student result will be displayed in a very good way

Soo we will use a Elif condition and take student result from the sidebar for the location.
Then we will make sure the total of the data frame will be grouped by name and marks 
Same for the average will be grouped by name and marks. 

After writing this code we will get the completely sorted section in the student results location from the sidebar. 

Topper

We will use the elif tag again by mentioning topper 
And we will get the total from the data frame and group it by name and marks by sorting the values in descending order.

And we will make sure yo mention that we need a single topper.
And we will make sure that it will ask how many students we want in the top. 

Search student

Again we will use elif by mentioning search student 
We will put a text tag which says enter a student name. 
We will make sure to put a code where user input doesn’t matter by putting capital or small letters. 
Soo that we will get it filtered. 

And we will put a if condition saying that after filtered if there is no empty then it will display as showing result by the name and their marks and average. 

If we search a name we should get all the details from the data set.( by getting total,avg and marks ) 

If the if condition is not able to find the student name then it will show student not found. 

Subject Analysis: 

We will use a elif and mention subject analysis. 
We will group subject and their average from the data set which will show marks and subject name. 

We will also make sure subject wise average is also shown. 

Pass/Fail

We will make sure pass or fail students.

Where passing marks is based on each different schools or university

Soo we will make sure to give the passing marks selection for the users itself.

Soo that the answers which we will get will be correct. 
We will apply if condition and make sure to get the passing and failing marks and make sure that the students names get visible.

Pivot Table

We will use the elif condition by mentioning pivot table. 
And write the code for it . 
Which will show student vs subjects.
