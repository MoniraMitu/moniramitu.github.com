<html>
  <head>
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
	 <style>
	    level{ 
		color:red;
		}
		form{
		background-color:yellow;
		}
		table{
		background-color:pink;
		}
	 </style>
  </head>
  <body>
      <table class="table table-hover">
	  <tr>
	    <th>Name</th>
		<th>ID</th>
		<th>Contact NO</th>
	</tr>
	<tr>
       <td>Samira Setu</td>
       <td>123456</td>	
       <td>1568694541687</td>	   
	</tr>
	<tr>
       <td>Mitu</td>
       <td>32164</td>	
       <td>852741963</td>	   
	</tr>
	<tr>
       <td>Innaya</td>
       <td>159753</td>	
       <td>15686945416</td>	   
	</tr>
	<tr>
       <td>Mahir</td>
       <td>12345696</td>	
       <td>15686945000</td>	   
	</tr>
	<tr>
       <td>Sami</td>
       <td>12345</td>	
       <td>15686945411</td>	   
	</tr>
    </table>
	  <form>
	 <level >Name</level> 
      <input class="form-control" type="text" placeholder ="write name" autofocus="autofocus"/>
	  <br>
	  <level>ID</level>
	  <input class="form-control"type="text"/>
	  <br>
	  <level>Contact No</level>
	  <input class="form-control" type="text"/>
	  <br>
	  <level>Password</level>
	  <input class="form-control"type="password/>"
	  <br>
	  <level>Gender</level>
	  <br>
	  <level>Male</level>
	  <input name="sex"type="radio"/>
	  <br>
	  <level>Female</level>
	  <input name="sex" type="radio">
	  <br>
	  <br>
	  <level>blood group</level>
	  <br>
	  <level>A+</level>
	  <input name="bg"type ="radio"/>
	  <br>
	  <level>B+</levl>
	  <input name="bg"type="radio"/>
	  <br>
	  <level>AB+</level>
	  <input name="bg" type="radio"/>
	  <br>
	  <br>
	  <input class="btn-success" type="Submit"/>
	  <input  class="btn-danger"type="Reset"/>
	  </form>
   </body>
</html>
