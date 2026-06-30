I am building an interactive tutorial website (HTML/CSS/JS, single file or index.html + style.css) for a Roblox game called BaBFT (Build a Bridge for Tresure). The game has a logic gate system. I am building a tutorial that visually explains every logic gates and how to make full circuits.

= AVAILABLE GATES IN BABFT = AND, OR, XOR, NAND, NOR, XNOR NO standalone NOT gate exists. To invert a signal: use NOR(signal, 0) = NOT(signal) — tie one input of a NOR gate permanently to 0. — this is the ONLY way to invert.

= KEY RULES =

No standalone NOT gate — always NOR(signal, 0) to invert
AND gate: output = 1 ONLY if ALL inputs = 1, any 0 input → output = 0
NOR gate: output = 1 ONLY if ALL inputs = 0
NAND gate: output = 0 ONLY if ALL inputs = 1
XOR gate: output = 1 if inputs are DIFFERENT (one 0, one 1)
XNOR gate: output = 1 if inputs are SAME (both 0 or both 1)
= WANT A SITE DEDICATED TO THIS FOR BUILD A BOAT FOR TRESURE PEOPLE TO HAVE A GUIDE TO LOGIC =
