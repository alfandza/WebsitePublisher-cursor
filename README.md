# WebsitePublisher for Cursor

Manage your WebsitePublisher websites directly from [Cursor](https://cursor.com) using the Model Context Protocol (MCP).

WebsitePublisher gives Cursor access to tools for managing websites, pages, entities, forms, publishing, scheduling, and other WebsitePublisher operations.

## Features

- Manage WebsitePublisher websites
- Create, update, and inspect pages
- Manage entities and entity data
- Work with forms
- Publish and unpublish content
- Manage website publishing operations
- Schedule website operations
- Use WebsitePublisher through Cursor's AI tools
- Authenticate securely with OAuth

## Installation

Install **WebsitePublisher** from the Cursor Plugin Marketplace.

After installation, Cursor will connect to the WebsitePublisher MCP server.

If authentication is required, Cursor will open the WebsitePublisher sign-in and authorization flow.

Sign in to your WebsitePublisher account and authorize Cursor to access your WebsitePublisher account.

Once authentication is complete, the WebsitePublisher tools will be available in Cursor.

## Authentication

WebsitePublisher uses OAuth for authentication.

Your WebsitePublisher password and other credentials are not stored in the Cursor plugin.

When authentication is requested:

1. Sign in to your WebsitePublisher account.
2. Authorize Cursor to access WebsitePublisher.
3. Return to Cursor.
4. Continue using the WebsitePublisher tools.

## Usage

Once WebsitePublisher is connected, you can interact with your websites through Cursor using natural language.

For example:

```text
List my WebsitePublisher projects.
```

```text
Show me the pages in the <project-name> project.
```

```text
Create a test page called "<page-name>".
```

```text
List the entities available in this project.
```

```text
Show me the fields of the <entity-name> entity.
```

```text
Publish the <page-name> page.
```

Cursor will select the appropriate WebsitePublisher tools to perform the requested operation.

## Troubleshooting

### WebsitePublisher tools are not available

If the WebsitePublisher tools do not appear in Cursor:

1. Make sure the WebsitePublisher plugin is installed.
2. Make sure you have completed the WebsitePublisher authentication flow.
3. Check that the MCP connection is active.
4. Reconnect or refresh the MCP connection in Cursor.

### Authentication fails

If the OAuth authentication flow fails, complete the sign-in process again and make sure you authorize Cursor to access WebsitePublisher.

If the problem persists, contact WebsitePublisher support.

### Changes are not appearing

If a change made through Cursor is not visible on your website, verify the relevant WebsitePublisher publishing status and refresh the website.

## Links

- [WebsitePublisher](https://www.websitepublisher.ai)
- [WebsitePublisher MCP Documentation](https://www.websitepublisher.ai/docs/mcp)
- [Cursor](https://cursor.com)

## Support

Contact WebsitePublisher support through [Contact](https://www.websitepublisher.ai/contact) or email [support@websitepublisher.ai](mailto:support@websitepublisher.ai)