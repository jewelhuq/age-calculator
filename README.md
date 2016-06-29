# age-calculator
I have a simple website to find out your age today .
I used the following code to figure out today your age in day,month and year

 $date = new DateTime($date);
 $now = new DateTime();
 $interval = $now->diff($date);
 echo"<h2 align=center>Today Your age : $interval->y Year $interval->m month  $interval->d days";

http://www.todaymyage.com
