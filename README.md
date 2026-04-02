# How to change the selection background for the selected BackStage items in WPF Ribbon control?

This sample demonstrates how to change the selection background for the selected [BackStage](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Tools.Controls.Backstage.html) items in [WPF Ribbon](https://www.syncfusion.com/wpf-ui-controls/ribbon) control.

## Overview
You can change the background color of selected and hovered BackStage items by overriding the style and setting the background to appropriate elements in the style in WPF Ribbon control. This approach allows developers to customize the appearance of BackStage items to match the theme or branding of their application.

### Why Customize BackStage Items?
The BackStage view in Ribbon provides a way to display additional options like settings, recent files, and application-level commands. By default, BackStage items have a predefined style. Customizing the selection and hover background improves user experience and visual consistency.

## How It Works
- **Override Default Style**: Create a custom style for BackStage items and apply it to the Ribbon control.
- **Set Background for States**: Define triggers for `IsSelected` and `IsMouseOver` states to apply different background colors.
- **Apply Consistent Theme**: Ensure that the customized style aligns with the overall application theme.

## Steps to Implement
1. Define a custom `Style` targeting `BackStageTabItem` in XAML.
2. Use `ControlTemplate` or `Setter` to modify the `Background` property.
3. Add triggers for selection and hover states.
4. Apply the style to BackStage items in the Ribbon.

## Benefits
- Enhances visual appearance of BackStage items.
- Provides flexibility to match corporate branding or user preferences.
- Improves accessibility by allowing better color contrast.

## Documentation
- KB Article: [How to change the selection background for the selected backstage items in WPF Ribbon control?](https://www.syncfusion.com/kb/8256/how-to-change-the-selection-background-for-the-selected-backstage-items-in-wpf-ribbon)
- Documentation: [Syncfusion WPF Ribbon BackStage Customization](https://support.syncfusion.com/kb/article/7370/how-to-change-the-selection-background-for-the-selected-backstage-items-in-wpf-ribbon)

---

### Requirements
Ensure that the **Syncfusion.Tools.WPF** assembly is referenced in your WPF application to use the Ribbon and BackStage controls successfully.

