# PHP-array-in-average
//This function is build for PHP array value average

<?php
  $a= array(23,34,56,43,85,95,);
  $sum = 0;
  for($i=0; $i< count($a); $i++)
  {
	  $sum = $sum + $a[$i];
  }
  print $sum/count($a);
?>
