<?php

   $name = $_POST['name'];
   $visitor_email = $_POST['email'];
   $message = $_POST['message'];



   $email_from = '';

   $eamil_subject = "";

   $email_body = "User Name: $name.\n".
                    "User_Email: $visitor_email.\n".
                        "User Message: $message.\n";



    $to = "";
    
    $headers = "Form: $email_from \r\n";

    $headers .= "Reply-To: $visitor_email\r\n";

    mail($to,$eamil_subject,$email_body,$headers);

    header("Location: index.html");

?>
