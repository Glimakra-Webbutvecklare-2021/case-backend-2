# Case: Webbapplikation med inloggnig
I detta caset ska ni göra en CRUD webbapplikation med användare och minst en resurs. Ni har frihet att välja vad applikationen ska hantera. Några exempel är följande:

- Online Receptbook (resurs: Recept)
- Twitter à la Glimåkra (resurs: Tweet)
- Instagram à la Glimåkra (resurs: Post)
- Blocket à la Glimåkra (resurs: Ad)

## Krav

### Design minimum
* Low fidelity designskiss
* Mobile first

### Design Extra
* Logotyp
* Färgtema

### Code minimum
* En README.md i gitrepot med följande delar:
    * Introduction: Vad gör er app och vilket problem löser det?
    * Requirements & Installation: Vad behövs för att man själv ska kunna köra appen?
    * Screenshots: minst en screenshot (eller gif) som visar appen under använding
* En användare ska kunna logga in och ut
    * inloggad användare ska kunna se sin egna samling av [Resurs]
    * ej inloggad användare ska inte kunna se privata [Resurs]
* [Resurs] ska kunna läggas till, editeras och raderas av ägare.
* [Resurs] ska kunna göras privat eller publik av ägare. 
* Alla publika [Resurs] ska finnas listade för en inloggad användare
    * Privat Resurs ska endast synas för ägare
* Statusmeddelande från servern vid redirect ska visas med flash-meddelande eller query strings. Exempelvis:
    * Skapande av resurs ska visa "Successfully created" vid redirect
    * Inloggning ska visa "Successfully logged in" vid redirect
    * Felaktig inloggning ska visa "Logged in failed" vid redirect

### Code Extra
* Publicerad via Linode eller motsvarade
* Det ska vara möjligt att sätta Likes på publika [Resurs]
* Det ska vara möjligt att kommentera på publika [Resurs]

## Feedback
Veckan efter presentation kommer feedback ges under följande rubriker:

- Databas-hantering
- MVC-struktur
- Användarupplevelse
- Allmän kodstil

*Designfeedback tillkommer från Mattias*

## Presentation- och Inlämningsdatum
Presenteras och in lämning för feedback 13 december kl 8.45. Tiden 14de till 19de December är feedbackperiod då ni får feedback, ni kan under tiden jobba med er portfolio och göra klart gamla case.
