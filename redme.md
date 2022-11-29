<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Документ без названия</title>
</head>

<body>
<?php
$array = ['hello' , '2', '32', 'str' , 'fist'];
$length = count($array);
$resultArray = [];

for ($i=0; $i < $length ; $i++) { 
    
    if(strlen($array[$i])<=3){

        $resultArray [] = $array[$i];

    }

}
var_dump($resultArray);


?>



</body>
</html>
