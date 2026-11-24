<!--
// Copyright (C) 2026 The Qt Company Ltd.
// SPDX-License-Identifier: LicenseRef-Qt-Commercial OR GFDL-1.3-no-invariants-only
-->

# Qt Bridge for C# &ndash; Examples

[People&nbsp;Directory](#people-directory) |
[Weather](#weather) |
[Bookshelf](#bookshelf) |
[Spreadsheet&nbsp;Sandbox](#spreadsheet-sandbox) |
[Models&nbsp;and&nbsp;Views](#models-and-views) |
[City&nbsp;Temperatures](#city-temperatures) |
[Primes](#primes)

## [People Directory](PeopleDirectory)

MVVM C# app example implemented both with WPF and with Qt Quick. The two implementations share a
core library containing the Model and ViewModel layers. The core library works with both WPF and
Qt Quick implementations without requiring any changes.

[![People Directory](.github/assets/people_directory.png)](PeopleDirectory)

[⇧ Top](#qt-bridge-for-c-–-examples)

## [Weather](Weather)

Weather forecast for the current location.

[![Weather](.github/assets/weather.png)](Weather)

[⇧ Top](#qt-bridge-for-c-–-examples)

## [Bookshelf](Bookshelf)

Demonstrates all three Qt Bridge resource access modes (`Native`, `ManagedAndNative` and
`ManagedOnly`) using a book library application that reads cover art, synopsis text, and app
metadata from `.resx` and Qt resources.

[![Bookshelf](.github/assets/bookshelf.png)](Bookshelf)

[⇧ Top](#qt-bridge-for-c-–-examples)

## [Spreadsheet Sandbox](SpreadsheetSandbox)

Shows how to build a two-dimensional spreadsheet-like model in C# and expose it to a QML table view.

[![Spreadsheet Sandbox](.github/assets/spreadsheet_sandbox.png)](SpreadsheetSandbox)

[⇧ Top](#qt-bridge-for-c-–-examples)

## [Models and Views](ModelsAndViews)

Shows how to expose C# data to QML `ListView`, `TableView`, and `TreeView` using the corresponding
Qt Bridge model types.

[![Models and Views](.github/assets/models_and_views.png)](ModelsAndViews)

[⇧ Top](#qt-bridge-for-c-–-examples)

## [City Temperatures](CityTemperatures)

Shows how to model and display tabular data from multiple cities using a C# data class exposed to a
QML view.

[![City Temperatures](.github/assets/city_temperatures.png)](CityTemperatures)

[⇧ Top](#qt-bridge-for-c-–-examples)

## [Primes](Primes)

Demonstrates prime number generation exposed to QML through multiple model patterns: static value
lists, observable collections, item models, and event-driven models.

[![Primes](.github/assets/primes.png)](Primes)

[⇧ Top](#qt-bridge-for-c-–-examples)
