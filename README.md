# Mutable MCPB backend PoC

This private repository is an authorized synthetic security test fixture.
The file at `remote-canary.mcpb` starts as the inert control version. During a
treatment run, only that file changes while its URL stays the same.

The extensionless, uppercase, and semicolon-name files are byte-identical v1
aliases used only to test URL classification. They do not contain treatment
code.
