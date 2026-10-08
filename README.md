<p align="center"><img src="https://raw.githubusercontent.com/ilscipio/flexible-delphi-jetbrains-plugin/main/pluginIcon.svg" width="80" alt="Flexible Delphi"></p>

# [Flexible Delphi](https://plugins.jetbrains.com/search?search=Flexible%20Delphi)

Delphi and Free Pascal in your JetBrains IDE. A Delphi form designer that links every event to its code. Completion, hover docs, refactoring, compile and debug. Opens old Delphi projects with binary forms, and current Delphi code with generics, anonymous methods and inline variables.

**Flexible Delphi is a young plugin. Please leave a review, open a GitHub issue, or write to info@ilscipio.com. Report a bug or an idea and get 20% off the annual license, or one month free.**

This repository holds the issue tracker and the documentation of the plugin. The plugin itself is proprietary and is available on the [JetBrains Marketplace](https://plugins.jetbrains.com/search?search=Flexible%20Delphi).

## Install

1. In IntelliJ IDEA, PyCharm, WebStorm, CLion or another JetBrains IDE, open **Settings > Plugins > Marketplace**.
2. Search for **Flexible Delphi** and click **Install**.
3. Restart the IDE.
4. Open a folder with Delphi or Free Pascal code (`.pas`, `.dpr`, `.lpr`, `.dfm`, `.lfm`).
5. To compile, run and debug, install [Free Pascal](https://www.freepascal.org/) or [Lazarus](https://www.lazarus-ide.org/), then open **Settings > Languages & Frameworks > Delphi Toolchain** and click **Detect and register installed SDKs**.

The plugin comes with a 30-day free trial. It is free for students and teachers, classroom assistance, open source projects and the Developer Recognition Program. Universities and educational organizations, startups and non-profit organizations get 50% off, and former student license holders get 40% off.

## Core Features

### Language Support
* **Native Object Pascal parser** for Delphi, Free Pascal (Delphi and ObjFPC modes), Turbo Pascal and ISO Pascal. No language server is needed
* **Conditional compilation**: `{$IFDEF}`, `{$IF}`, `{$ELSE}` and `{$DEFINE}` are evaluated with the project defines, and inactive code is grey
* **Old and new code**: ANSI (Windows-1252) source detection, Turbo Pascal control characters, generics, attributes, anonymous methods, inline variables, multiline strings and the `if` expression
* **Form files**: text DFM, LFM and FMX files with highlighting, and binary DFM files of older Delphi versions
* **Semantic highlighting**, folding, and a formatter in Delphi style

### Navigation & Intelligence
* **Go to Declaration** across units, uses clauses, unit scope names, inherited members and generic types
* **Declaration and implementation** with Ctrl+Shift+Up and Ctrl+Shift+Down, as in Delphi
* **Class completion** with Alt+Enter, or Ctrl+Shift+C in the Delphi keymap: missing method bodies, property fields and property accessors
* **Call Hierarchy**: the callers and the callees of a routine
* **Find Usages** and **Rename**, case-insensitive, including the implementation and the form file. Usages show as read or write
* **Structure View**, **Breadcrumbs**, **Go to Symbol** and **Go to Class**

### Completion & Documentation
* **Code completion** that opens after a dot, for members, unit names, types, keywords and compiler directives. Private members show only where Delphi allows them
* **Parameter info** (Ctrl+P) with every overload, and parameter name hints
* **Hover documentation** from `///` XMLDoc comments, and bundled documentation for 320 RTL and VCL symbols
* **28 code templates** from the Delphi IDE, and postfix templates such as `.if`, `.notnil`, `.forin` and `.tryf`

### Inspections & Quick Fixes
* **Alt+Enter on an unknown name**: add the unit to the uses clause, declare a local variable or a field, or create the routine
* Unresolved identifier, unused unit, unused local variable, function result not set, missing method implementation, empty except block, missing `inherited`, unreachable code, assignment to a for-loop variable, and Delphi-only syntax in Free Pascal files

### Language Injection
* **Built-in assembler** in `asm ... end` blocks
* **SQL, RegExp, JSON, HTML and XML** in strings and in form files (`SQL.Strings`)

### Form Designer
* **Design tab** for every unit with a form. F12 switches between form and code in the Delphi keymap
* **Component palette**, **canvas** and **Object Inspector** with Properties and Events
* **Double-click a component or an event** to create the handler in the unit and jump to it
* **Binary DFM files** open in the designer and save back as binary

### Compile, Run & Debug
* **SDKs** for Free Pascal, Lazarus and Delphi
* **Project import** from `.dproj`, `.lpi`, `.dof` and `.cfg` files
* **Run configurations** with clickable compiler messages, and a **Delphi keymap** with Ctrl+F9, Shift+F9, F12 and Ctrl+Shift+C
* **Debugger** for Free Pascal and Lazarus builds (GDB), with Step Over and Step Into that stay in your code
* **New project wizard** for console, LCL form, VCL form and library projects

### MCP Server
* **Embedded MCP server** for MCP clients: code structure, references, completion, documentation, inspections, forms, and compile, run and debug

## Links

* [Report a bug or an idea](https://github.com/ilscipio/flexible-delphi-jetbrains-plugin/issues)
* [JetBrains Marketplace](https://plugins.jetbrains.com/search?search=Flexible%20Delphi)
* [Ilscipio](https://www.ilscipio.com)

Flexible Delphi is an independent plugin and is not affiliated with Embarcadero Technologies, the Free Pascal and Lazarus projects, or JetBrains.

## License

The plugin is proprietary software under the [End User License Agreement](https://www.ilscipio.com/en/end-user-license-agreement-eula-of-jetbrains-plugin/). The documentation in this repository is licensed under [CC BY 4.0](LICENSE.DOC).
