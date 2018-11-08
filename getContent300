<?php
/* получаем ID персоны */
$options=300;
$res = $modx->getObject('modResource',$idr); /* получен объект ресурс */
$input= $res->get('content');
$options = !empty($options)?$options:300;/*число букв оставляется  */
if (!empty($input) && !empty($options)) {
  if (strlen($input) > $options) {
    $output = substr($input, 0, strrpos(substr($input, 0, $options), '.'));
  } else{
    $output = $input;
  }
}

print $output;
