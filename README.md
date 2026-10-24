<!--
// Copyright (C) 2026 The Qt Company Ltd.
// SPDX-License-Identifier: LicenseRef-Qt-Commercial OR GFDL-1.3-no-invariants-only
-->

# Qt Bridge for C# &ndash; Examples

Each example is contained in its own directory. Some examples also include a `README.md` file
with additional notes.

| Example | Description |
|---------|-------------|
| [Bookshelf](Bookshelf) | Demonstrates all three Qt Bridge resource access modes (`Native`, `ManagedAndNative` and `ManagedOnly`) using a book library application that reads cover art, synopsis text, and app metadata from `.resx` and Qt resources. |
| [CityTemperatures](CityTemperatures) | Shows how to model and display tabular data from multiple cities using a C# data class exposed to a QML view. |
| [ModelsAndViews](ModelsAndViews) | Shows how to expose C# data to QML `ListView`, `TableView`, and `TreeView` using the corresponding Qt Bridge model types. |
| [Primes](Primes) | Demonstrates prime number generation exposed to QML through multiple model patterns: static value lists, observable collections, item models, and event-driven models. |
| [SpreadsheetSandbox](SpreadsheetSandbox) | Shows how to build a two-dimensional spreadsheet-like data model in C# and expose it to a QML table view. |
| [Weather](Weather) | Weather forecast for the current location. |
