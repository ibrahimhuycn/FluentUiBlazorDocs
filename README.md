# FluentUI Blazor Documentation (ATTN: GENERATED README FILE)

A comprehensive collection of Fluent UI Blazor component documentation extracted from the official [Fluent UI Blazor documentation site](https://www.fluentui-blazor.net/) (Version: 4.12.1+dc098671).

## 🎯 Purpose

This repository serves as a curated documentation resource specifically designed to provide **context to Large Language Models (LLMs)** through **GitMCP (Model Context Protocol)**. It enables AI assistants to have detailed knowledge of Fluent UI Blazor components, their APIs, usage patterns, and best practices.

## 🚀 Quick Start with GitMCP

### MCP Server URL
```
https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs
```

### AI Assistant Integration

#### Cursor
Add to your `~/.cursor/mcp.json`:
```json
{
  "mcpServers": {
    "FluentUI Blazor Docs": {
      "url": "https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs"
    }
  }
}
```

#### Claude Desktop
Add to your `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "FluentUI Blazor Docs": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs"
      ]
    }
  }
}
```

#### Windsurf
Add to your `~/.codeium/windsurf/mcp_config.json`:
```json
{
  "mcpServers": {
    "FluentUI Blazor Docs": {
      "serverUrl": "https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs"
    }
  }
}
```

#### Other Supported Platforms
- **VSCode** - See [GitMCP Integration Guide](https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs)
- **Cline** - See [GitMCP Integration Guide](https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs)
- **Highlight AI** - See [GitMCP Integration Guide](https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs)
- **Augment Code** - See [GitMCP Integration Guide](https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs)
- **Msty AI** - See [GitMCP Integration Guide](https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs)

## 📚 Documentation Coverage

This repository contains comprehensive documentation for Fluent UI Blazor components including:

### Core Components

| Component | Documentation | Official URL |
|-----------|---------------|--------------|
| **Button** | ✅ Available | [FluentButton](https://www.fluentui-blazor.net/Components/Button) |
| **Card** | ✅ Available | [FluentCard](https://www.fluentui-blazor.net/Components/Card) |
| **DataGrid** | ✅ Available | [FluentDataGrid](https://www.fluentui-blazor.net/Components/DataGrid) |
| **Dialog** | ✅ Available | [FluentDialog](https://www.fluentui-blazor.net/Components/Dialog) |
| **Icon** | ✅ Available | [FluentIcon](https://www.fluentui-blazor.net/Components/Icon) |
| **Menu** | ✅ Available | [FluentMenu](https://www.fluentui-blazor.net/Components/Menu) |
| **ProgressRing** | ✅ Available | [FluentProgressRing](https://www.fluentui-blazor.net/Components/ProgressRing) |
| **Select** | ✅ Available | [FluentSelect](https://www.fluentui-blazor.net/Components/Select) |
| **Tabs** | ✅ Available | [FluentTabs](https://www.fluentui-blazor.net/Components/Tabs) |
| **TextField** | ✅ Available | [FluentTextField](https://www.fluentui-blazor.net/Components/TextField) |
| **Toast** | ✅ Available | [FluentToast](https://www.fluentui-blazor.net/Components/Toast) |
| **Toolbar** | ✅ Available | [FluentToolbar](https://www.fluentui-blazor.net/Components/Toolbar) |
| **Tooltip** | ✅ Available | [FluentTooltip](https://www.fluentui-blazor.net/Components/Tooltip) |
| **TreeView** | ✅ Available | [FluentTreeView](https://www.fluentui-blazor.net/Components/TreeView) |
| **Wizard** | ✅ Available | [FluentWizard](https://www.fluentui-blazor.net/Components/Wizard) |

### Form Components

| Component | Documentation | Official URL |
|-----------|---------------|--------------|
| **Checkbox** | ✅ Available | [FluentCheckbox](https://www.fluentui-blazor.net/Components/Checkbox) |
| **Radio** | ✅ Available | [FluentRadio](https://www.fluentui-blazor.net/Components/Radio) |
| **Switch** | ✅ Available | [FluentSwitch](https://www.fluentui-blazor.net/Components/Switch) |
| **Slider** | ✅ Available | [FluentSlider](https://www.fluentui-blazor.net/Components/Slider) |
| **DatePicker** | ✅ Available | [FluentDatePicker](https://www.fluentui-blazor.net/Components/DatePicker) |
| **TimePicker** | ✅ Available | [FluentTimePicker](https://www.fluentui-blazor.net/Components/TimePicker) |

### Layout Components

| Component | Documentation | Official URL |
|-----------|---------------|--------------|
| **Stack** | ✅ Available | [FluentStack](https://www.fluentui-blazor.net/Components/Stack) |
| **Grid** | ✅ Available | [FluentGrid](https://www.fluentui-blazor.net/Components/Grid) |
| **Splitter** | ✅ Available | [FluentSplitter](https://www.fluentui-blazor.net/Components/Splitter) |
| **Spacer** | ✅ Available | [FluentSpacer](https://www.fluentui-blazor.net/Components/Spacer) |

### Navigation Components

| Component | Documentation | Official URL |
|-----------|---------------|--------------|
| **NavMenu** | ✅ Available | [FluentNavMenu](https://www.fluentui-blazor.net/Components/NavMenu) |
| **Breadcrumb** | ✅ Available | [FluentBreadcrumb](https://www.fluentui-blazor.net/Components/Breadcrumb) |
| **Pagination** | ✅ Available | [FluentPagination](https://www.fluentui-blazor.net/Components/Pagination) |

## 📖 What's Included

Each component documentation includes:

- **Overview** - Component description and purpose
- **API Documentation** - Complete parameter and method references
- **Code Examples** - Real-world usage examples with proper Razor syntax
- **Best Practices** - Implementation guidelines and recommendations
- **Event Handling** - Event callbacks and their usage
- **Styling Options** - Theming and customization information
- **Accessibility Notes** - A11y considerations and implementations

## 🏗️ Repository Structure
```
FluentUiBlazorDocs-main/
│
├── README.md
│
├── 1. Getting Started/
│   ├── 1.1 Code Setup.md
│   ├── 1.2 Project templates.md
│   ├── 1.3 Themes.md
│   ├── 1.4 Design Tokens.md
│   ├── 1.5 Reboot CSS.md
│   ├── 1.6 Using Icons and Emoji.md
│   └── 1.7 Blazor Hybrid.md
│
├── 2. Layout/
│   ├── 2.1 Header.md
│   ├── 2.2 Footer.md
│   ├── 2.3 Body Content.md
│   ├── 2.4 Grid.md
│   ├── 2.5 Layout.md
│   ├── 2.5 Main Layout.md
│   ├── 2.6 Spacer.md
│   ├── 2.7 Splitter.md
│   ├── 2.8 Splitter Multi.md
│   └── 2.9 Stack.md
│
├── 3. Forms And Inputs/
│   ├── 3.1 Overview.md
│   ├── 3.2 Checkbox.md
│   ├── 3.3 Date and Time.md
│   ├── 3.4 Input File.md
│   ├── 3.5 Lists/
│   │   ├── 3.5.1 Autocomplete.md
│   │   ├── 3.5.2 Combobox.md
│   │   ├── 3.5.3 Listbox.md
│   │   ├── 3.5.4 Select.md
│   │   └── 3.5.5 Option.md
│   ├── 3.6 Number Field.md
│   ├── 3.7 Radio.md
│   ├── 3.8 Radio Group.md
│   ├── 3.9 Rating.md
│   ├── 3.10 Search.md
│   ├── 3.11 Slider.md
│   ├── 3.12 Switch.md
│   ├── 3.13 TextArea.md
│   ├── 3.14 Text Field.md
│   └── 3.15 Time Picker.md
│
└── 4. Components/
    ├── 4.1 Overview.md
    ├── 4.2 Accordion.md
    ├── 4.3 Anchor.md
    ├── 4.4 Anchored Region.md
    ├── 4.5 AppBar.md
    ├── 4.6 Badge/
    │   ├── 4.6.1 Badge.md
    │   ├── 4.6.2 CounterBadge.md
    │   └── 4.6.3 PresenceBadge.md
    ├── 4.7 Breadcrumb.md
    ├── 4.8 Button/
    │   ├── 4.8.1 Button.md
    │   └── 4.8.2 MenuButton.md
    ├── 4.9 Card.md
    ├── 4.10 Data grid/
    │   ├── 4.10.1 Overview.md
    │   ├── 4.10.2 Getting Started.md
    │   ├── 4.10.3 Typical grid usage.md
    │   ├── 4.10.4 ...Content Parameters.md
    │   ├── 4.10.5 Auto fit.md
    │   ├── 4.10.6 Auto items per page.md
    │   ├── 4.10.7 Custom Paging.md
    │   ├── 4.10.8 Multi line text in cells.md
    │   ├── 4.10.9 Table with scrollbars.md
    │   ├── 4.10.10 Custom comparer sort.md
    │   ├── 4.10.11 Custom GridSort.md
    │   ├── 4.10.12 Single Multi Select.md
    │   ├── 4.10.13 Dynamic Columns.md
    │   ├── 4.10.14 Header generation.md
    │   ├── 4.10.15 Template Columns.md
    │   ├── 4.10.16 More Template Columns.md
    │   ├── 4.10.17 Virtualized Grid.md
    │   ├── 4.10.18 Remote Data.md
    │   └── 4.10.19 Manual Grid.md
    ├── 4.11 Dialog.md
    ├── 4.12 Divider.md
    ├── 4.13 Drag and Drop.md
    ├── 4.14 Emoji.md
    ├── 4.15 Flipper.md
    ├── 4.16 Highlighter.md
    ├── 4.17 Horizontal Scroll.md
    ├── 4.18 Icon.md
    ├── 4.19 KeyCode.md
    ├── 4.20 Label.md
    ├── 4.21 Menu.md
    ├── 4.22 MessageBar.md
    ├── 4.23 MessageBox.md
    ├── 4.24 NavMenu.md
    ├── 4.25 NavMenuTree.md
    ├── 4.26 Overflow.md
    ├── 4.27 Overlay.md
    ├── 4.27 Panel.md
    ├── 4.28 Persona.md
    ├── 4.29 Popover.md
    ├── 4.30 ProfileMenu.md
    ├── 4.31 Progress.md
    ├── 4.32 Progress Ring.md
    ├── 4.33 Pull to refresh.md
    ├── 4.34 Skeleton.md
    ├── 4.35 Sortable List.md
    ├── 4.36 SplashScreen.md
    ├── 4.37 Tabs.md
    ├── 4.38 Toast.md
    ├── 4.39 Toolbar.md
    ├── 4.40 ToolTip.md
    ├── 4.40 Tree View.md
    └── 4.41 Wizard.md
```

## 🔧 Local Development

### Prerequisites
- Basic understanding of Blazor and C#
- Familiarity with Fluent UI design principles

### Usage
1. Browse the documentation files in the `docs/` directory
2. Each component has its own markdown file with comprehensive documentation
3. Use the GitMCP integration for AI-assisted development

## 🤖 AI Assistant Capabilities

Once integrated with GitMCP, your AI assistant can help you with:

- **Component Selection** - Recommend the right Fluent UI Blazor component for your needs
- **Code Generation** - Generate complete, working component implementations
- **Best Practices** - Provide guidance on proper usage patterns
- **Troubleshooting** - Help debug component-related issues
- **Performance Optimization** - Suggest performance improvements
- **Accessibility** - Ensure proper a11y implementation

## 📊 Version Information

- **Source Version**: Fluent UI Blazor 4.12.1+dc098671
- **Documentation Extracted**: From official [fluentui-blazor.net](https://www.fluentui-blazor.net/)
- **Last Updated**: January 2025
- **Framework**: .NET 9.0.6

## 🌟 Key Features

- ✅ **Complete API Coverage** - All parameters, methods, and events documented
- ✅ **Real Code Examples** - Working Razor component examples
- ✅ **Best Practices** - Performance and accessibility guidelines
- ✅ **GitMCP Ready** - Optimized for AI assistant integration
- ✅ **Up-to-Date** - Based on latest stable release
- ✅ **Searchable** - Well-structured for easy navigation
- ✅ **Copy-Paste Ready** - Examples you can use immediately

## 🤝 Contributing

This repository is primarily for documentation distribution. For component issues or feature requests, please visit the official [Microsoft Fluent UI Blazor repository](https://github.com/microsoft/fluentui-blazor).

### Documentation Updates
If you notice outdated information or want to contribute improvements:

1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 License

This documentation is provided under the MIT License. See [LICENSE](LICENSE) for details.

The original Fluent UI Blazor components are licensed under the MIT License by Microsoft Corporation.

## 🔗 Related Links

- **Official Site**: [fluentui-blazor.net](https://www.fluentui-blazor.net/)
- **GitHub Repository**: [microsoft/fluentui-blazor](https://github.com/microsoft/fluentui-blazor)
- **NuGet Package**: [Microsoft.FluentUI.AspNetCore.Components](https://www.nuget.org/packages/Microsoft.FluentUI.AspNetCore.Components)
- **GitMCP**: [gitmcp.io](https://gitmcp.io/)
- **GitMCP Documentation**: [Chat with this repository's docs](https://gitmcp.io/ibrahimhuycn/FluentUiBlazorDocs)

## 💡 Getting Started Example

```razor
@page "/example"
@inject IToastService ToastService

<FluentStack Orientation="Orientation.Vertical" VerticalGap="10">
    <FluentButton Appearance="Appearance.Accent" 
                  OnClick="@ShowToast">
        Show Toast
    </FluentButton>
    
    <FluentDataGrid Items="@items">
        <PropertyColumn Property="@(p => p.Name)" />
        <PropertyColumn Property="@(p => p.Value)" />
    </FluentDataGrid>
</FluentStack>

@code {
    private List<MyItem> items = new();

    private void ShowToast()
    {
        ToastService.ShowSuccess("Hello from Fluent UI Blazor!");
    }
}
```

---

**Happy coding with Fluent UI Blazor! 🚀**

For questions or support, please refer to the [official documentation](https://www.fluentui-blazor.net/) or open an issue in this repository.
