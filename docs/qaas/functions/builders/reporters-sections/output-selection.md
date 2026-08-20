---
id: qaas.functions.builders.reporters.sections.output.selection
type: reference
status: stable
since: 2.0.0
last_verified: 2026-05-27
applies_to: [runner]
keywords: [runner, reference]
summary: "Reference page for Reporters: Output selection."
---

<!-- Verified-against: QaaS.Runner\QaaS.Runner.Assertions\ConfigurationObjects\ReporterBuilder.cs -->

# Reporters: Output selection

> TL;DR — This page mirrors the `Output selection` section from [Reporters](../reporters.md) as a focused reference.

## When to use {: #when-to-use}

Use this page when you need the focused member list, signatures, and source notes for this section without scanning the full parent reference.

## C# (CAC) usage {: #c-cac-usage}

### `ShouldSaveTerminalOutput` {: #shouldsaveterminaloutput}

??? info "Source file, signature, and docstring"
    **Member**
    `ReporterBuilder.ShouldSaveTerminalOutput(bool shouldSaveTerminalOutput)`
    
    **Kind** `function`
    
    **Declaring Type** `ReporterBuilder`
    
    **Source File** `QaaS.Runner.Assertions/ConfigurationObjects/ReporterBuilder.cs`
    
    **Signature**
    ```csharp
    public ReporterBuilder ShouldSaveTerminalOutput(bool shouldSaveTerminalOutput)
    ```
    
    **Docstring**
    
    Configures whether all terminal output from the QaaS execution is saved once per launch as an terminal.log attachment.

## Edge cases {: #edge-cases}

- This page is generated from the parent reference section; edit the source XML docs or generator when content needs to change.
- If a linked source member is renamed, regenerate the reference docs before changing prose by hand.

## See also {: #see-also}

- [Reporters](../reporters.md)
