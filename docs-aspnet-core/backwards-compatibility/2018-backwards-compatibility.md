---
title: 2018 Releases
page_title: 2018 Releases | Telerik UI for ASP.NET Core
description: "Learn about the breaking changes and backwards compatibility released by Telerik UI for ASP.NET Core in 2018."
previous_url: https://docs.telerik.com/aspnet-core/backwards-compatibility
slug: breakingchanges_aspnetcore
position: 1
---

# 2018 Releases

## Kendo UI R1 2018 SP1

### Changes from 2018 R1

To enable more complex widget configuration scenarios and ensure the tag-naming consistency across the Telerik UI for ASP.NET Core suite, the Kendo UI R1 2018 release introduces changes in the tags of the following wrappers:

* Dialog&mdash;Previously, it was possible to nest content directly in the `<kendo-dialog>` tag. Now the content must be nested within a `<content>` tag.
* Window&mdash;Previously, it was possible to nest content directly in the `<kendo-window>` tag. Now the content must be nested within a `<content>` tag.
* Upload:
  * The `<kendo-upload-async-settings>` tag name is now changed to `<async>`.
  * The `<kendo-upload-files>` tag name is now changed to `<files>`.
  * The `<kendo-upload-file>` tag name is now changed to `<file>`.
  * The `<kendo-upload-localization-settings>` tag name is now changed to `<localization>`.
  * The `<kendo-upload-validation-settings>` tag name is now changed to `<validation>`.
* Splitter&mdash;Previously, the tag name of the pane was `<kendo-splitter-pane>`. The tag name is now changed to `<pane>`.

[Telerik UI for ASP.NET Core](http://www.telerik.com/aspnet-core-ui) is a set of server-side wrappers that allows you to use the [Kendo UI widgets](../kendo-ui/introduction) from the server code. That is why, all important changes in the Kendo UI suite also apply to the client-side code and behavior of the Telerik UI for ASP.NET Core wrappers. For the list of all breaking changes, refer to the articles on the [Kendo UI breaking changes](../kendo-ui/backwards-compatibility/2017-backward-compatibility).

## See Also

* [Kendo UI 2016 Breaking Changes](../kendo-ui/backwards-compatibility/2016-backward-compatibility)
* [Kendo UI 2015 Breaking Changes](../kendo-ui/backwards-compatibility/2015-backward-compatibility)
* [Kendo UI 2014 Breaking Changes](../kendo-ui/backwards-compatibility/2014-backward-compatibility)
* [Kendo UI 2013 Breaking Changes](../kendo-ui/backwards-compatibility/2013-backward-compatibility)
* [Kendo UI 2012 Breaking Changes](../kendo-ui/backwards-compatibility/2012-backward-compatibility)
