
<form action="" method="get">
     Ten: <input type="text" name= "ten">
    <br>
    Tuoi: <input type="text" name= "tuoi">
    <br>
    Dia chi:<input type="text" name= "address">
    <br>
    Que quan: <input type="text" name= "hometow">
    <br>
     Tinh trang hon nhan: <select name="married">
     	<option value="1">Doc than </option>
     	<option value="2">Da ket hon </option>
     	<option value="3">Khac </option>
     </select>
    <br>
    Gioi tinh: <input type="radio" name= "gender" value="1">Nam<br>
    			<input type="radio" name= "gender" value="2">Nu<br>
   				<input type="radio" name= "gender" value="3">Khac<br>
    Ngay sinh: <input type="date" name= "birthdate"><br>
    <button type="submit">Show</button>

</form>
<?php 

 $name= $_GET['ten'];
 $age= $_GET['tuoi'];
 $address= $_GET['address'];
 $hometow= $_GET['hometow'];
 $married= $_GET['married'];
 $gender= $_GET['gender'];
 $birthdate= $_GET['birthdate'];

 var_dump($name, $age,$addres,$hometow,$married,$gender,$birthdate);
?>
