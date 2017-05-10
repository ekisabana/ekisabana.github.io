<?php
include "function.php";

$XmlToJson = new XmlToJson();
$json = $XmlToJson->Parse('http://aviation.bmkg.go.id/latest/observation.x.xml.php');
echo $json;
