<?php
    //Die E-Mail Adresse, an die die Kontaktanfragen gesendet werden
    $empfaenger = "klanghaus29@gmail.com";
    if(isset($_REQUEST["submit"])){
        if(empty($_REQUEST["name"]) || empty($_REQUEST["email"]) || empty($_REQUEST["nachricht"])){
            $error = "Bitte f&uuml;llen Sie alle Felder aus";
        }
        else{
            //Text der E-Mail Nachricht
            $mailnachricht="Sie haben eine Anfrage über ihr Kontaktformular erhalten:\n";
            $mailnachricht .= "Name: ".$_REQUEST["name"]."\n".
                      "E-Mail: ".$_REQUEST["email"]."\n".
                      "Datum: ".date("d.m.Y H:i")."\n".
                      "\n\n".$_REQUEST["nachricht"]."\n";            
            //Betreff der E-Mail Nachricht
            $mailbetreff = "Neue Kontaktanfrage von ".$_REQUEST["name"]." (".$_REQUEST["email"].")";
            //Hier wird die E-Mail versendet
            if(mail($empfaenger, $mailbetreff, $mailnachricht)){
                //Text den der Seiten Besucher nach dem Versand sieht
                $success = "Wir haben Ihre Anfrage erhalten und werden sie so schnell wie möglich bearbeiten. <br>";
            }
            else{
                $error = "Beim Versenden Ihrer Anfrage ist ein Fehler aufgetreten! Versuchen Sie es bitte später nocheinmal";
            }
        }
    }
?>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&family=Raleway&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css" >
    <link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/grids-responsive-min.css">
    </head>
<body>
    <!-- HEADER DU SITE -->
    <header>
        <h1>La ruche</h1>
    </header>
    <!-- FIN DE HEADER -->
    <!-- NAV -->
    <nav>
        <ul>
            <li>
                <a href="index.html" class="lien-principal">Accueil</a>
            </li>
            <li>
                <a href="expositions.html" class="lien-principal">Expositions</a>
                <ul class="sous-menu">
                    <li><a href="peintures.html" class="lien-sous-menu">Peintures</a></li>
                    <li><a href="sculptures.html" class="lien-sous-menu">Sculptures</a></li>
                    <li><a href="photographies.html" class="lien-sous-menu">Photographies</a></li>
                </ul>
            </li>
            <li>
                <a href="artistes.html" class="lien-principal">Artistes</a>
            </li>
            <li>
                <a href="contact.html" class="lien-principal">Contact</a>
            </li>
        </ul>
    </nav>
    <!-- FIN DE NAV -->
    <!-- MON CONTENU -->
  <div id="kontaktformular">
    <?php if(isset($success)){
        echo "<div>".$success."</div>"; 
    } 
    else { ?>
    <form id="kontaktform" action="" method="post" class="pure-form pure-form-aligned">
        <fieldset>
            <div class="pure-control-group">
                <label for="name">Name</label>
                <input id="name" name="name" required size="40" placeholder="Name">
            </div>
            <div class="pure-control-group">
                <label for="email">E-Mail</label>
                <input id="email" name="email" type="email" required size="40" placeholder="E-Mail">
            </div>
            <div class="pure-control-group">
                <label for="nachricht">Nachricht</label>
                <textarea id="nachricht" name="nachricht" required cols="39" rows="10" placeholder="Nachricht"></textarea>
            </div>
            <div style="float:right;font-size: 50%; text-align: right">by <a href="https://www.devno.com/kontaktformular">devno</a></div>
            <div style="clear:both;"></div> 
            <div class="pure-control-group">
                <label for="submit"></label>
                <button id="submit" name="submit" type="submit" class="pure-button pure-button-primary" onsubmit="validateForm()">Absenden</button>
            </div>
        </fieldset>  
    </form>
    <script>
        function validateForm(){
            var form = document.getElementById("kontaktform");
            return form.checkValidity();
        }
    </script>
    <?php 
    } 
    if(isset($error)){
        echo '<div class="error">'.$error.'</div>'; 
    } ?>
</div>
    <!-- FIN DE CONTENU -->
    <!-- FOOTER -->
    <footer id="galerie-footer">
        <p>La Ruche | &copy; 2020</p>
        <ul>
            <li><a href="" class="lien-footer">CGV</a></li>
            <li><a href="" class="lien-footer">Mentions légales</a></li>
            <li><a href="" class="lien-footer">Contact</a></li>
        </ul>
    </footer>
    <!-- FIN DE FOOTER -->
</body>
</html>
