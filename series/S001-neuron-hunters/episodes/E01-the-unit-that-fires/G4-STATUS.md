# G4 status

| Subgate | Status |
| --- | --- |
| G4.1 Voices | PASS |
| G4.2 Recast | PASS |
| G4.3 Sound bed | PASS |
| G4.4 Master / regression | **OPEN** — candidate, not PASS |

## Candidate specs

- Source: G4.3 recast + bed (locked meaning)
- Target: −18 LUFS integrated, −1.5 dBTP, mono 44.1 kHz
- Measured on candidate: −17.8 LUFS, −1.5 dBTP, LRA 4.1 LU
- Fade in 0.4 s / fade out ~1.6 s on tail
- Deliverables (session artifacts): `S001-E01-G4-MASTER-candidate.wav` and `.mp3` @ 192 kb/s

G4.4 PASS only after identity / registration / absence regression on **this** file, and explicit accept of loudness/format.
No story changes in this gate.
