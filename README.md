#relproof

One of the biggest problems in the open-source world today is the inability to verify whether binaries downloaded from release pages actually match the source code. Unfortunately, users and developers often have to rely on blind trust.

With this project, we are fundamentally solving this problem: We are developing mechanisms for independent rebuilding, creating signed attestations for Rekor, and making this mandatory during installation.

The final outputs of the project will be: Nix recipes, a rebuilderd-compatible backend structure, a quickly usable verification tool, and practical installation packages. Our goal is to close this trust gap in the supply chain and make the process completely transparent.
