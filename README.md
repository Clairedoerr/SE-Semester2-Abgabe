# Abschlussbericht Software Engineering 2 - Social Media App LearnTogether

![Logo](https://github.com/Clairedoerr/SE-Semester2-Abgabe/blob/main/Logo%20(2).jpg?raw=true)


von Claire Dörr - DVM 2024


## Einleitung
Im Rahmen des Moduls Software Engineering 2 bestand die Aufgabe darin, in einem eigenständig organisierten Projektteam eine Social-Media-App zu entwickeln. Ziel war es, ein funktionales Softwareprodukt zu erstellen und gleichzeitig praxisorientierte Erfahrungen mit etablierten Methoden des Softwareengineerings zu sammeln.
<br>
Während des Projekts haben wir sämtliche Phasen eines interaktiven, agilen Entwicklungsprozesses durchlaufen. Neben der technischen Realisierung lag ein besonderer Fokus auf der koordinierten, kollaborativen Teamarbeit unter Anwendung des Scrum-Frameworks. 
<br>
Der vorliegende Bericht dokumentiert meinen individuellen Beitrag zur Projektarbeit, beschreibt die eingesetzten Werkzeuge und die Vorgehensmodelle, analysiert aufgetretene Herausforderungen sowie deren Lösungen, gibt aber auch einen Einblick in die gewonnenen technischen und organisatorischen Erkenntnisse im Verlauf des Projekts.

## Projektbeschreibung- und ziel 
Im Projektverlauf entwickelten wir die Social-Media-App „LearnTogether“, deren zentrales Ziel es ist, gemeinsames Lernen zu fördern. Die Anwendung soll eine digitale Umgebung schaffen, in der sich Nutzer gegenseitig durch Beiträge, Kommentare und Interaktionen zum Lernen motivieren und unterstützen – als Antwort auf die oft fehlende Eigenmotivation beim individuellen Lernen.
<br>
Die Zielgruppe der App „LearnTogether“ umfasst Schüler, Studierende sowie Personen, die an persönlicher Weiterentwicklung interessiert sind. Dabei wurde großer Wert auf eine einfache und intuitive Benutzeroberfläche gelegt, die den sozialen Austausch über Lerninhalte erleichtert.
Die Kernfunktionen umfassen Nutzer-Authentifizierung (Registrierung, Login, Logout), das Erstellen und Anzeigen von Posts, eine Kommentarfunktion sowie die Bearbeitung des eigenen Profils. 
<br>
Unsere Entscheidung für diese Projektidee basierte auf eigenen Erfahrungen im Studium, in denen sich gemeinsames Lernen als besonders motivierend und effektiv erwiesen hat. LearnTogether überträgt dieses Prinzip in eine digitale, skalierbare Form.
<br>
Das Ziel des Projekts war es daher, eine funktionale und benutzerfreundliche Webanwendung zu entwickeln, die den sozialen Austausch zu dem Thema Lernen aktiv fördert und somit einen konkreten Beitrag zur digitalen Bildung leistet. Die Plattform soll dabei Anwender motivieren, Lernprozesse gemeinsam zu gestalten, Erfahrungen auszutauschen und sich gegenseitig in ihrem individuellen Lernfortschritt zu unterstützen.
Der Fokus lag dabei sowohl auf der technischen Umsetzung zentraler Social-Media Funktionalitäten, erfüllt aber auch einen gesellschaftlichen Mehrwert, in dem die App gemeinsames Lernen digital unterstützt. Gleichzeitig verfolgte das Projekt das Ziel, theoretisch erlernte Konzepte des Softwareengineerings – insbesondere in den Bereichen agiler Entwicklung, Projektmanagement und Anforderungsanalyse – praxisnah anzuwenden und zu vertiefen. 
## Individueller Beitrag im Projekt
### Teamstruktur und Rollenverteilung
Unser Projektteam bestand aus drei Mitgliedern: Kristina Baotic, Emely Maier und Claire Dörr. Um das Projekt effizient umzusetzen, haben wir als Team das agile Vorgehensmodell Scrum verwendet. Scrum ist ein Framework zur Entwicklung von Software, das auf interaktiver Arbeit, klarem Rollenverständnis und regelmäßigen Austausch (Sprints) basiert. Innerhalb des Scrum-Frameworks wurden die Rollen klar verteilt und so übernahm ich in unserem Team die Rolle des Scrum Masters. Der Scrum MAszer ist dafür verantwortlich, den Scrum-Prozess im Team zu etablieren, dessen Einhaltung zu gewährleisten und das Team bei der Beseitigung von Hindernissen zu unterstützen.
<br>
Gleichzeitig war ich auch Teil des Entwicklungsteam und arbeitete aktiv sowohl am Frontend – als auch an Backend-Komponenten mit. 
### Verantwortung im Bereich Projektmanagement
Als Scrum Master war ich verantwortlich für die Einhaltung der Prozesse, die Moderation unserer Meetings, die Beseitigung von Hindernissen sowie die Förderung einer offenen und produktiven Teamkommunikation. Somit plante ich die Sprints und sorgte dafür, dass diese organisiert abliefen, unser Kanban-Baord gepflegt wurde und die Teammitglieder ihre Aufgaben klar zugeteilt bekamen. Zweimal die Woche führten wir ein kurzes Stand-up-Meeting durch, um uns über den aktuellen Fortschritt auszutauschen. In diesem Treffen beantwortete jeder von uns jeweils die drei zentralen Fragen: Was habe ich seit dem letzten Meeting erledigt? Was werde ich als nächstes bearbeiten? Gibt es aktuelle Probleme oder Blockaden?
<br>
Diese regelmäßigen Treffen förderten nicht nur die Transparenz innerhalb des Teams, sondern ermöglichten uns, aufkommende Schwierigkeiten frühzeitig zu erkennen und gemeinsam zu lösen. Insbesondere bei technischen Herausforderungen oder Unklarheiten in der Aufgabenverteilung, halfen wir uns gegenseitig weiter, was sich als zentraler Erfolgsfaktor für unsere Zusammenarbeit herausstellte. 
<br>
Darüber hinaus war ich für die Erstellung eines GitHub Projekts zuständig. GitHub ist eine webbasierte Plattform zur Versionsverwaltung und kollaborativen Softwareentwicklung, die auf dem Versionskontrollsystem Git basiert und Teams ermöglicht, den Programm-Code effizient zu verwalten, daran zu arbeiten und Änderungen nachvollziehbar zu dokumentieren. Die Versionskontrolle in GitHub war essenziell für eine teamübergreifende Arbeit an unserem Code. Durch GitHub war die Zusammenarbeit erheblich erleichtert, da der Code zentral verfügbar war und alle Mitglieder stets mit der aktuellsten Version arbeiteten konnten. 
<br>
Im Vorfeld der technischen Umsetzung beschäftigte ich mich auch mit den Grundlagen des Requirements-Engineerings, um sicherzustellen, dass unser Projekt auf einer strukturierten und zielgerichteten Anforderungsbasis aufbaut. Requirements-Engineering beschreibt den systematischen Prozess zur Erhebung, Analyse, Spezifikation und Verwaltung von Anforderungen an ein zu entwickelndes System. 
Vor Projektbeginn führten wir eine umfassende Anforderungserhebung durch. Hierbei analysierten wir die Bedürfnisse unserer potenziellen Nutzer und überführten diese in erste Anforderungen. In diesem Schritt betrieben wir auch eine Form der „Anforderungsarchäologie“, indem wir bestehende Social-Media-Plattformen analysierten und aus deren Funktionen, Stärken und Schwächen Rückschlüsse auf unsere eigene Produktvision zogen. 
Anschließend erfolgte eine Anforderungsanalyse, bei der wir die ermittelten Anforderungen hinsichtlich ihrer Umsetzbarkeit, Priorität und Abhängigkeiten beurteilten. Die identifizierten funktionalen Anforderungen (wie z. B. Nutzerregistrierung, Post-Erstellung, Kommentarfunktion) und nicht-funktionalen Anforderungen wurden von uns entsprechend priorisiert und in ein initiales Product Backlog überführt. Dieses Backlog bildete die Grundlage für unsere Arbeit mit dem Kanban-Board, das ich in Trello erstellte, unsere Teammitglieder hinzufügte und pflegte zusammen mit den anderen. Das Kanban-Board diente der transparenten Verwaltung aller Aufgaben im Projektverlauf: Aufgaben wurden dort in Spalten wie „To-Do“, „In Bearbeitung“ und „Erledigt“ gegliedert, einzelnen Teammitgliedern zugewiesen und bei Fortschritt entsprechend verschoben. So war jederzeit ersichtlich, wer woran arbeitet und welche Aufgaben anstehen. 
<br>
Die strukturierte Anwendung des Requirements-Engineerings half uns nicht nur bei der fundierten Planung, sondern stellte auch sicher, dass wir im Laufe des Projekts kontinuierlich nutzerorientiert und zielgerichtet entwickeln konnten. Dieser methodische Ansatz erwies sich insbesondere im Zusammenspiel mit agilen Prozessen wie Scrum als entscheidender Erfolgsfaktor für die Qualität und Realisierbarkeit unserer Lösung.
<br>
Im Rahmen der Vorbereitung auf die abschließende Projektmesse teilten wir die Aufgaben innerhalb des Teams klar untereinander auf, um einen reibungslosen Ablauf der Präsentation sicherzustellen. Meine Aufgabe bestand unter anderem darin, ein kurzes Präsentationsvideo zu schneiden, das während der Messe auf einem Bildschirm gezeigt wurde. Gemeinsam bauten wir den Stand auf, koordinierten die technische Ausstattung. Ziel war es, die Funktionen und das Konzept von LearnTogether möglichst anschaulich und verständlich zu präsentieren.
### Verantwortung im Bereich der Technik
Im Bereich der Technik hatte ich ebenfalls mehrere Aufgaben. Zunächst skizzierten wir im Team die Webapp. Dieser Schritt war einer der ersten, die wir im Projekt angegangen sind. Nachdem wir das grobe Design besprochen hatten, erstellte ich mithilfe von Wireframe Mockups. Dadurch hatte wir alle die gleiche Vorstellung darüber, wie es aussehen soll und es konnte ein HTML-Gerüst erstellt werden. <br>
https://wireframe.cc/pro/pp/43d7950bb883700<br><br>
Die Webapp wurde jedoch schlussendlich mit einer kleinen geringfügigen Modifikation umgesetzt: Die ursprünglich vorgesehene „Entdecken“-Seite wurde entfern, da die entsprechenden Beiträge bereits auf der Startseite integriert sind und dies inhaltliche Wiederholungen zur Folge gehabt hätte.
Zu meine Aufgaben bei der Erstellung des Frontends gehörten das Erstellen der Navigationsleiste auf allen Seiten, sowie das Anfertigen der Frontend Seiten „Post-Ansicht“, „Profilseite“ und die Seite zur Profilbearbeitung. Dazu frischte ich meine Kenntnisse in HTML und CSS im Bereich des Erstellens und Designens auf. 
Bei der Erstellung der seitlichen Navigationsleiste, welche auf allen Seiten eingebunden ist, legte ich besonderen Wert auf die Benutzerfreundlichkeit und ein konsistentes Design. Ich arbeitete mit fixierter Positionierung, sodass die Leiste auch beim Scrollen sichtbar bleibt. Die Navigationselemente ordnete ich mithilfe von `flex-direction: column` vertikal an, um eine klare Struktur zu schaffen. Statt Textlinks verwendete ich aussagekräftige Icons in Bildform, so wird der Zweck der Buttons auf einen Blick ersichtlich. Im CSS definierte ich zusätzlich Maße, Abstände und das Layout der Icons, um ein einheitliches Erscheinungsbild und eine gute Bedienbarkeit über alle Seiten hinweg sicherzustellen.
<br>
**HTML:**
```html
<div id="navigation">
    <a href="{% url 'startseite' %}"><img src="{% static 'design_images/bild_haus.jpg' %}" alt="Home"></a>
    <a href="{% url 'posten' %}"><img src="{% static 'design_images/bild_erstellen.jpg' %}" alt="Hinzufügen"></a>
    <a href="{% url 'ueber_uns' %}"><img src="{% static 'design_images/bild_ueber_uns.jpg' %}" alt="Benutzer"></a>
</div>
```
**CSS:**
```css
#navigation {
    position: fixed;
    top: 0px;
    width: 80px;
    height: 100%;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 100px;
}

#navigation a {
    margin: 12px 0;
}

#navigation img {
    width: 28px;
    height: 28px;
}
```

Eine weitere wichtige Komponente der App, die ich auch erstellt hatte, ist die Posten-Seite. Benutzer können hier eigene Beiträge mit einem Titel und einem Bild hochladen. Die Seite wurde in HTML mithilfe von HTML-Forms umgesetzt. Mit `enctype="multipart/form-data"` wurde es so konfiguriert, dass neben Textdaten auch Bilddateien korrekt an den Server übermittelt werden können. Das `enctype`-Attribut ist hierbei notwendig, da es die Dateien in mehreren Teilen überträgt und so sicherstellt, dass auch Binärdaten wie Bilder vom Server empfangen und verarbeitet werden können. Über den Button Posten wird der Beitrag anschließend an die zugehörige Django-View weitergeleitet. Zusätzlich habe ich auch hier mit CSS für eine klare Struktur, ausreichend Abstand und eine benutzerfreundliche Darstellung gesorgt.

```html
<form id="forms" method="POST" enctype="multipart/form-data" action="{% url 'upload' %}">
    {% csrf_token %}
    <div class="form">
        <label for="titel">Titel:</label>
        <input type="text" id="titel" name="titel" placeholder="Titel vom Post..." required>
    </div>

    <div class="form">
        <label for="photo">Upload: </label>
        <input
            type="file"
            id="photo"
            name="datei"
            accept="image/*" required>
    </div>

    <div class="buttons">
        <button type="reset">Zurücksetzen</button>
    </div>

    <div class="buttons">
        <button type="submit">Posten</button>
    </div>

</form>
```

Nachdem der Beitrag erstellt wurde, wird dieser auf der Startseite angezeigt und kann auf der Post-Detail-Seite vergrößert angeschaut und kommentiert werden. Das Front-End hierfür habe ich ebenfalls erstellt. Dort habe ich ein zweispaltiges Layout entworfen links wird das Bild mit Titel und Benutzer angezeigt, rechts befindet sich ein Kommentarbereich. Die technische Umsetzung des Kommentarbereichs über das Backend übernahm Frau Meyer. So legte für den Kommentarbereich Platzhalter und das visuelle Grundgerüst an, um eine klare Struktur zu schaffen, auf die anschließend die Backend-Funktionalität aufbauen konnte. Eine enge Abstimmung war erforderlich, um das Design nahtlos in die Anwendung zu integrieren.

```html
<a href="{% url 'startseite' %}" class="zurueck-button">Zurück zur Startseite</a>
<div class="kommentar-seite">
  <div class="post-bereich">
    <img src="/static/images/{{ bildname }}" alt="Bild">
    <h2>{{ info.beschreibung }}</h2>
    <p style="color:gray;">Von: {{ info.benutzer }}</p>
  </div>

  <div class="kommentar-bereich">
    <h3>Kommentare:</h3>
    <div id="comments">
      {% for comment in kommentare %}
        <p><strong>{{ comment.benutzer }}:</strong> {{ comment.text }}</p>
      {% empty %}
        <p style="color:gray;">Noch keine Kommentare</p>
      {% endfor %}
    </div>

    <textarea id="new-comment" placeholder="Kommentar schreiben..."></textarea><br>
    <button onclick="saveComment()">Speichern</button>
  </div>
</div>
```

Ein weiterer Teil meiner Aufgabe war die Umsetzung des Frontends für die Profilseite. Dort habe ich das Layout gestaltet, in dem der Benutzername sowie die bisherigen Beiträge des Nutzers übersichtlich dargestellt werden. Der obere Bereich („Kopfzeile“) zeigt das Profilbild zusammen mit dem Namen, darunter werden die Posts des Users in einer Kachelansicht angezeigt. 

```html
<div class="hauptinhalt">
        <div id="profil_kopfzeile">
        <img src="{% static 'design_images/Profilbild.jpg' %}" alt="Profilbild" id="profilbild">
        <div id="profildaten">
                <p><strong>Profilname: </strong>{{ user.vorname }} {{user.nachname}}</p>
        </div>
        <button type="button" id="profil_button">
                <a href="{% url 'profil_bearbeiten' %}">Profil bearbeiten</a>
        </button>
        </div>
        <h1>Deine Beiträge: </h1>
        <div class="posts">
                {% for bild, info in posts.items %}
        <div class="post-inhalt">
                <img src="/static/images/{{ bild }}" alt ="Bild">
                <p style = "margin-top: 5px;">{{ info.beschreibung }}</p>
        </div>
        {% endfor %}
        </div>
</div>
```

Auch die Seite „Profil bearbeiten“ habe ich im Frontend umgesetzt. Dabei erstellte ich ein einfaches HTML-Formular, das die Bearbeitung von Benutzerinformationen wie Name, E-Mail, Geburtsdatum und Passwort erlaubt. Um die Eingabefelder übersichtlich darzustellen, verwendete ich passende Labels, Abstände und einfache CSS-Formatierungen. Der Fokus lag hier auf Benutzerfreundlichkeit und einer klaren Struktur, die eine einfache Interaktion ermöglicht.

```html
<div class="hauptinhalt">

    <h1>Profil bearbeiten</h1>
    
    <form method="post">
        {% csrf_token %}
        <label> Vorname: <input type="text" name="vorname" value="{{ user.vorname }}"></label><br>
        <label> Nachname: <input type="text" name="nachname" value="{{ user.nachname }}"></label><br>
        <label> Email: <input type="email" name="email" value="{{ user.email }}"></label><br>
        <label> Geburtsdatum: <input type="date" name="geburtstdatum" value="{{ user.geburtsdatum }}"></label><br>
        <label> Neues Passwort (leer lassen, wenn unverändert): <input type="password" name="password"></label><br>
    
        <button type="submit">Speichern</button>
    
    </form>
    
    <a href="{% url 'profil' %}"> Zurück zum Profil</a>
    
</div>
```

Nach der Gestaltung der Profil- und Profilbearbeitungsseite im Frontend ging es im nächsten Schritt darum, auch die dahinterliegende Logik im Backend umzusetzen. Hierzu zählte vor allem die Arbeit mit dem Benutzersystem: Ich war verantwortlich für die Implementierung der User-Authentifikation, die Registrierung, das Login/Logout sowie die Bearbeitung und Verwaltung von Benutzerprofilen.
<br>
Bevor ich mit der eigentlichen Backend-Entwicklung begann, richtete ich zunächst die Serverumgebung ein. Dazu installierte ich auf meinem Ubuntu-Server sowohl Django als Webframework als auch Apache als Webserver. Django ist ein leistungsfähiges, in Python geschriebenes Webframework, das die schnelle Entwicklung sicherer und wartbarer Webanwendungen nach dem Model-View-Template-Prinzip ermöglicht. Durch die Konfiguration von Apache und das Einbinden des Django-Projekts, konnte ich die Anwendung auf dem Server, das Backend über die Django-Views starten und auch testen. Durch die Konfiguration von Apache – insbesondere über die `000-default.conf` – und das Einbinden der Django-WSGI-Schnittstelle, konnte das Projekt so eingerichtet werden, dass es auch nach Serverneustarts permanent läuft. So war es möglich, die Anwendung stabil zu hosten und das Backend über Django-Views zu entwickeln.
<br>
Im Rahmen der Backend-Struktur legte ich in der Datei `urls.py` die verschiedenen Seitenrouten der Anwendung an. Dort definierte ich URL-Pfade wie z. B. `/startseite`, `/posten`, `/profil` oder `/post/` und verknüpfte sie jeweils mit den zugehörigen Funktionen in der Datei `views.py`.
<br>
Damit eine Seite im Browser erreichbar ist, müssen URL-Eintrag und View-Funktion aufeinander abgestimmt sein – also z. B. `path("profil", views.profil)` mit einer gleichnamigen Funktion `def profil(request)` in der View-Datei. So entsteht die Verbindung zwischen Adresse, Logik und Darstellung.
<br>
Ein zentraler Bestandteil der Backend-Entwicklung, welcher meine Aufgabe war, war die Umsetzung der Benutzer-Authentifizierung, insbesondere die Registrierung und Anmeldung von Nutzerinnen und Nutzern. Die Registrierung erfolgt über ein HTML-Formular, das die Daten wie Benutzername, Passwort, Vorname, Nachname, E-Mail und Geburtsdatum an die zugehörige View sendet. In der View-Funktion `registrieren()` (in views.py) werden diese Daten entgegengenommen und in einer JSON-Datei gespeichert, die als Benutzerdatenbank dient. Vor dem Speichern wird überprüft, ob der Benutzername bereits existiert – ist dies der Fall, wird ein Hinweis zurückgegeben.

```python
def registrieren(request):
    if request.method == "POST":
        username = request.POST.get("username")
        password = request.POST.get("password")
        vorname = request.POST.get("vorname")
        nachname = request.POST.get("nachname")
        email = request.POST.get("email")
        geburtsdatum = request.POST.get("geburtsdatum")

        users = load_users()

        if username in users:
            return HttpResponse("Benutzer existiert bereits.")

        users[username] = {
            "password": password,
            "vorname": vorname,
            "nachname": nachname,
            "email": email,
            "geburtsdatum": geburtsdatum,
        }
        save_users(users)

        request.session["username"] = username
        return redirect("startseite")
    return render(request, "meine_app/registrieren.html")
```

Die Daten werden in einer separaten Datei users.json gespeichert. Der Zugriff auf diese Datei erfolgt über die Hilfsfunktionen `load_users()` und `save_users()`, die das Laden und Speichern der Benutzerinformationen übernehmen. Die Session wird genutzt, um eingeloggte Benutzer zu identifizieren, was unter anderem für das personalisierte Anzeigen von Inhalten erforderlich ist.

```python
def load_users():
    if os.path.exists(USERS_FILES):
        with open(USERS_FILES, "r") as datei:
            return json.load(datei)
    return {}
def save_users(users):
    with open(USERS_FILES, "w") as datei:
        json.dump(users, datei)
```

Für den Login habe ich eine View-Funktion erstellt, die über ein HTML-Formular Benutzername und Passwort entgegennimmt. Die eingegebenen Daten werden mit dem in der `users.json` gespeicherten Daten abgeglichen. Wenn der Benutzername existiert und das Passwort korrekt ist, wird der Benutzername in der Session gespeichert – so erkennt Django, welcher Nutzer eingeloggt ist. 

```python
def login(request):
    if request.method == "POST":
        username = request.POST.get("username")
        password = request.POST.get("password")
        users = load_users()
        if username in users and users[username]["password"] == password:
            request.session["username"] = username
            return redirect("startseite")
        else:
            return HttpResponse("Ungültige Anmeldedaten")

    return render(request, "meine_app/login.html")
```

Auf der Profilseite wird oben der Name des eingeloggten Nutzers angezeigt. Dieser wird aus der `users.json` geladen, indem man über den in der Session gespeicherten Benutzernamen (`request.session[“username“]`) den passenden Datensatz abruft. Zudem zeigt die Seite nur die Beiträge an, die dieser Nutzer erstellt hat. Dazu wird überprüft, ob der gespeicherte Benutzername (`info[“benutzer“]`) mit eingeloggten übereinstimmt. 

```python
def profil(request):
    if "username" not in request.session:
        return redirect("login")

    username = request.session["username"]

    if os.path.exists(BESCHREIBUNGEN_DATEI):
        with open(BESCHREIBUNGEN_DATEI, "r") as datei: 
            try:
                beschreibungen = json.load(datei)
            except:
                beschreibungen = {}
    else:
        beschreibungen = {}
    
    eigene_posts = {}
    for bild, info in beschreibungen.items():
        if isinstance(info, dict) and info.get("benutzer") == username:
            eigene_posts[bild] = info

    users = load_users()
    user_data = users.get(username, {})

    return render(request, "meine_app/profil.html", {"user": user_data, "posts": eigene_posts} )
```

Nutzer können über einen Button ihr Profil bearbeiten. Die View `profil_bearbeiten()` lädt die aktuellen Daten und zeigt sie in einem Formular an. Wird dieses Formular abgeschickt, werden die geänderten Werte in der users.json gespeichert. 

```python
def profil_bearbeiten(request):
    if "username" not in request.session:
        return redirect("login")

    username = request.session["username"]
    users = load_users()
    user_data = users.get(username, {})

    if request.method == "POST":
        user_data["vorname"] = request.POST.get("vorname", "")
        user_data["nachname"] = request.POST.get("nachname", "")
        user_data["email"] = request.POST.get("email", "")
        user_data["geburtsdatum"] = request.POST.get("geburtsdatum", "")

        new_password = request.POST.get("password", "")
        if new_password:
            user_data["password"] = new_password

        users[username] = user_data
        save_users(users)

        return redirect("profil")

    return render(request, "meine_app/profil_bearbeiten.html", {"user": user_data})
```

Die Benutzer können somit jederzeit ihre Profildaten aktualisieren – auch das Passwort – wobei das Passwort-Feld leer bleiben kann, wenn es nicht geändert werden soll. 

## Herausforderungen und Lösungen
Eine der zentralen Herausforderungen zu Beginn unseres Projekts bestand darin, die Aufgaben realistisch aufzuteilen und zeitlich zu planen. Aufgrund unseres noch begrenzten technischen Vorwissens war es schwer einzuschätzen, welche Bestandteile des Projekts wir wann umsetzen können. Diese Unsicherheit führte zu Zurückhaltung bei der Übernahme komplexerer Aufgaben und erschwerte eine klare Zieldefinition. 
Ein geeigneter Lösungsansatz für künftige Projekte könnte darin bestehen, zu Beginn bewusst niedrigere Ziele zu setzen, die bei Bedarf erweitert werden können. Dies verhindert, dass später wesentliche Funktionen aufgrund von Zeit- oder Ressourcenmangel gestrichen werden müssen. Eine bessere Projektplanung unter Einbeziehung von Risikomanagement und realistischen Meilensteinen ist daher essenziell, um frühzeitig auf Herausforderungen reagieren zu können.
<br>
Eine weitere Herausforderung zeigte sich bei der praktischen Umsetzung einzelner technischer Funktionen. Oft war zunächst unklar, wie bestimmte Aufgaben überhaupt programmiert werden sollten. Zur Lösung dieser Probleme griffen wir auf verschiedene Ressourcen zurück, darunter Fachportale wie Stack Overflow, offizielle Dokumentationen, Lernplattformen, Videotutorials sowie die begleitenden Skripte des Kurses. Auch der Austausch im Team war hierbei besonders wertvoll – durch die gegenseitige Unterstützung konnten viele Verständnisprobleme gemeinsam überwunden werden.
<br>
Auch das Zeitmanagement war anspruchsvoll, da das Projekt parallel zu anderen Studienleistungen lief. Ein strukturierter Zeitplan sowie regelmäßige, kurze Meetings halfen dabei, Fortschritte sichtbar zu machen und Verzögerungen frühzeitig zu erkennen. 

## Zusammenarbeit im Team
Die Zusammenarbeit im Team war von einem kooperativen, respektvollen und zielorientierten Miteinander geprägt. Durch regelmäßige Stand-up-Meetings, eine klare Aufgabenverteilung über das Kanban-Board sowie den Einsatz agiler Methoden wie Scrum, konnten wir unsere Arbeitsprozesse effizient strukturieren und koordinieren. Offene Kommunikation, gegenseitige Unterstützung bei technischen Herausforderungen und eine gemeinsame Verantwortung für das Projektergebnis, förderten ein produktives Arbeitsklima, das maßgeblich zum Erfolg unserer Teamarbeit beitrug.

## Reflexion: Optimierungspotenzial und künftige Verbesserungen
Rückblickend würde ich bei einem zukünftigen Projekt noch mehr Zeit in die initiale Planungsphase investieren. Eine frühere und detailliertere Aufteilung der Aufgaben, sowie ein klar strukturierter Zeitplan hätten uns dabei geholfen, gezielter in das Projekt zu starten und mögliche Engpässe frühzeitig zu erkennen.
<br>
Darüber hinaus würde ich technischen Herausforderungen künftig proaktiver begegnen, indem ich bereits zu Beginn gezielt externe Ressourcen wie Tutorials, Fachliteratur oder Dokumentationen einplane und diese systematisch nutze. Auch die frühzeitige Abstimmung über Schnittstellen und technische Verantwortlichkeiten innerhalb des Teams würde ich konsequenter umsetzen, um die Integration verschiedener Komponenten effizienter und reibungsloser zu gestalten.
<br>
Insgesamt sehe ich im Bereich der Projektplanung, insbesondere im Hinblick auf Risikomanagement und realistische Zielsetzung, Potenzial zur Verbesserung. Ein schrittweises Vorgehen mit frühzeitigem Feedback, etwa durch Prototypen oder Mockups, hat geholfen, Unsicherheiten früh zu erkennen und iterativ Lösungen zu entwickeln. Diese Erkenntnisse werde ich in künftigen Projekten bewusst berücksichtigen.

## Fazit
Das Projekt war insgesamt eine äußerst bereichernde und praxisnahe Erfahrung. Durch die eigenständige Entwicklung einer Social-Media-Anwendung konnte ich meine technischen Kompetenzen deutlich erweitern. Gleichzeitig ermöglichte die enge Zusammenarbeit im Team wertvolle Einblicke in die dynamischen Prozesse gemeinschaftlicher Projektarbeit, die von Kommunikation, gegenseitiger Unterstützung und einem klaren Rollenverständnis geprägt war.
<br>
Besonders hilfreich war der strukturierte Einsatz von Methoden wie Scrum und Requirements-Engineering, die mir nicht nur geholfen haben, die Projektarbeit effizient zu organisieren, sondern auch ein tieferes Verständnis für professionelle Softwareentwicklungsprozesse vermittelt haben. Diese methodischen Ansätze haben sich als praxisrelevant und übertragbar auf verschiedenste Kontexte erwiesen.
<br>
Die im Projekt erlernten Kompetenzen und Erfahrungen lassen sich zudem gut auf meinen zukünftigen beruflichen Kontext übertragen. Gerade dort, wo zunehmend digitale Lösungen und Prozessoptimierungen zum Einsatz kommen, sind sowohl technisches Verständnis als auch methodisch fundierte Herangehensweisen in der Projektplanung und -umsetzung von großer Bedeutung. Das Projekt hat mir somit nicht nur fachlich, sondern auch im Hinblick auf meine spätere Berufspraxis einen nachhaltigen Mehrwert geboten.
<br>
Die Präsentation auf der Projektmesse war ein motivierender Abschluss des Projekts. Das positive Feedback und das Interesse der Besucher zeigten, dass unsere Anwendung überzeugend war – sowohl funktional als auch konzeptionell. Besonders erfreulich war, dass unser Team den ersten Platz belegte. Diese Anerkennung bestätigte nicht nur die Qualität unserer Arbeit, sondern auch den Wert einer sorgfältigen Planung und Vorbereitung.

## Anhang
Der vollständige Code, sowie der Bericht ist im Git Repository zu finden.
https://github.com/Clairedoerr/SE-Semester2-Abgabe.git
