# Changelogs - Tropic Bot

Hier werden alle Änderungen vom `Tropic Bot` aufgelistet

# Version: 1.0 (beta-private)

- ## Improvements

   - Levelsystem hinzugefügt
   - Economysystem hinzugefügt
   - Warnsystem hinzugefügt

- ## Changes

   - Der Bot hat nun einen neuen Namen `Tropic Bot`
   - Es gibt viele Änderungen im Code, zum einen mehr Design, aber auch Verbesserungen im Code (Nur für den Dev angedacht)
   - `/ticket panel create` wurde aufgeteilt in `ticket button_panel create` und `ticket select_menu_panel create`
   - Wenn man nun Ticket Panels erstellt wurden neue Optionen hinzugefügt:
      - bei `/ticket button_panel create`:
         - `panel_title`
         - `panel_button_label`
         - `panel_button_emoji`
         - `panel_button_style`
      - bei `/ticket select_menu_panel create`:
         - `panel_title`
   - zum Command `/fun generate password` wurden neue Optionen hinzugefügt:
      - `uppercase`
      - `numbers`
      - `special_character`
   - zum Command `moderation ban` wurden neue Optionen hinzugefügt:
      - `reason`
   - zum Command `moderation kick` wurden neue Optionen hinzugefügt:
      - `reason`

- ## Removes

   - Es wurden leider die Musik Commands serverweit entfernt, ob sie Premium haben oder nicht - dies bezieht sich aber nicht auf den Support Server
   - Wegen dem neuen großem Update wurde die komplette Database gelöscht

- ## Fixxes

   - Wenn man eine Kategorie jetzt aussucht, bei dem Command `/help` und der Bot dir die Commands auflistet von der Kategorie, werden dir nun die Commands richtig angezeigt

- ## Upcomming
   
   - Demnächst wird die Database auomatisch aktualisiert, falls sich an der Database was ändert. Bisher wurde sie immer nur einfach gelöscht womit alle Daten verloren gingen, wie in diesem Update
   - Englischen Support hinzufügen