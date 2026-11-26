# SP-Sem1-Projekt
Projekt Strukturierete Programmierung 1. Semester

# Defintion des Projekts
  Das Ziel ist ein Algorithmus zur Prozeduralen Generierung einer Map / eines Spielfelds für das Spiel PacMan.
  Die Standard Parameter für die Mapgernerierung wären:
    - Variable größe, 15x15 bis zu 45x45 / als Breitformat 51 x 35
    - keine Sackgassen also von jedem Feld 2 oder mehr Bewegungsmöglichkeiten zu anderen Feldern
    - Links/Rechts Symetrie
    - Gangbreite 1x1 d.h. es dürfen keine 2x2 Felder existieren
    - Eine Durchgehende Außenwand also keine Möglichkeiten zum "entkommen"
    - Das "Ghosthouse" / Geisterhaus in der Mitte mit 5x3 bzw. 6x3 je nachdem ob die Karte eine gerade oder ungerade Spaltenanzahl hat und einem 1/2 Tiles "Ausgang" an der Oberseite.
      Das Geisterhause kann nicht betreten werden
    - Warptunnel - eine Verbindung der linken und rechten Seite der Karte auf Höhe der Mitte des Geisterhauses
    - 
