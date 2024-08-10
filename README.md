<div align="center">
    <a href="https://github.com/notnotmelon/rivets">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://forums.factorio.com/images/ext/20b0f93fa0933e4aa7df8592f124d153.png">
        <img alt="Rivets 🔩 - the Factorio mod loader" width="75%" style="max-width: 600px" src=".github/assets/logo-horizontal.png">
    </picture>
    </a>

[![Discord](https://img.shields.io/discord/1260754935952314418?color=lightblue&label=Community%20Chat&logo=Discord&logoColor=aqua)](https://discord.gg/xRYEZYz5WR)
![Downloads](https://img.shields.io/crates/d/rivets)
[![](https://img.shields.io/badge/License-Rivets_2024-green)](https://github.com/factorio-rivets/pdb2hpp/blob/master/LICENSE.md)

</div>

# pdb2hpp 🔩

A tool designed to create rust FFI bindings for Factorio's compiled C++ classes, structs, and unions.
Works by parsing the debug symbols contained in `factorio.pdb`.

# Examples

Running the following command:
`> pdb2hpp LuaSurface`

Would generate the following FFI binding:


# Credits

Inspired by the wonderful [PDB crate](https://github.com/getsentry/pdb/blob/master/examples/pdb2hpp.rs).