# FreePDFmaker
Open source LAMP web application that allows users to make free PDF files.

Motivation
To make PDF making easier for non-technifal users. 

Build status
The project is currently under construction. Alpha version 1.0  

Code style
Everyone is welcome to contribute. Kindly use PSR-1 (https://www.php-fig.org/psr/psr-1/) and PSR-2 (https://www.php-fig.org/psr/psr-2/)  standards.

Screenshots
N/A.

Tech/framework used
Bootstrap.

Built with
HTML, CSS. PHP, JavaScript, FPDF.

Features
Free. User inputs data and then downloads and prints. 

Code Example
<?php
require('fpdf.php');

$pdf = new FPDF();
$pdf->AddPage();
$pdf->SetFont('Arial','B',16);
$pdf->Cell(40,10,'Hello World!');
$pdf->Output();
?>

Installation
Pending instructions.

API Reference
N/A.

Tests
Pending instructions.

How to use?
Pending instructions.

Contribute
Open to contributions. 

Credits
Diego Sanchez

License
Free. Open source.

Diego Sanchez   
