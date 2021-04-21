# gmail
Send Mail via a GMAIL account in TMINC PHP EXTENSION.
Import this Library on the Page where you want to use it by PHP EXTENSION meta() function.
Open string.php file in root directory and
 Define variables as of below.
    $gmail_username = "-- YOUR GMAIL ID --";
    $gmail_password = "-- YOUR GMAIL PASSWORD --";
    $gmail_from = "-- SET FROM MAIL --";
    FROM MAIL: This will be visible to mail recievers af "From" mail.
    
    
   #How to send Mail?
   After importing, use gmai() function to send mail.
   Parameters in gmail()
   gmail("--TO / RECIEVERS E-MAIL ADDRESS --", "-- MAIL SUBJECT --", "-- MAIL BODY (Can accept HTML)--");
   
   
