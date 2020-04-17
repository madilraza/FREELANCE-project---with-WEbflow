# FREELANCE-project---with-WEbflow
# Project requirements
Necessary requirements for the freelancer are that he or she has extensive experience with Webflow
and the configuration of existing templates, the implementation of CRM systems .
The bid should not be changed after the offer since every requirement is listed below.
The freelancer should take the responsiveness of the website into account.
That the freelancer communicates the planned approach and necessary plugins in his or her offer
and asks questions regarding the project before the project starts.
It is especially important that the freelancer uses the building blocks and elements from the template
in order to create new elements, otherwise other elements on the website can be affected too.

# Project background
We purchased the Webflow template from Panels (https://panels-template.webflow.io/) and are
currently looking for someone who can create the necessary backend in order for us to sign up users
and post job listings.
Our website has most of the subpages already implemented and can be viewed over this link:
https://taus-sassa.webflow.io/
The single subpages are already created.
# Project description

The project is consists of smaller tasks which are described in the following:
1. Implement a sign up and sign in functionality with all the necessary settings on Webflow and if
necessary external plugins. We want users to be able to sign up, sign in, change their email,
password, apply for jobs etc.

# Part 1:
That’s the header (before the user signs in).
That should be the header after a user signs in.
The button “Anmelden” (Sign in) changes to “Abmelden” (Sign out) and the button “Berater
werden” (Become a Consultant/Sign up) to “Mein Profil” (My profile).
Important: If someone is not signed in and clicks on “Projekt finden” he or she should be
redirected to the “Anmelden” page. Only signed in users are allowed to see that page.
# Part 2:
That’s the “Berater werden” page
Implement an upload functionality for CVs in PDF format (currently it’s just a text entry field). All
the fields need to be filled and the box clicked in order to click on “Bewerbung versenden” (submit
application). After the submitting the application the user should be redirected to a success page
and receive a mail (see below).
That’s the “Berater werden erfolg” page
“Liebe/r Bewerber/in,
Vielen Dank für Deine Bewerbung.
Wir werden Deine Unterlagen ausführlich prüfen und uns innerhalb von zwei Arbeitstagen bei Dir
melden. Falls Du in der Zwischenzeit Fragen hast, schau doch auf unserer FAQ-Seite vorbei oder
kontaktiere uns direkt über folgende E-Mail-Adresse: support@ts.com.
Bis dahin, beste Grüße
Dein taus&sassa-Team”
That’s the mail the user should receive if the application is received
The information from the application should be gathered in the CRM. After I accept the application
on the CRM the user should be able to sign in and receive the following email (see below). If I did
not accept the application and the user tries to sign in he or she should be redirected to the same
page (see above). If I decline the application the user should receive the following email and be
redirected to this page if he or she tries to sign in (see below).
That’s the “Berater werden absage” page
“Liebe/r Bewerber/in,
Vielen Dank für Dein Interesse an taus&sassa. Wir haben Deine Unterlagen sorgfältig geprüft und
müssen Dir leider mitteilen, dass wir Dich nicht ins taus&sassa-Netzwerk aufnehmen können.
Du hast leider nicht die ausreichende berufliche Erfahrung. Wir glauben daher nicht, dass wir für
Dich über taus&sassa einen passenden “Match” finden würdenWir würden uns freuen, wenn Du Dich zu einem späteren Zeitpunkt wieder bei taus&sassa
bewerben würdest.
Viele Grüße und beruflich weiterhin viel Erfolg
Dein taus&sassa-Team”
That’s the mail the user should receive if the application is rejected
“Liebe/r Bewerber/in,
Herzlich willkommen in unserem Beraterpool. Hier siehst Du eine Übersicht aller aktiven Projekte,
die wir momentan besetzen möchten. Du kannst Dich gerne auf jede Ausschreibung bewerben,
die Dir zusagt.
Sobald wir neue Projektanfragen erhalten, werden wir Dich per E-Mail informieren
Beste Grüße
Dein taus&sassa-Team”
That’s the mail the user should receive if the application is accepted
Part 3:
That’s the “Mein Profil” page in which users can change their personal information
Implement the upload functionality on this page as well. “Email Adresse” should be prefilled with
the Email address of the user who signed up. The user should be able to change it, but the field
cannot be empty. In order to change the password the user needs to fill both fields “Passwort” and
“Passwort bestätigen”. In order to save the changes the user needs to click on “Profil
aktualisieren”. After that the user should be redirected to another success page (see below). If the
user wants to delete the account he or she is required to click the box below. After deleting the
account the user should be directed to another success page (see below).
That’s the “Profil erfolg” page
That’s the “Gelöscht erfolg” page
# Part 5:
That’s the “Passwort vergessen” page in which users can reset their password
If the user inputs an email address that does not exists they should receive a error message. If
the email exists in the system the user should be redirect to the password success page (see
below) and receive the following email (see below) in which the user can create a new website in
the new password page (see below).
“Lieber Tausendsassa,
wir haben eine Anfrage zum Zurücksetzen Deines Passworts erhalten. Um Dein Passwort
zurückzusetzen klicke auf den folgenden Link.
Wenn Du das nicht beantragt hast, ignoriere einfach diese E-Mail.
Dein Passwort wird erst geändert, wenn Du auf den obigen Link klickst und ein neues Passwort
erstellen.
Beste Grüße
Dein taus&sassa-Team”
That’s the mail the user should receive if he or she clicks on the “Passwort zurücksetzen” button
That’s the “Passwort zurücksetzen” page in which users can create a new password
After the user successfully resets their password they will be redirected to the “Mein Profil” page
descripted in Part 3.
 # Part 6:
This is the most important part of the project and needs to be if necessary adapted by the
freelancer. We already created the elements shown below on our own.
That should be the “Projekt finden” page in which users can see available jobs
That should be the page after clicking on a job from the previous page
Important: After the user clicks on “Bewerben” I should receive a notification on the CRM or
Email that he or she is interested in the specific project. After clicking the button it should look like
the “Anmelden” button in the header and should not be clickable anymore for the specific user.
# 2. Implement a cookie consent that looks like the example below. If necessary use external plugins
in order to be GDPR compliant.
Cookie consent widget
# 3. Add the buttons “Anmelden” and “Berater werden” in the tablet mode and smaller into the
dropdown menu of the website under “Über uns” and remove them from the header.
Current header in tablet mode
# 4. Make that the header is not fix anymore and disappears if the user scrolls down.
