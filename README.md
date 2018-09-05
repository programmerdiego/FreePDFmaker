# FreePDFmaker
<strong>Open source LAMP web application that allows users to make free PDF files.</strong>

<strong>Motivation:</strong>
To make PDF making easier for non-technifal users. 

<strong>Build status:</strong>
The project is currently under construction. Alpha version 1.0  

<strong>Code style:</strong>
Everyone is welcome to contribute. Kindly use PSR-1 (https://www.php-fig.org/psr/psr-1/) and PSR-2 (https://www.php-fig.org/psr/psr-2/)  standards.

<strong>Screenshot:</strong>
N/A.

<strong>Tech/framework used:</strong>
Bootstrap.

<strong>Built with:</strong>
HTML, CSS. PHP, JavaScript, FPDF.

<strong>Features:</strong>
Free. User inputs data and then downloads and prints. 

<strong>Code Example:</strong>
<?php
require('fpdf.php');

$pdf = new FPDF();
$pdf->AddPage();
$pdf->SetFont('Arial','B',16);
$pdf->Cell(40,10,'Hello World!');
$pdf->Output();
?>

<strong>Installation:</strong>
Pending instructions.

<strong>API Reference:</strong>
N/A.

<strong>Tests:</strong>
Pending instructions.

<strong>How to use?:</strong>
Pending instructions.

<strong>Contribute:</strong>
Open to contributions. 

<strong>Credits:</strong>
Diego Sanchez

<strong>License:</strong>
Free. Open source.

Diego Sanchez   
