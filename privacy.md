---
permalink: /privacy/
title: "AOD+ Privacy Policy"
---

# AOD+ — Privacy Policy

_Last updated: 16 November 2026_

AOD+ ("the app") is an always-on display for Android by Kinetra, published on Google Play by
**Alessandro D'Adamo**, based in Portugal ("we", "us"), the data controller for the data described in
section 4. Contact: [a.dadamo@kinetra.uk](mailto:a.dadamo@kinetra.uk)

## 1. In short

- **Everything happens on your phone.** AOD+ reads your notifications and calendar only to show them on
  your screen. Nothing it reads is sent to us or to anyone else.
- **The app cannot go online.** It does not have Android's internet permission, so it is technically
  unable to send data off your device. There are no AOD+ servers.
- **We collect nothing through the app**: no accounts, no ads, no analytics, no tracking, no crash
  reports, no advertising identifiers.
- **Nothing is sold or shared**, because we don't have it.
- **You are in control**: every permission can be revoked in Android's settings, and uninstalling the
  app removes everything it stored.

## 2. What the app accesses, and why

Android shows you each of these before you grant it. AOD+ uses each one only for the purpose below.

| Access | Why AOD+ needs it | What AOD+ does not do |
|---|---|---|
| **Notification access** (granted by you in Android settings) | To show your notifications on the always-on screen: app name and icon, title, text, time, and whether it is a conversation or marked important. When you tap a notification, AOD+ opens it as the notification itself would; when you swipe one away, AOD+ clears it on the phone, as the notification shade would. | It never saves, logs, copies or transmits notification content. Content is kept in memory only while it is on screen. It does not reply to messages or act on notifications except when you tap or swipe them. |
| **Calendar, read only** (`READ_CALENDAR`) | To show your next events: title, start and end time, all-day flag, colour, whether you declined it. | It cannot create, change or delete events. Nothing is stored or transmitted. |
| **List of installed apps** (apps with a launcher icon) | To show which app a notification comes from, for the per-app settings screen, and to suggest your work apps in the Work preset. | The list is not stored except for the package names of apps you configure, and it never leaves the phone. |
| **Notifications** (`POST_NOTIFICATIONS`) and **full-screen intent** (`USE_FULL_SCREEN_INTENT`) | To bring up the always-on screen when the display turns off (Android only allows this through a full-screen notification), and to show the "AOD+ on" status notification that Android requires while the service runs. | These notifications contain no personal data. You can turn the status notification off. |
| **Foreground service** (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE`), **wake lock** (`WAKE_LOCK`), **start at boot** (`RECEIVE_BOOT_COMPLETED`) | To notice when the screen turns off and show the always-on screen, also after a restart. | They give no access to any data. |
| **Sensors** (proximity, motion; no permission needed) | Pocket mode (black screen when covered) and lift to wake, only while the always-on screen is showing. | Readings are used instantly and never recorded. |
| **Face or fingerprint** (`USE_BIOMETRIC`, optional) | To reveal hidden previews after Android's own face or fingerprint check. | The check is done by Android. AOD+ only receives "succeeded" or "failed", never images, templates or any biometric data. |
| **Accessibility service** (optional, "AOD+ · screen lock") | Only to lock the phone and turn the screen off, as the side key would. You turn it on yourself after an explanation in the app. | It does not read the screen, receives no events from other apps, and collects nothing. |
| **Battery optimisation** (your choice in Android settings) | So Android doesn't stop the service in the background. | No data involved. |
| **Google Play billing** (`com.android.vending.BILLING`) and **network state** (`ACCESS_NETWORK_STATE`), both added by Google Play's billing library | To offer the subscription and check whether it is active. The purchase itself happens in the Google Play app. | AOD+ never sees your payment details. Network state only tells whether a connection exists; without the internet permission AOD+ still cannot use it. |

AOD+ also reads a few system settings so it behaves like the rest of the phone: whether the lock screen
hides sensitive notification content, the screen brightness, the auto-lock delay, and (on Samsung phones)
whether Samsung's own always-on display is on. These values are used on the spot and not stored.

## 3. What is stored, and where

Only on your phone, in the app's private storage, which other apps cannot read:

- your settings (for example brightness, active hours, clock style, presets);
- your per-app choices, stored with the app's package name (for example "com.example.mail: always on top");
- technical state: the time of your last unlock (to know which notifications are new), whether a
  subscription is active and when that was last checked, which settings sections you folded;
- Google Play's billing library may keep its own usage statistics on the device. Since AOD+ has no
  internet permission, they cannot be sent.

No notification or calendar content is ever stored. App data is excluded from Android backups and device
transfers. Clearing the app's data or uninstalling it deletes all of the above.

## 4. What we receive

**From the app: nothing.** We have no way to see how you use AOD+ or what it shows.

**If you write to us** (for example with *Support → Write* in the app, which opens your own email app):
we receive what you send — your email address, your message and anything you attach. The subject is
pre-filled with the app version, phone model and Android version to help us answer; you can delete it
before sending. We use this only to reply to you, keep it only as long as needed to handle your request,
and never share it. Legal basis (GDPR): our legitimate interest in answering your request.

**From Google Play**: like every developer, we receive reports that Google Play prepares itself — install
and sales figures, the order number, product, price, country and date of purchases (for accounting and
refunds), and, if you agreed to share diagnostics with Google, crash and performance statistics collected
by Android. These are produced by Google, not by AOD+, and we do not use them to identify you.

## 5. Google Play and payments

The subscription and its free trial are sold and managed by Google Play: payment, renewals, cancellation
and refunds follow Google's terms and [Google's Privacy Policy](https://policies.google.com/privacy).
Google acts as an independent controller of the data it processes. AOD+ only asks the Google Play app on
your phone whether your subscription is active.

## 6. What we never do

We do not sell, rent or share personal data; show ads; use analytics or tracking; build profiles; use
your data to train models; or transfer data to other countries — because AOD+ sends us no data at all.

## 7. Your screen, your choice

Whatever AOD+ shows can be seen by people near your phone. By default it follows your lock screen's rule
for sensitive content; you choose which apps show their full text, which stay hidden until you confirm
with face or fingerprint, and which don't appear at all. Please check that showing work notifications on
an always-on screen is allowed by your employer's policies.

## 8. Security

Data stays in the app's private storage, protected by Android's app sandbox and your device encryption.
Nothing is transmitted, so nothing can be intercepted on the way.

## 9. Children

AOD+ is not directed at children under 13 (or the minimum age in your country) and collects no data from
anyone.

## 10. Your rights

Under the GDPR you have rights of access, correction, deletion, restriction,
objection and portability. Because the app does not send us your data, we hold none from your use of
AOD+; you can delete everything it stored by clearing its data or uninstalling it. For emails you sent
us, write to the address above and we will answer within one month. You can also complain to the
Portuguese data protection authority, CNPD ([cnpd.pt](https://www.cnpd.pt)), or to the data protection
authority of your country.

## 11. Changes

If this policy changes, the new version is published at this address with a new date. If a change would
let the app collect or send data — which it cannot do today — it would come with an app update and a
clear notice in the app first.

## 12. Contact

Alessandro D'Adamo (Kinetra) · Portugal · [a.dadamo@kinetra.uk](mailto:a.dadamo@kinetra.uk)

---

# AOD+ — Informativa sulla privacy

_Ultimo aggiornamento: 16 novembre 2026_

AOD+ («l'app») è un always-on display per Android di Kinetra, pubblicato su Google Play da
**Alessandro D'Adamo**, con sede in Portogallo («noi»), titolare del trattamento dei dati descritti al
punto 4. Contatti: [a.dadamo@kinetra.uk](mailto:a.dadamo@kinetra.uk)

## 1. In breve

- **Tutto avviene sul telefono.** AOD+ legge notifiche e calendario solo per mostrarli sul tuo schermo.
  Niente di ciò che legge viene inviato a noi o a chiunque altro.
- **L'app non può andare online.** Non ha il permesso di accesso a internet di Android, quindi
  tecnicamente non può inviare dati fuori dal dispositivo. Non esistono server di AOD+.
- **Non raccogliamo nulla tramite l'app**: niente account, pubblicità, statistiche, tracciamento,
  segnalazioni di crash o identificativi pubblicitari.
- **Niente viene venduto o condiviso**, perché non l'abbiamo.
- **Decidi tu**: ogni permesso si può revocare dalle impostazioni di Android, e disinstallando l'app si
  cancella tutto ciò che ha salvato.

## 2. A cosa accede l'app, e perché

Android te li mostra uno per uno prima che tu li conceda. AOD+ usa ciascuno solo per lo scopo indicato.

| Accesso | Perché serve ad AOD+ | Cosa AOD+ non fa |
|---|---|---|
| **Accesso alle notifiche** (lo concedi tu nelle impostazioni di Android) | Mostrare le notifiche sull'always-on display: nome e icona dell'app, titolo, testo, ora, e se si tratta di una conversazione o di una notifica importante. Quando tocchi una notifica, AOD+ la apre come farebbe la notifica stessa; quando la scorri via, AOD+ la elimina dal telefono, come la tendina delle notifiche. | Non salva, registra, copia né trasmette mai il contenuto delle notifiche. Il contenuto resta in memoria solo mentre è sullo schermo. Non risponde ai messaggi e non agisce sulle notifiche se non quando le tocchi o le scorri via. |
| **Calendario, in sola lettura** (`READ_CALENDAR`) | Mostrare i prossimi eventi: titolo, inizio e fine, giornata intera, colore, se lo hai rifiutato. | Non può creare, modificare o cancellare eventi. Niente viene salvato o trasmesso. |
| **Elenco delle app installate** (quelle con un'icona) | Mostrare da quale app arriva una notifica, per la schermata delle impostazioni per app e per suggerire le app di lavoro nel preset Lavoro. | L'elenco non viene salvato, salvo il nome di pacchetto delle app che configuri, e non lascia mai il telefono. |
| **Notifiche** (`POST_NOTIFICATIONS`) e **schermo intero** (`USE_FULL_SCREEN_INTENT`) | Far comparire l'always-on display quando lo schermo si spegne (Android lo permette solo con una notifica a schermo intero) e mostrare la notifica «AOD+ attivo» che Android richiede finché il servizio è attivo. | Queste notifiche non contengono dati personali. La notifica di stato si può spegnere. |
| **Servizio in primo piano** (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE`), **wake lock** (`WAKE_LOCK`), **avvio all'accensione** (`RECEIVE_BOOT_COMPLETED`) | Accorgersi dello spegnimento dello schermo e mostrare l'always-on display, anche dopo un riavvio. | Non danno accesso ad alcun dato. |
| **Sensori** (prossimità, movimento; non serve un permesso) | Modalità tasca (schermo nero se coperto) e riattivazione sollevando il telefono, solo mentre l'always-on display è visibile. | Le letture si usano al momento e non vengono mai registrate. |
| **Viso o impronta** (`USE_BIOMETRIC`, facoltativo) | Mostrare le anteprime nascoste dopo la verifica di viso o impronta fatta da Android. | La verifica la fa Android. AOD+ riceve solo «riuscita» o «non riuscita», mai immagini, modelli o altri dati biometrici. |
| **Servizio di accessibilità** (facoltativo, «AOD+ · blocco schermo») | Solo bloccare il telefono e spegnere lo schermo, come il tasto laterale. Lo attivi tu dopo una spiegazione nell'app. | Non legge lo schermo, non riceve eventi dalle altre app e non raccoglie nulla. |
| **Ottimizzazione della batteria** (scelta tua nelle impostazioni di Android) | Evitare che Android fermi il servizio in background. | Nessun dato coinvolto. |
| **Fatturazione Google Play** (`com.android.vending.BILLING`) e **stato della rete** (`ACCESS_NETWORK_STATE`), aggiunti dalla libreria di pagamento di Google Play | Offrire l'abbonamento e controllare se è attivo. L'acquisto avviene nell'app Google Play. | AOD+ non vede mai i tuoi dati di pagamento. Lo stato della rete dice solo se c'è una connessione; senza il permesso internet AOD+ comunque non può usarla. |

AOD+ legge anche alcune impostazioni di sistema per comportarsi come il resto del telefono: se la
schermata di blocco nasconde i contenuti sensibili delle notifiche, la luminosità dello schermo, il ritardo
del blocco automatico e (sui telefoni Samsung) se l'always-on display di Samsung è acceso. Questi valori si
usano al momento e non vengono salvati.

## 3. Cosa viene salvato, e dove

Solo sul telefono, nella memoria privata dell'app, che le altre app non possono leggere:

- le impostazioni (per esempio luminosità, orari di attività, stile dell'orologio, preset);
- le scelte per app, salvate con il nome di pacchetto dell'app (per esempio «com.example.mail: sempre in
  alto»);
- lo stato tecnico: l'ora dell'ultimo sblocco (per capire quali notifiche sono nuove), se c'è un
  abbonamento attivo e quando è stato controllato, quali sezioni delle impostazioni hai chiuso;
- la libreria di pagamento di Google Play può tenere sul dispositivo proprie statistiche d'uso. Dato che
  AOD+ non ha il permesso internet, non possono essere inviate.

Il contenuto di notifiche ed eventi non viene mai salvato. I dati dell'app sono esclusi dai backup e dai
trasferimenti tra dispositivi di Android. Cancellando i dati dell'app o disinstallandola si elimina tutto
quanto sopra.

## 4. Cosa riceviamo

**Dall'app: niente.** Non abbiamo modo di sapere come usi AOD+ o cosa mostra.

**Se ci scrivi** (per esempio con *Assistenza → Scrivi* nell'app, che apre la tua app di posta): riceviamo
ciò che invii — il tuo indirizzo email, il messaggio ed eventuali allegati. L'oggetto è precompilato con
versione dell'app, modello del telefono e versione di Android per aiutarci a rispondere; puoi cancellarlo
prima dell'invio. Usiamo questi dati solo per risponderti, li conserviamo solo per il tempo necessario a
gestire la richiesta e non li condividiamo. Base giuridica (GDPR): il nostro legittimo interesse a
rispondere alla tua richiesta.

**Da Google Play**: come ogni sviluppatore riceviamo i rapporti che Google Play prepara da sé — numeri di
installazioni e vendite, numero d'ordine, prodotto, prezzo, paese e data degli acquisti (per contabilità e
rimborsi) e, se hai accettato di condividere la diagnostica con Google, statistiche su crash e prestazioni
raccolte da Android. Li produce Google, non AOD+, e non li usiamo per identificarti.

## 5. Google Play e pagamenti

L'abbonamento e la prova gratuita sono venduti e gestiti da Google Play: pagamento, rinnovi, disdetta e
rimborsi seguono i termini di Google e la [Norma sulla privacy di Google](https://policies.google.com/privacy).
Google agisce come titolare autonomo dei dati che tratta. AOD+ chiede soltanto all'app Google Play del tuo
telefono se l'abbonamento è attivo.

## 6. Cosa non facciamo mai

Non vendiamo, affittiamo né condividiamo dati personali; non mostriamo pubblicità; non usiamo statistiche
o tracciamento; non creiamo profili; non usiamo i tuoi dati per addestrare modelli; non trasferiamo dati in
altri paesi — perché AOD+ non ci invia alcun dato.

## 7. Il tuo schermo, la tua scelta

Ciò che AOD+ mostra può essere visto da chi è vicino al telefono. Di default segue la regola della
schermata di blocco sui contenuti sensibili; scegli tu quali app mostrano il testo completo, quali restano
nascoste finché non confermi con viso o impronta e quali non compaiono affatto. Verifica che mostrare le
notifiche di lavoro su un always-on display sia consentito dalle regole del tuo datore di lavoro.

## 8. Sicurezza

I dati restano nella memoria privata dell'app, protetti dall'isolamento delle app di Android e dalla
crittografia del dispositivo. Niente viene trasmesso, quindi niente può essere intercettato.

## 9. Minori

AOD+ non è rivolta a minori di 13 anni (o dell'età minima prevista nel tuo paese) e non raccoglie dati di
nessuno.

## 10. I tuoi diritti

Il GDPR ti riconosce i diritti di accesso, rettifica, cancellazione, limitazione, opposizione e
portabilità. Poiché l'app non ci invia i tuoi dati, non ne conserviamo alcuno legato all'uso di AOD+; puoi
cancellare tutto ciò che ha salvato cancellandone i dati o disinstallandola. Per le email che ci hai
inviato, scrivi all'indirizzo sopra e ti risponderemo entro un mese. Puoi anche presentare reclamo
all'autorità portoghese per la protezione dei dati, CNPD ([cnpd.pt](https://www.cnpd.pt)), o all'autorità
per la protezione dei dati del tuo paese (in Italia il Garante per la protezione dei dati personali).

## 11. Modifiche

Se questa informativa cambia, la nuova versione viene pubblicata a questo indirizzo con una nuova data. Se
una modifica permettesse all'app di raccogliere o inviare dati — cosa che oggi non può fare — arriverebbe
con un aggiornamento dell'app e con un avviso chiaro nell'app prima.

## 12. Contatti

Alessandro D'Adamo (Kinetra) · Portogallo · [a.dadamo@kinetra.uk](mailto:a.dadamo@kinetra.uk)
