<?php
//$id100 = array("Khalifah", 21,KSA);

//$id100 = array("name" =>"Khalifah",
//  "age" =>  21,
//    "Country" =>"KSA");
//
//
//echo "<pre>";
//echo "<h1>";
//print_r ($id100);
//echo $id100[age];
//echo "</pre>";
//echo "</h1>";

//------------------------
//array inside arrays school with classes
//$school =array(
//    "class1"=>array(  "class1"=>array("ali","ahmed","mazen"),"ahmed","mazen"),
//    "class2"=> array("saleh","khalid","rahsed"),
//    "class3"=> array("khalifah","mohhamed","nawaf"),
//    "class4"=> array("malek","rami","adnan")
//    
//);
//echo "<pre>";
//print_r($school);
//echo "<pre>";

$school =array(1, 2, 3 ,4 ,5 );
echo "<pre>";
echo "<h1>";
print_r($school);
foreach($school as $value){
  echo  $value . "<br />";
}
echo "<pre>";
echo "</h1>";
?>

