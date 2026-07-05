# dynamic oil buzzer REV1d
  
#### DE - [Bedienungsanleitung](https://github.com/sebastianlehner/DYNOB/blob/main/dynamic_oil_buzzer_REV1d_DE.pdf)
#### EN - [manual](https://github.com/sebastianlehner/DYNOB/blob/main/dynamic_oil_buzzer_REV1d_EN.pdf)  

#### Funktionsübersicht / Einbauanleitung - [https://youtu.be/VGgJPHZ6h68](https://youtu.be/VGgJPHZ6h68)
#### Lernmodus - [https://youtu.be/bumlYxhFiTA](https://youtu.be/bumlYxhFiTA)
<img width="450" height="450" alt="dyn_oil_buzzer_REV1d_Uebersicht" src="https://github.com/user-attachments/assets/c9ba2301-ec27-43f6-be9d-d74610d9175b" />

Diese Platine dient als **dynamische Öldruck-Überwachung** für Diesel- und Benzin-Motoren.  
Bei Überschreitung von **2050 U/min** wird der Öldruck 2 überprüft (ist inaktiv bei Unterschreitung von 2000 U/min).  
Weiters piepst/blinkt die Platine bei Drehzahl-Verlust trotz vorhandenem Öldruck 2 (Keilriemenriss bei Diesel-Motoren).  
  
Bei Öldruck 1-Verlust blinkt die LED sofort. Liegt ein anderer Fehler vor, wird dies <ins>nach 2 Sekunden</ins> signalisiert (LED und Buzzer).  
Wird eine Drehzahl von <ins>über 9000 U/min</ins> detektiert, zirpt der Buzzer und die LED leuchtet dauerhaft ! (falsche Motoreinstellung/Übersetzung)
<ins> </ins>
### Kompatibilität:
**VW T3, Golf 1, Golf 2, Polo 2, Caddy 1, Jetta 2, Passat B2 und Scirocco 2**


### Vorteile:

- plug & play, ersetzt alle alten Platinen-Versionen
- für alle Diesel- und Benzin-Motoren (4,5,6 und 8 Zylinder)
- Lernmodus für nicht standardmäßige Riemenübersetzungen
- erkennt Keilriemenriss bei Diesel-Motoren (Drehzahl-Verlust bei vorhandenem Öldruck 2)

### Spezifikationen
<table class="vclTable">
  <tr>
    <td>
      Versorgungsspannung
    </td>
    <td colspan="2">
      6V ... 16 V
    </td>
  </tr>
  <tr>
    <td>
      Versorgungsstrom
    </td>
    <td colspan="2">
      5mA
    </td>
</tr>
  <tr>
    <td>
      max. Versorgungsstrom
    </td>
    <td colspan="2">
      150mA
    </td>
</tr>
  <tr>
    <td>
      Drehzahlschwelle aktiv
    </td>
    <td colspan="2">
      >2050 U/min
    </td>
</tr>
  <tr>
    <td>
      Drehzahlschwelle inaktiv
    </td>
    <td colspan="2">
      <2000 U/min
    </td>
</tr>
  <tr>
  <td>
    maximale Summer-Lautstärke
  </td>
  <td colspan="2">
    ~90 dBA
  </td>
</tr>
 <tr>
  <td>
    Umgebungstemperatur
  </td>
  <td colspan="2">
    -40°C ... 85°C
  </td>
</tr>
</table>

### ersetzt folgende Öldruckplatinen:
251 919 064 A  
251 919 064 B  
251 919 064 C  
251 919 064 D  
251 919 064 G  
321 919 064 M  
  
251 919 253 F  
251 919 253 G  
251 919 253 H  
251 919 253 J  
251 919 253 K  
251 919 253 L  

### changelog:
**REV1d - ab 03.06.2026:** Funktion identisch zu REV1c, zusätzliche Bauteile wurden auf der Platine untergebracht (händisches Löten fällt weg)  
**REV1d - ab 21.06.2026:** Alarm-Wartezeit von 5 Sek auf 2 Sek reduziert, über 9000 U/min zirpt der Buzzer aufgrund falscher Motoreinstellung/Übersetzung

251919064A 251919064B 251919064C 251919064D 251919064G 321919064M 251919253F 251919253G 251919253H 251919253J 251919253K 251919253L  
