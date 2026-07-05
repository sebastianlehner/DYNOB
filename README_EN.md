# dynamic oil buzzer REV1d  
#### EN - [manual](https://github.com/sebastianlehner/DYNOB/blob/main/dynamic_oil_buzzer_REV1d_EN.pdf)
#### DE - [Bedienungsanleitung](https://github.com/sebastianlehner/DYNOB/blob/main/dynamic_oil_buzzer_REV1d_DE.pdf)  

#### function overview / mounting instructions - [https://youtu.be/VGgJPHZ6h68](https://youtu.be/VGgJPHZ6h68)
#### learning mode - [https://youtu.be/bumlYxhFiTA](https://youtu.be/bumlYxhFiTA)
<img width="450" height="450" alt="dyn_oil_buzzer_REV1d_Uebersicht" src="https://github.com/user-attachments/assets/c9ba2301-ec27-43f6-be9d-d74610d9175b" />

This circuit board serves as a **dynamic oil pressure monitor** for diesel and benzin engines.  
When the engine speed exceeds **2050 RPM**, oil pressure 2 is checked (this function is inactive when the engine speed is below 2000 RPM).  
Furthermore, the circuit board beeps and flashes if the engine speed is lost despite oil pressure 2 being present (V-belt failure in diesel engines).  

If oil pressure 1 is lost, the LED flashes immediately. If another fault occurs, this is signaled <ins>after 2 seconds</ins> (LED and buzzer).  
If a speed <ins>above 9000 rpm</ins> is detected, the buzzer will beep and the LED will stay on! (incorrect motor setting/gear ratio)
<ins> </ins>
### compatibility:
**VW T3, Golf 1, Golf 2, Polo 2, Caddy 1, Jetta 2, Passat B2 und Scirocco 2**


### advantages:

- plug and play, replaces all older circuit board versions
- for all diesel and petrol engines (4, 5, 6 and 8 cylinders)
- learning mode for non-standard belt ratios
- detects V-belt failure in diesel engines (loss of engine speed if oil pressure 2 is present)

### specifications
<table class="vclTable">
  <tr>
    <td>
      supply voltage
    </td>
    <td colspan="2">
      6V ... 16 V
    </td>
  </tr>
  <tr>
    <td>
      supply current
    </td>
    <td colspan="2">
      5mA
    </td>
</tr>
  <tr>
    <td>
      max. supply current
    </td>
    <td colspan="2">
      150mA
    </td>
</tr>
  <tr>
    <td>
      RPM threshold (active)
    </td>
    <td colspan="2">
      >2050 RPM
    </td>
</tr>
  <tr>
    <td>
      RPM threshold (inactive)
    </td>
    <td colspan="2">
      <2000 RPM
    </td>
</tr>
  <tr>
  <td>
    max. loudness
  </td>
  <td colspan="2">
    ~90 dBA
  </td>
</tr>
 <tr>
  <td>
    ambient temperature
  </td>
  <td colspan="2">
    -40°C ... 85°C
  </td>
</tr>
</table>

### replaces the following dyn. oil pressure boards:
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
**REV1d - starting June 03, 2026:** Functionality identical to REV1c, additional components have been added to the circuit board (manual soldering is no longer required)  
**REV1d - starting June 21, 2026:** Alarm delay reduced from 5 seconds to 2 seconds, above 9000 rpm the buzzer beeps due to incorrect motor settings or gear ratio
