<p> Python and MySQL, you'll need to use a MySQL connector library. One of the commonly used libraries is <br><strong>mysql-connector-python </strong></p>
so First , intall the Library<br>
1. Install Command: 
<h4>  pip install mysql-connector-python</h4>

2. Establish a connection
<h4>  
  connection = mysql.connector.connect(
        host='your_host',              
        database='your_database',
        user='your_username',
        password='your_password'
    )
</h4>
3. Create a cursor object
<h4>  cursor = connection.cursor()</h4>
