---
sidebar_position: 2
#
# This file is autogenerated. DO NOT MODIFY DIRECTLY
#
---

import ScriptEventPreview from '@site/src/components/ScriptEventPreview';

# Eingabe

## Joypad-Eingabe: Binde Skript An Eingabe
Run the specified script any time a joypad button is pressed.
<ScriptEventPreview title={"Joypad-Eingabe: Binde Skript An Eingabe"} fields={[{"key":"input","label":"Button","description":"The joypad button to check.","type":"input","defaultValue":["b"]},{"key":"override","type":"checkbox","label":"Überschreibe Standard-Tasten-Aktion","description":"Set if the script should replace the default game action for the specified button.","defaultValue":true},{"key":"__scriptTabs","type":"tabs","defaultValue":"press","values":{"press":"Durch Drücken von"}},{"key":"true","label":"Durch Drücken von","description":"The script to run when the button is pressed.","type":"events","allowedContexts":["global","entity"],"conditions":[{"key":"__scriptTabs","in":[null,"press"]}]}]} />

- **Button**: The joypad button to check.  
- **Überschreibe Standard-Tasten-Aktion**: Set if the script should replace the default game action for the specified button.  
- **Durch Drücken von**: The script to run when the button is pressed.  

## Falls Joypad-Eingabe Gedrückt
Conditionally run part of the script if the specified joypad button is currently pressed. Will not wait for user input and will only execute once, if you wish to run a script every time a button is pressed use Attach Script To Button instead.

**Referenzen**  
[/docs/scripting/script-glossary/input#attach-script-to-button](/docs/scripting/script-glossary/input#attach-script-to-button)<ScriptEventPreview title={"Falls Joypad-Eingabe Gedrückt"} fields={[{"key":"input","label":"Beliebiges von","description":"The input buttons to check.","type":"input","defaultValue":["a","b"]},{"key":"true","label":"Wahr","description":"The script to run if the condition is true.","type":"events"},{"key":"__collapseElse","label":"Andernfalls","type":"collapsable","defaultValue":true,"conditions":[{"key":"__disableElse","ne":true}]},{"key":"false","label":"Falsch","description":"The script to run if the condition is false.","conditions":[{"key":"__collapseElse","ne":true},{"key":"__disableElse","ne":true}],"type":"events"}]} />

- **Beliebiges von**: The input buttons to check.  
- **Wahr**: The script to run if the condition is true.  
- **Falsch**: The script to run if the condition is false.  

## Joypad-Eingabe: Skript Pausieren Bis Gedrückt
Pauses the script until one of the specified joypad buttons are pressed.
<ScriptEventPreview title={"Joypad-Eingabe: Skript Pausieren Bis Gedrückt"} fields={[{"key":"input","label":"Beliebiges von","description":"The input buttons to check.","type":"input","defaultValue":["a","b"]}]} />

- **Beliebiges von**: The input buttons to check.  

## Joypad-Eingabe: Entferne Skript Von Eingabe
Remove an attached script from a joypad button restoring the default functionality of the button.
<ScriptEventPreview title={"Joypad-Eingabe: Entferne Skript Von Eingabe"} fields={[{"key":"input","label":"Entfernt angefügtes Skript von Eingabe","description":"The joypad button to remove the attached script from.","type":"input","defaultValue":["b"]}]} />

- **Entfernt angefügtes Skript von Eingabe**: The joypad button to remove the attached script from.  
