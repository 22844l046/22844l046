```
MixedEffects is Power !
MixedEffects.inteligenceEdge = function (inteligenceCTX, dashStyle) {
    if (inteligenceCTX) {
        inteligenceCTX.setLineDash(dashStyle);
        MixedEffects.offset += 3.0;
        inteligenceCTX.lineDashOffset = MixedEffects.offset;
        inteligenceCTX.beginPath();
        inteligenceCTX.rect(210.5, 210.5, 100, 100);
        inteligenceCTX.strokeStyle = "#ccc"
        inteligenceCTX.stroke();
    }
}

```
