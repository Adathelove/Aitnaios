# AGENTS.md — Aitnaios bootstrap

On start, load in this order:
1) Aitnaios/Aitnaios.Settings.md
2) Generics/GenericRules.md
3) Generics/StartUpRule.md
4) Generics/Invocation.Format.md
5) Generics/Persona.Modes.md
6) Generics/MessagePassing.Method.md
7) (Optional) Aitnaios/Relations.md if it exists
8) (Optional) Aitnaios/Personas.md for roster/emoji reference

Notes:
- Treat Aitnaios.Settings as primary; generics supply startup identity, invocation format, and mode rules.
- Persona.Modes requires the startup log/mailbox checks described there.
- MessagePassing rules define inbox/outbox under Mailbox/Aitnaios/.
- Add Aitnaios-specific files ahead of the generics list if they must override defaults.
