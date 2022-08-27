---
sidebar_position: 2
#
# This file is autogenerated. DO NOT MODIFY DIRECTLY
#
---

import ScriptEventPreview from '@site/src/components/ScriptEventPreview';

# Scene

## Change Scene
<ScriptEventPreview title={"Change Scene"} fields={[{"key":"sceneId","label":"Scene","type":"scene","defaultValue":"LAST_SCENE"},{"key":"x","label":"X","type":"number","min":0,"max":255,"defaultValue":0,"width":"50%"},{"key":"y","label":"Y","type":"number","min":0,"max":255,"defaultValue":0,"width":"50%"},{"key":"direction","label":"Direction","type":"direction","width":"50%","defaultValue":""},{"key":"fadeSpeed","label":"Fade Speed","type":"fadeSpeed","defaultValue":"2","width":"50%"}]} />

- **Scene**  
- **X**  
- **Y**  
- **Direction**  
- **Fade Speed**  

## Remove All From Scene Stack
<ScriptEventPreview title={"Remove All From Scene Stack"} fields={[{"label":"Clears the stack of saved scene states."}]} />

- **Clears the stack of saved scene states.**  

## Restore First Scene From Stack
<ScriptEventPreview title={"Restore First Scene From Stack"} fields={[{"label":"Pop all scene state from stack."},{"type":"break"},{"key":"fadeSpeed","label":"Fade Speed","type":"fadeSpeed","defaultValue":"2","width":"50%"}]} />

- **Pop all scene state from stack.**  
- **Fade Speed**  

## Restore Previous Scene From Stack
<ScriptEventPreview title={"Restore Previous Scene From Stack"} fields={[{"label":"Pop the top scene state from stack."},{"type":"break"},{"key":"fadeSpeed","label":"Fade Speed","type":"fadeSpeed","defaultValue":"2","width":"50%"}]} />

- **Pop the top scene state from stack.**  
- **Fade Speed**  

## Store Current Scene On Stack
<ScriptEventPreview title={"Store Current Scene On Stack"} fields={[{"label":"Push scene state to stack."}]} />

- **Push scene state to stack.**  
