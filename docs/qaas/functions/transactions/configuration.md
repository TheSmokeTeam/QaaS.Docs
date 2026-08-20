---
id: qaas.functions.transactions.configuration
type: reference
status: stable
since: 2.0.0
last_verified: 2026-05-27
applies_to: [runner]
keywords: [runner, reference]
summary: "Reference page for Configuration."
---

<!-- Verified-against: QaaS.Runner\QaaS.Runner.Sessions\Actions\Transactions\Builders\TransactionBuilder.cs -->

# Configuration

> TL;DR — This page lists the public Runner functions in the `Configuration` category.

## When to use {: #when-to-use}

Use this page when you need source-backed signatures, declaring types, and XML doc comments for this function category.

Each entry uses the short function name as the table-of-contents label. Expand an entry to inspect its source file, signature, and XML doc comments.


## `WithEmptyRequest` {: #withemptyrequest}

??? info "Source file, signature, and docstring"
    **Member**
    `TransactionBuilder.WithEmptyRequest()`
    
    **Kind** `function`
    
    **Declaring Type** `TransactionBuilder`
    
    **Source File** `QaaS.Runner.Sessions/Actions/Transactions/Builders/TransactionBuilder.cs`
    
    **Signature**
    ```csharp
    public TransactionBuilder WithEmptyRequest()
    ```
    
    **Docstring**
    
    Configures the transaction to send one bodyless HTTP GET per iteration without reading from a data source.
    
    Configure an HTTP GET before building the transaction. Non-empty data-source selectors and input serialization are mutually exclusive with this mode.

## See also {: #see-also}

- [Runner Functions](../index.md)
