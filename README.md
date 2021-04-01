<?php

function Fibonacci($n)
{
  
    $number1 = 1;
    $number2 = 1;
  
    $count = 0;
    while ($count < $n)
    {
        echo ' '.$number1;
        $number3 = $number2 + $number1;
        $number1 = $number2;
        $number2 = $number3;
        $count = $count + 1;
    }
}

$n = 12;
Fibonacci($n);
