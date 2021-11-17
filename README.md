# Procégraphe

From source code to graphs

Note: the accent on "Procégraphe" is not a typo. This is written by a mad french guy who thinks strict ASCII is totally out of fashion.

## Usage

Procégraphe is supposed to **help analysts** in the tedious task of figuring out what the source code they find anywhere on the Internet or in their socks can be used for, or worse: how can it even work?

1. Give it the source code
2. Tell it what it is supposed to look for
3. Tell it do the job
4. Enjoy the graph(s) it spits so you can finally find what is where in this f... source code and how all those thingies relate together.

## Features (no yet implemented)

Procégraphe build graphes from relations found in source codes. It doesn't run the source code in order to discover procedural relations, so it only export static nodes and relations.

It may graph:

- variables dependencies
- types dependencies
- potential methods or procedure calls
- class inheritance
- prototype inheritance
- object inheritance
- scopes
- URI links
- DOM inheritance

## Input formats

- single **AppleSoft BASIC** utf8 file
- single **LOGO** utf8 file
- single **Graphisoft GDL** utf8 file
- single **POV-RAY** file utf8 file
- **Python** module as folder
- **Rust** cargo
- Full **PHP + MySQL website on Apache** as folder

## Output formats

- GraphViz **DOT**
- **GraphML**
- Gephi **GEXF**
- GUESS **GDF**
- **GML**
- Pajek **NET**
- UCINET **DL**
- Tulip **TPL**
- Netdraw **VNA**
