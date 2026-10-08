# Motion & Animation

Use motion to communicate hierarchy and state, not decoration for its own sake.

Guidelines:
- prefer transform/opacity for performant transitions;
- respect prefers-reduced-motion;
- avoid blocking first interaction;
- keep animation durations consistent;
- use skeletons only when they clarify loading;
- test on low-power mobile devices.

Do not animate critical content in ways that harm readability or accessibility.
