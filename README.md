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
├── docs/
│   ├── components/
│   │   ├── fluent-toolbar.md
│   │   ├── fluent-tabs.md
│   │   ├── fluent-toast.md
│   │   ├── fluent-tooltip.md
│   │   ├── fluent-treeview.md
│   │   ├── fluent-wizard.md
│   │   └── ... (more components)
│   └── ...
├── README.md
└── LICENSE
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
