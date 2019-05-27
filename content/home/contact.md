+++
# Contact widget.
widget = "contact"
active = true
date = 2016-04-20T00:00:00

title = "Contact"
subtitle = ""

# Order that this section will appear in.
weight = 8

# Automatically link email and phone?
autolink = true

+++

Vous pouvez me contacter directement depuis le site :  

<form action="https://formspree.io/antoine.sireyjol@gmail.com" method="POST">
  <label for="name">Votre nom: </label>
  <input type="text" name="name" required="required" placeholder=""><br>
  <label for="email">Votre adresse e-mail: </label>
  <input type="email" name="_replyto" required="required" placeholder=""><br>
  <label for="message">Votre message:</label><br>
  <textarea rows="4" name="message" id="message" required="required" class="form-control" placeholder="Feel free to write in english!"></textarea>
  <input type="hidden" name="_next" value="/html/thanks.html" />
  <input type="submit" value="Envoyer" name="submit" class="btn btn-primary btn-outline">
  <input type="hidden" name="_subject" value="Website message" />
  <input type="text" name="_gotcha" style="display:none" />
</form>   
  
  
  
    
Ou m'envoyer un e-mail :  
