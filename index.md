---
title:
permalink: /
feature_image: "pictures/header.png"
feature_text: |
  ## Förderverein Kyritzschule Darmstadt e.V.
  ### Gemeinsam mehr Erreichen - für unsere Kinder
---

<section id="ueber-uns" class="onepage-section" markdown="1">

## Über uns

Wir sind der **Förderverein der Kyritzschule Darmstadt e.V.** - ein Zusammenschluss engagierter Eltern und Unterstützer*innen, die die Kyritzschule nicht nur begleiten, sondern aktiv mitgestalten möchten.

Nachdem die Kyritzschule 2025 organisatorisch von der Goetheschule Darmstadt getrennt wurde, war klar:  
Es braucht einen eigenen Förderverein, der sich ausschließlich für die Belange unserer Schule einsetzt.

Im Mai 2026 konnten wir die Gründung formall abschließen und freuen uns mit den ersten Projekten starten zu können.

<hr class="section-divider section-divider--strong">

## Was wir machen

Wir möchten dort helfen, wo es den größten Unterschied für unsere Kinder macht - im Klassenzimmer, auf dem Pausenhof und bei besonderen Veranstaltungen. Unsere Schwerpunkte sind:

- Zusätzliche Lern- und Spielmaterialien finanzieren  
  (z. B. Bücher, Experimentierkästen, Sportgeräte)
- Klassen- und Schulprojekte unterstützen  
  (z. B. Theateraufführungen, Projekttage, Wettbewerbe)
- Kulturelle und sportliche Aktivitäten fördern 
  damit Kinder vielfältige Erfahrungen sammeln können
- Veranstaltungen und Feste mitorganisieren  
  (z. B. Sommerfest, Flohmarkt, Adventsbasar)
- Externe Spenden einwerben, um größere Anschaffungen und besondere Projekte zu realisieren

So schaffen wir Gelegenheiten und Erlebnisse, die den Schulalltag bereichern und den Zusammenhalt stärken.

</section>

<section id="mitglied-werden" class="onepage-section" markdown="1">

## Mitglied werden

Als Förderverein brauchen wir nicht nur Mittel, die wir weitergeben und einsetzen können, sondern auch Personen, die aktiv im Verein sind. Sie können unten den Mitgliedsantrag und die Beitragsordnung runterladen. Für eine Mitgliedschaft füllen Sie den Mitgliedsantrag aus und lassen uns diesen über den Briefkasten des Fördervereins (Eingang der Schule an der Emilstraße), persönlich oder auch digital (Emailadresse im Impressum) zukommen. 
Sollten sie die digitale Variante wählen, stellen sie bitte sicher, dass der Antrag formal unterschrieben ist und eine eindeutige Zuordnung möglich ist.

Mit Ihrer Unterstützung können wir Projekte ermöglichen, die ohne zusätzliche Mittel nicht möglich wären.

### Dokumente

- [Beitrittserklärung]({{ "/documents/260507_Beitrittserklaerung.pdf" | relative_url }})
- [Beitragsordnung]({{ "/documents/260507_Beitragsordnung.pdf" | relative_url }})
- [Vereinfachter Nachweis]({{ "/documents/260519_VerinfachterNachweis.pdf" | relative_url }})

</section>

<section id="spenden" class="onepage-section" markdown="1">

# Spenden

Gerne können Sie uns auch über die betterplace-Plattform eine einmalige oder regelmäßige Spende zukommen lassen. Ob groß oder klein - **jeder Beitrag zählt** und macht einen Unterschied.

</section>

<section id="projekte" class="onepage-section" markdown="1">

## Projekte

Wir möchten dort unterstützen, wo konkrete Projekte den Alltag der Kinder bereichern: im Unterricht, auf dem Pausenhof, bei Veranstaltungen und bei besonderen Aktionen der Schulgemeinschaft.

{% if site.posts.size > 0 %}
<div class="project-list">
  {% for post in site.posts limit: 3 %}
  <article class="project-item">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
  </article>
  {% endfor %}
</div>
{% else %}
Aktuelle Projekte werden hier veröffentlicht, sobald sie starten.
{% endif %}

</section>

<section id="kontakt" class="onepage-section" markdown="1">

## Kontakt

Sie haben Fragen zum Förderverein, möchten uns unterstützen oder direkt Kontakt aufnehmen? Schreiben Sie uns gerne über das Formular. Wir melden uns schnellstmöglich zurück.

<div class="contact-card">
  <form
    class="contact-form"
    name="kontakt"
    method="POST"
    enctype="multipart/form-data"
    action="https://formspree.io/f/mykdryqe"
  >
    <input type="hidden" name="subject" value="Neue Nachricht über die Kontaktseite">
    <input type="text" name="_gotcha" style="display: none;">

    <div class="form-grid">
      <label class="form-field">
        <span>Vorname</span>
        <input type="text" name="vorname" autocomplete="given-name" required>
      </label>

      <label class="form-field">
        <span>Nachname</span>
        <input type="text" name="nachname" autocomplete="family-name" required>
      </label>

      <label class="form-field form-field-full">
        <span>E-Mail-Adresse</span>
        <input type="email" name="email" autocomplete="email" required>
      </label>

      <label class="form-field form-field-full">
        <span>Nachricht</span>
        <textarea name="nachricht" rows="7" required></textarea>
      </label>

    </div>

    <div class="form-actions">
      <button type="submit" class="button">Absenden</button>
      <button type="reset" class="button button--secondary">Zurücksetzen</button>
    </div>
  </form>
</div>

</section>
