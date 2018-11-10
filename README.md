Sweetalert2 eklentisini PHP içersinde kullanmak için ufak bir fonksiyon


sweetalert2 js ve css kodları sayfamıza dahil edin.

fonksiyonlar.php
<?php
function Goster($mesaj,$aciklama,$durum){
    return "<script type='text/javascript'>swal ('$mesaj' ,'$aciklama',  '$durum' );</script>";    
}
?>

herhangi bi php dosyası
<?php
include "fonksiyonlar.php";

// işlemler işlemler 

echo Goster("Hoşgeldin",$kullanici,"success");

?>
