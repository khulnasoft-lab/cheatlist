# nix-build

> Erstellen eines Nix-Ausdrucks.
> Weitere Informationen: <https://nixos.org/manual/nix/stable/command-ref/nix-build.html>.

- Erstelle einen Nix-Ausdruck:

`nix-build '<nixpkgs>' --attr {{firefox}}`

- Erstelle einen gesandboxten Nix-Ausdruck (auf nicht-NixOS):

`nix-build '<nixpkgs>' --attr {{firefox}} --option sandbox true`
