# skills

The CLI for the open agent skills ecosystem.
# Convex Documentation

> For general information about Convex, read [https://www.convex.dev/llms.txt](https://www.convex.dev/llms.txt).


## understanding

- [Best Practices](/understanding/best-practices.md): Essential best practices for building scalable Convex applications including database queries, function organization, validation, and security.
- [TypeScript](/understanding/best-practices/typescript.md): Move faster with end-to-end type safety
- [Convex Overview](/understanding/overview.md): Introduction to Convex - the reactive database with TypeScript queries
- [Dev workflow](/understanding/workflow.md): Development workflow from project creation to production deployment
- [The Zen of Convex](/understanding/zen.md): Convex best practices and design philosophy

## quickstart

- [Android Kotlin Quickstart](/quickstart/android.md): Add Convex to an Android Kotlin project
- [Using Convex with Bun](/quickstart/bun.md): Add Convex to a Bun project
- [Next.js Quickstart](/quickstart/nextjs.md): Add Convex to a Next.js project
- [Node.js Quickstart](/quickstart/nodejs.md): Add Convex to a Node.js project
- [Nuxt Quickstart](/quickstart/nuxt.md): Add Convex to a Nuxt project
- [Quickstarts](/quickstart/overview.md): Get started quickly with your favorite frontend framework or language
- [Python Quickstart](/quickstart/python.md): Add Convex to a Python project
- [React Quickstart](/quickstart/react.md): Add Convex to a React project
- [React Native Quickstart](/quickstart/react-native.md): Add Convex to a React Native Expo project
- [Remix Quickstart](/quickstart/remix.md): Add Convex to a Remix project
- [Rust Quickstart](/quickstart/rust.md): Add Convex to a Rust project
- [Script Tag Quickstart](/quickstart/script-tag.md): Add Convex to any website
- [Svelte Quickstart](/quickstart/svelte.md): Add Convex to a Svelte project
- [iOS Swift Quickstart](/quickstart/swift.md): Add Convex to an iOS Swift project
- [TanStack Start Quickstart](/quickstart/tanstack-start.md): Add Convex to a TanStack Start project
- [Vue Quickstart](/quickstart/vue.md): Add Convex to a Vue project

## functions

- [Actions](/functions/actions.md): Call third-party services and external APIs from Convex
- [Bundling](/functions/bundling.md): How Convex bundles and optimizes your function code
- [Debugging](/functions/debugging.md): Debug Convex functions during development and production
- [Error Handling](/functions/error-handling.md): Handle errors in Convex queries, mutations, and actions
- [Application Errors](/functions/error-handling/application-errors.md): Handle expected failures in Convex functions
- [HTTP Actions](/functions/http-actions.md): Build HTTP APIs directly in Convex
- [Internal Functions](/functions/internal-functions.md): Functions that can only be called by other Convex functions
- [Mutations](/functions/mutation-functions.md): Insert, update, and remove data from the database
- [Functions](/functions/overview.md): Write functions to define your server behavior
- [Queries](/functions/query-functions.md): Fetch data from the database with caching and reactivity
- [Runtimes](/functions/runtimes.md): Learn the differences between the Convex and Node.js runtimes for functions
- [Argument and Return Value Validation](/functions/validation.md): Validate function arguments and return values for security

## database

- [OCC and Atomicity](/database/advanced/occ.md): Optimistic concurrency control and transaction atomicity in Convex
- [Schema Philosophy](/database/advanced/schema-philosophy.md): Convex schema design philosophy and best practices
- [System Tables](/database/advanced/system-tables.md): Access metadata for Convex built-in features through system tables including scheduled functions and file storage information.
- [Backups](/database/backup-restore.md): Backup and restore your Convex data and files
- [Document IDs](/database/document-ids.md): Create complex, relational data models using IDs
- [Data Import & Export](/database/import-export.md): Import data from existing sources and export data to external systems
- [Data Export](/database/import-export/export.md): Export your data out of Convex
- [Data Import](/database/import-export/import.md): Import data into Convex
- [Database](/database/overview.md): Store JSON-like documents with a relational data model
- [Paginated Queries](/database/pagination.md): Load paginated queries
- [Reading Data](/database/reading-data.md): Query and read data from Convex database tables
- [Filtering](/database/reading-data/filters.md): Filter documents in Convex queries
- [Indexes](/database/reading-data/indexes.md): Speed up queries with database indexes
- [Introduction to Indexes and Query Performance](/database/reading-data/indexes/indexes-and-query-perf.md): Learn the effects of indexes on query performance
- [Schemas](/database/schemas.md): Schema validation keeps your Convex data neat and tidy. It also gives you end-to-end TypeScript type safety!
- [Data Types](/database/types.md): Supported data types in Convex documents
- [Writing Data](/database/writing-data.md): Insert, update, and delete data in Convex database tables

## realtime

- [Realtime](/realtime.md): Building realtime apps with Convex

## auth

- [Custom OIDC Provider](/auth/advanced/custom-auth.md): Integrate Convex with any OpenID Connect identity provider using custom authentication configuration and ConvexProviderWithAuth.
- [Custom JWT Provider](/auth/advanced/custom-jwt.md): Configure Convex to work with custom JWT providers that don't implement full OIDC protocol, including setup and client-side integration.
- [Convex & Auth0](/auth/auth0.md): Integrate Auth0 authentication with Convex
- [Convex & WorkOS AuthKit](/auth/authkit.md): Integrate WorkOS AuthKit authentication with Convex
- [Adding WorkOS AuthKit to an Existing App](/auth/authkit/add-to-app.md): Adding WorkOS AuthKit to an existing Convex application
- [Automatic AuthKit Configuration](/auth/authkit/auto-provision.md): Configure WorkOS AuthKit integration with automatic provisioning for Convex deployments
- [AuthKit Troubleshooting](/auth/authkit/troubleshooting.md): Debugging issues with AuthKit authentication with Convex
- [Convex & Clerk](/auth/clerk.md): Integrate Clerk authentication with Convex
- [Convex Auth](/auth/convex-auth.md): Built-in authentication for Convex applications
- [Storing Users in the Convex Database](/auth/database-auth.md): Store user information in your Convex database
- [Debugging Authentication](/auth/debug.md): Troubleshoot authentication issues in Convex
- [Auth in Functions](/auth/functions-auth.md): Access user authentication in Convex functions
- [Authentication](/auth/overview.md): Add authentication to your Convex app.

## scheduling

- [Cron Jobs](/scheduling/cron-jobs.md): Schedule recurring functions in Convex
- [Scheduling](/scheduling/overview.md): Schedule functions to run once or repeatedly with scheduled functions and cron jobs
- [Scheduled Functions](/scheduling/scheduled-functions.md): Schedule functions to run in the future

## file-storage

- [Deleting Files](/file-storage/delete-files.md): Delete files stored in Convex
- [Accessing File Metadata](/file-storage/file-metadata.md): Access file metadata stored in Convex
- [File Storage](/file-storage/overview.md): Store and serve files of any type
- [Serving Files](/file-storage/serve-files.md): Serve files stored in Convex to users
- [Storing Generated Files](/file-storage/store-files.md): Store files generated in Convex actions
- [Uploading and Storing Files](/file-storage/upload-files.md): Upload files to Convex storage

## search

- [AI & Search](/search/overview.md): Run search queries over your Convex documents
- [Full Text Search](/search/text-search.md): Run search queries over your Convex documents
- [Vector Search](/search/vector-search.md): Run vector search queries on embeddings

## components

- [Authoring Components](/components/authoring.md): Creating new components
- [Components](/components/overview.md): Self contained building blocks of your app
- [Understanding Components](/components/understanding.md): Understanding components
- [Using Components](/components/using.md): Using existing components

## ai

- [Convex Agent Skills](/ai/agent-skills.md): Install Convex Agent Skills to give your AI coding agent specialized Convex workflows
- [Convex MCP Server](/ai/convex-mcp-server.md): Convex MCP server
- [AI Code Generation](/ai/overview.md): How to use AI code generation effectively with Convex
- [Using Claude Code with Convex](/ai/using-claude-code.md): Tips and best practices for using Claude Code with Convex
- [Using Codex with Convex](/ai/using-codex.md): Tips and best practices for using OpenAI Codex with Convex
- [Using Conductor with Convex](/ai/using-conductor.md): Tips and best practices for using Conductor with Convex
- [Using Cursor with Convex](/ai/using-cursor.md): Tips and best practices for using Cursor with Convex
- [Using GitHub Copilot with Convex](/ai/using-github-copilot.md): Tips and best practices for using GitHub Copilot with Convex

## agents

- [Agent Definition and Usage](/agents/agent-usage.md): Configuring and using the Agent class
- [LLM Context](/agents/context.md): Customizing the context provided to the Agent's LLM
- [Debugging](/agents/debugging.md): Debugging the Agent component
- [Files and Images in Agent messages](/agents/files.md): Working with images and files in the Agent component
- [Getting Started with Agent](/agents/getting-started.md): Setting up the agent component
- [Human Agents](/agents/human-agents.md): Saving messages from a human as an agent
- [Messages](/agents/messages.md): Sending and receiving messages with an agent
- [AI Agents](/agents/overview.md): Building AI Agents with Convex
- [Playground](/agents/playground.md): A simple way to test, debug, and develop with the agent
- [RAG (Retrieval-Augmented Generation) with the Agent component](/agents/rag.md): Examples of how to use RAG with the Convex Agent component
- [Rate Limiting](/agents/rate-limiting.md): Control the rate of requests to your AI agent
- [Streaming](/agents/streaming.md): Streaming messages with an agent
- [Threads](/agents/threads.md): Group messages together in a conversation history
- [Tool Approval](/agents/tool-approval.md): Human-in-the-loop tool approval for the Agent component
- [Tools](/agents/tools.md): Using tool calls with the Agent component
- [Usage Tracking](/agents/usage-tracking.md): Tracking token usage of the Agent component
- [Workflows](/agents/workflows.md): Defining long-lived workflows for the Agent component

## testing

- [Continuous Integration](/testing/ci.md): Set up continuous integration testing for Convex applications
- [Testing Local Backend](/testing/convex-backend.md): Test functions using the local open-source Convex backend
- [convex-test](/testing/convex-test.md): Mock Convex backend for fast automated testing of functions
- [Testing](/testing/overview.md): Testing your backend

## production

- [Abuse Protection](/production/abuse-protection.md): What Convex deployments are protected from by default, including DDoS attacks, and how to add your own Cloudflare or Vercel edge for more control
- [Contact Us](/production/contact.md): Get support, provide feedback, stay updated with Convex releases, and report security vulnerabilities through our community channels.
- [Custom Domains](/production/custom-domains.md): Set up a custom domain for your Convex cloud deployment
- [Environment Variables](/production/environment-variables.md): Declare, store, and access environment variables in Convex
- [Deploy Your Frontend](/production/hosting.md): Deploy your Convex backend alongside your frontend hosting
- [Custom Hosting](/production/hosting/custom.md): Host your frontend on any static hosting provider, such as GitHub Pages.
- [Using Convex with Netlify](/production/hosting/netlify.md): Host your frontend on Netlify and your backend on Convex
- [Using Convex with Vercel](/production/hosting/vercel.md): Host your frontend on Vercel and your backend on Convex
- [Integrations](/production/integrations.md): Integrate Convex with third party services
- [Audit Logging](/production/integrations/audit-logging.md): Add transactional audit logging to your Convex functions
- [Exception Reporting](/production/integrations/exception-reporting.md): Configure exception reporting integrations for your Convex deployment
- [Log Streams](/production/integrations/log-streams.md): Configure logging integrations for your Convex deployment
- [(Legacy) Event schema](/production/integrations/log-streams/legacy-event-schema.md): Log streams configured before May 23, 2024 will use the legacy format
- [Streaming Data in and out of Convex](/production/integrations/streaming-import-export.md): Streaming Data in and out of Convex
- [Working with Multiple Deployments](/production/multiple-deployments.md): Creating multiple deployments in a single project
- [Multiple Repositories](/production/multiple-repos.md): Use Convex in multiple repositories
- [Networking](/production/networking.md): IP addresses used by Convex for outbound requests
- [Deploying Your App to Production](/production/overview.md): Tips for building safe and reliable production apps
- [Pausing a Deployment](/production/pause-deployment.md): Temporarily disable a deployment without deleting data
- [Project Configuration](/production/project-configuration.md): Configure your Convex project for development and production deployment using convex.json, environment variables, and deployment settings.
- [Regions](/production/regions.md): Learn how to select a region for your Convex deployments
- [Status and Guarantees](/production/state.md): Learn about Convex's production guarantees, availability targets, data durability, security features, and upcoming platform enhancements.
- [Limits](/production/state/limits.md): We’d love for you to have unlimited joy building on Convex but engineering

## self-hosting

- [Self Hosting](/self-hosting.md): Self Hosting Convex Projects

## cli

- [Agent Mode](/cli/agent-mode.md): Configure agentic development for cloud-based and local deployments
- [Deploy Keys](/cli/deploy-key-types.md): Use deploy keys for authentication in production build environments
- [Local Deployments for Development](/cli/local-deployments.md): Develop with Convex using deployments running locally on your machine
- [CLI](/cli/overview.md): Command-line interface for managing Convex projects and functions
- [npx convex ai-files](/cli/reference/ai-files.md): Manage Convex AI files
- [npx convex codegen](/cli/reference/codegen.md): Generate backend type definitions
- [npx convex dashboard](/cli/reference/dashboard.md): Open the dashboard in the browser
- [npx convex data](/cli/reference/data.md): List tables and print data from your database
- [npx convex deploy](/cli/reference/deploy.md): Deploy to a production or preview deployment
- [npx convex deployment](/cli/reference/deployment.md): Manage deployments
- [npx convex dev](/cli/reference/dev.md): Develop against a dev deployment, watching for changes
- [npx convex docs](/cli/reference/docs.md): Open the docs in the browser
- [npx convex env](/cli/reference/env.md): Set and view environment variables
- [npx convex export](/cli/reference/export.md): Export data from your deployment to a ZIP file
- [npx convex function-spec](/cli/reference/function-spec.md): List function metadata from your deployment
- [npx convex import](/cli/reference/import.md): Import data from a file to your deployment
- [npx convex insights](/cli/reference/insights.md): Show health insights for your deployment
- [npx convex logout](/cli/reference/logout.md): Log out of Convex on this machine
- [npx convex logs](/cli/reference/logs.md): Watch logs from your deployment
- [npx convex mcp](/cli/reference/mcp.md): Manage the Model Context Protocol server for Convex [BETA]
- [npx convex run](/cli/reference/run.md): Run a function or evaluate an inline readonly query on your deployment
- [npx convex update](/cli/reference/update.md): Print instructions for updating the convex package
- [Typecheck Performance](/cli/troubleshooting/typecheck-performance.md): Debug slow typechecking performance when pushing code

## client

- [Kotlin and Convex type conversion](/client/android/data-types.md): Customizing and converting types between the Kotlin app and Convex
- [Android Kotlin](/client/android/overview.md): Android Kotlin client library for mobile applications using Convex
- [Bun](/client/javascript/bun.md): Use Convex clients with the Bun JavaScript runtime
- [Node.js](/client/javascript/node.md): Use Convex HTTP and subscription clients in Node.js applications
- [Convex JavaScript Clients](/client/javascript/overview.md): JavaScript clients for Node.js and browser applications using Convex
- [Script Tag](/client/javascript/script-tag.md): Use Convex directly in HTML with script tags, no build tools required
- [Next.js](/client/nextjs/app-router.md): How Convex works in a Next.js app
- [Next.js Server Rendering](/client/nextjs/app-router/server-rendering.md): Implement server-side rendering with Convex in Next.js App Router using preloadQuery, fetchQuery, and server actions for improved performance.
- [Next.js Pages Router](/client/nextjs/pages-router.md): Complete guide to using Convex with Next.js Pages Router including client-side authentication, API routes, and server-side rendering.
- [Next.js Pages Quickstart](/client/nextjs/pages-router/quickstart.md): Get started with Convex in Next.js Pages Router by building a reactive task list app with queries, mutations, and real-time updates.
- [OpenAPI & Other Languages](/client/open-api.md): While Convex doesn't have first-party clients for languages such as Go, Java, or
- [Python](/client/python.md): Python client library for building applications with Convex
- [Convex React Native](/client/react-native.md): How Convex works in a React Native app
- [Configuring Deployment URL](/client/react/deployment-urls.md): Configuring your project to run with Convex
- [Optimistic Updates](/client/react/optimistic-updates.md): Make your React app more responsive with optimistic UI updates
- [Convex React](/client/react/overview.md): React client library for interacting with your Convex backend
- [Rust](/client/rust.md): Rust client library for building applications with Convex
- [Svelte](/client/svelte.md): Reactive Svelte client library for Convex applications
- [Swift and Convex type conversion](/client/swift/data-types.md): Customizing and converting types between the Swift app and Convex
- [iOS & macOS Swift](/client/swift/overview.md): Swift client library for iOS and macOS applications using Convex
- [Convex with TanStack Query](/client/tanstack/tanstack-query.md): Integrate Convex with TanStack Query for advanced data fetching patterns
- [TanStack Start](/client/tanstack/tanstack-start.md): How Convex works with TanStack Start
- [TanStack Start with Clerk](/client/tanstack/tanstack-start/clerk.md): Learn how to integrate Clerk authentication with Convex in TanStack Start applications using ID tokens and ConvexProviderWithClerk.
- [Nuxt](/client/vue/nuxt.md): Nuxt is a powerful web framework powered by Vue.
- [Vue](/client/vue/overview.md): Community-maintained Vue integration for Convex applications

## dashboard

- [Deployments](/dashboard/deployments.md): Understand Convex deployments including production, development, and preview deployments, and how to switch between them in the dashboard.
- [Data](/dashboard/deployments/data.md): View, edit, and manage database tables and documents in the dashboard
- [Settings](/dashboard/deployments/deployment-settings.md): Configure your Convex deployment settings including URLs, environment variables, authentication, backups, integrations, and deployment management.
- [File Storage](/dashboard/deployments/file-storage.md): Upload, download{
  "aiFiles": {
    "enabled": false,
    "skills": {
      "agents": ["claude-code", "codex", "cursor"]
    }
  }
}npx skills updatehttps://github.com/vercel-labs/skills
<!-- agent-list:start -->
Supports **OpenCode**, **Claude Code**, **Codex**, **Cursor**, and [67 more](#supported-agents).
<!-- agent-list:end -->

[![skills.sh](https://skills.sh/b/vercel-labs/skills)](https://skills.sh/vercel-labs/skills)

## Install a Skill

```bash
npx skills add https://github.com/vercel-labs/skills --skill find-skills
```

## Use a Skill Without Installing

Generate a prompt for one skill, or start a supported coding agent interactively:

```bash
npx skills use vercel-labs/agent-skills@web-design-guidelines | claude
npx skills use vercel-labs/agent-skills --skill web-design-guidelines --agent claude-code
```

`skills use` resolves sources the same way as `skills add`, writes the selected skill files to a temporary directory, and prints only the generated prompt to stdout unless `--agent` is provided. With `--agent`, it starts one supported agent interactively with the generated prompt.

### Source Formats

```bash
# GitHub shorthand (owner/repo)
npx skills add vercel-labs/agent-skills

# Full GitHub URL
npx skills add https://github.com/vercel-labs/agent-skills

# Direct path to a skill in a repo
npx skills add https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines

# GitLab URL
npx skills add https://gitlab.com/org/repo

# Any git URL
npx skills add git@github.com:vercel-labs/agent-skills.git

# Local path
npx skills add ./my-local-skills
```

### Options

| Option                    | Description                                                                                                                                        |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| `-g, --global`            | Install to user directory instead of project                                                                                                       |
| `-a, --agent <agents...>` | <!-- agent-names:start -->Target specific agents (e.g., `claude-code`, `codex`). See [Supported Agents](#supported-agents)<!-- agent-names:end --> |
| `-s, --skill <skills...>` | Install specific skills by name (use `'*'` for all skills)                                                                                         |
| `-l, --list`              | List available skills without installing                                                                                                           |
| `--copy`                  | Copy files instead of symlinking to agent directories                                                                                              |
| `-y, --yes`               | Skip all confirmation prompts                                                                                                                      |
| `--all`                   | Install all skills to all agents without prompts                                                                                                   |

### Examples

```bash
# List skills in a repository
npx skills add vercel-labs/agent-skills --list

# Install specific skills
npx skills add vercel-labs/agent-skills --skill frontend-design --skill skill-creator

# Install a skill with spaces in the name (must be quoted)
npx skills add owner/repo --skill "Convex Best Practices"

# Install to specific agents
npx skills add vercel-labs/agent-skills -a claude-code -a opencode

# Non-interactive installation (CI/CD friendly)
npx skills add vercel-labs/agent-skills --skill frontend-design -g -a claude-code -y

# Install all skills from a repo to all agents
npx skills add vercel-labs/agent-skills --all

# Install all skills to specific agents
npx skills add vercel-labs/agent-skills --skill '*' -a claude-code

# Install specific skills to all agents
npx skills add vercel-labs/agent-skills --agent '*' --skill frontend-design
```

### Installation Scope

| Scope       | Flag      | Location            | Use Case                                      |
| ----------- | --------- | ------------------- | --------------------------------------------- |
| **Project** | (default) | `./<agent>/skills/` | Committed with your project, shared with team |
| **Global**  | `-g`      | `~/<agent>/skills/` | Available across all projects                 |

### Installation Methods

When installing interactively, you can choose:

| Method                    | Description                                                                                 |
| ------------------------- | ------------------------------------------------------------------------------------------- |
| **Symlink** (Recommended) | Creates symlinks from each agent to a canonical copy. Single source of truth, easy updates. |
| **Copy**                  | Creates independent copies for each agent. Use when symlinks aren't supported.              |

## Other Commands

| Command                      | Description                                   |
| ---------------------------- | --------------------------------------------- |
| `npx skills use <source>`    | Use one skill without installing              |
| `npx skills list`            | List installed skills (alias: `ls`)           |
| `npx skills find [query]`    | Search for skills interactively or by keyword |
| `npx skills remove [skills]` | Remove installed skills from agents           |
| `npx skills update [skills]` | Update installed skills to latest versions    |
| `npx skills init [name]`     | Create a new SKILL.md template                |

### `skills list`

List all installed skills. Similar to `npm ls`.

```bash
# List all installed skills (project and global)
npx skills list

# List only global skills
npx skills ls -g

# Filter by specific agents
npx skills ls -a claude-code -a cursor
```

### `skills find`

Search for skills interactively or by keyword.

```bash
# Interactive search (fzf-style)
npx skills find

# Search by keyword
npx skills find typescript
```

### `skills update`

```bash
# Update all skills (interactive scope prompt)
npx skills update

# Update a single skill by name
npx skills update my-skill

# Update multiple specific skills
npx skills update frontend-design web-design-guidelines

# Update only global or project skills
npx skills update -g
npx skills update -p

# Non-interactive (auto-detects scope: project if in a project, else global)
npx skills update -y
```

| Option          | Description                                                               |
| --------------- | ------------------------------------------------------------------------- |
| `-g, --global`  | Only update global skills                                                 |
| `-p, --project` | Only update project skills                                                |
| `-y, --yes`     | Skip scope prompt (auto-detect: project if in a project dir, else global) |
| `[skills...]`   | Update specific skills by name instead of all                             |

### `skills init`

```bash
# Create SKILL.md in current directory
npx skills init

# Create a new skill in a subdirectory
npx skills init my-skill
```

### `skills remove`

Remove installed skills from agents.

```bash
# Remove interactively (select from installed skills)
npx skills remove

# Remove specific skill by name
npx skills remove web-design-guidelines

# Remove multiple skills
npx skills remove frontend-design web-design-guidelines

# Remove from global scope
npx skills remove --global web-design-guidelines

# Remove from specific agents only
npx skills remove --agent claude-code cursor my-skill

# Remove all installed skills without confirmation
npx skills remove --all

# Remove all skills from a specific agent
npx skills remove --skill '*' -a cursor

# Remove a specific skill from all agents
npx skills remove my-skill --agent '*'

# Use 'rm' alias
npx skills rm my-skill
```

| Option         | Description                                      |
| -------------- | ------------------------------------------------ |
| `-g, --global` | Remove from global scope (~/) instead of project |
| `-a, --agent`  | Remove from specific agents (use `'*'` for all)  |
| `-s, --skill`  | Specify skills to remove (use `'*'` for all)     |
| `-y, --yes`    | Skip confirmation prompts                        |
| `--all`        | Shorthand for `--skill '*' --agent '*' -y`       |

## What are Agent Skills?

Agent skills are reusable instruction sets that extend your coding agent's capabilities. They're defined in `SKILL.md`
files with YAML frontmatter containing a `name` and `description`.

Skills let agents perform specialized tasks like:

- Generating release notes from git history
- Creating PRs following your team's conventions
- Integrating with external tools (Linear, Notion, etc.)

Discover skills at **[skills.sh](https://skills.sh)**

## Supported Agents

Skills can be installed to any of these agents:

<!-- supported-agents:start -->
| Agent | `--agent` | Project Path | Global Path |
|-------|-----------|--------------|-------------|
| AiderDesk | `aider-desk` | `.aider-desk/skills/` | `~/.aider-desk/skills/` |
| Amp, Replit, Universal | `amp`, `replit`, `universal` | `.agents/skills/` | `~/.config/agents/skills/` |
| Antigravity | `antigravity` | `.agents/skills/` | `~/.gemini/antigravity/skills/` |
| Antigravity CLI | `antigravity-cli` | `.agents/skills/` | `~/.gemini/antigravity-cli/skills/` |
| AstrBot | `astrbot` | `data/skills/` | `~/.astrbot/data/skills/` |
| Autohand Code CLI | `autohand-code` | `.autohand/skills/` | `~/.autohand/skills/` |
| Augment | `augment` | `.augment/skills/` | `~/.augment/skills/` |
| IBM Bob | `bob` | `.bob/skills/` | `~/.bob/skills/` |
| Claude Code | `claude-code` | `.claude/skills/` | `~/.claude/skills/` |
| OpenClaw | `openclaw` | `skills/` | `~/.openclaw/skills/` |
| Cline, Dexto, Kimi Code CLI, Loaf, Warp, Zed | `cline`, `dexto`, `kimi-code-cli`, `loaf`, `warp`, `zed` | `.agents/skills/` | `~/.agents/skills/` |
| CodeArts Agent | `codearts-agent` | `.codeartsdoer/skills/` | `~/.codeartsdoer/skills/` |
| CodeBuddy | `codebuddy` | `.codebuddy/skills/` | `~/.codebuddy/skills/` |
| Codemaker | `codemaker` | `.codemaker/skills/` | `~/.codemaker/skills/` |
| Code Studio | `codestudio` | `.codestudio/skills/` | `~/.codestudio/skills/` |
| Codex | `codex` | `.agents/skills/` | `~/.codex/skills/` |
| Command Code | `command-code` | `.commandcode/skills/` | `~/.commandcode/skills/` |
| Continue | `continue` | `.continue/skills/` | `~/.continue/skills/` |
| Cortex Code | `cortex` | `.cortex/skills/` | `~/.snowflake/cortex/skills/` |
| Crush | `crush` | `.crush/skills/` | `~/.config/crush/skills/` |
| Cursor | `cursor` | `.agents/skills/` | `~/.cursor/skills/` |
| Deep Agents | `deepagents` | `.agents/skills/` | `~/.deepagents/agent/skills/` |
| Devin for Terminal | `devin` | `.devin/skills/` | `~/.config/devin/skills/` |
| Droid | `droid` | `.factory/skills/` | `~/.factory/skills/` |
| Firebender | `firebender` | `.agents/skills/` | `~/.firebender/skills/` |
| ForgeCode | `forgecode` | `.forge/skills/` | `~/.forge/skills/` |
| Gemini CLI | `gemini-cli` | `.agents/skills/` | `~/.gemini/skills/` |
| GitHub Copilot | `github-copilot` | `.agents/skills/` | `~/.copilot/skills/` |
| Goose | `goose` | `.goose/skills/` | `~/.config/goose/skills/` |
| Hermes Agent | `hermes-agent` | `.hermes/skills/` | `~/.hermes/skills/` |
| inference.sh | `inference-sh` | `.inferencesh/skills/` | `~/.inferencesh/skills/` |
| Jazz | `jazz` | `.jazz/skills/` | `~/.jazz/skills/` |
| Junie | `junie` | `.junie/skills/` | `~/.junie/skills/` |
| iFlow CLI | `iflow-cli` | `.iflow/skills/` | `~/.iflow/skills/` |
| Kilo Code | `kilo` | `.kilocode/skills/` | `~/.kilocode/skills/` |
| Kiro CLI | `kiro-cli` | `.kiro/skills/` | `~/.kiro/skills/` |
| Kode | `kode` | `.kode/skills/` | `~/.kode/skills/` |
| Lingma | `lingma` | `.lingma/skills/` | `~/.lingma/skills/` |
| MCPJam | `mcpjam` | `.mcpjam/skills/` | `~/.mcpjam/skills/` |
| Mistral Vibe | `mistral-vibe` | `.vibe/skills/` | `~/.vibe/skills/` |
| Moxby | `moxby` | `.moxby/skills/` | `~/.moxby/skills/` |
| Mux | `mux` | `.mux/skills/` | `~/.mux/skills/` |
| OpenCode | `opencode` | `.agents/skills/` | `~/.config/opencode/skills/` |
| OpenHands | `openhands` | `.openhands/skills/` | `~/.openhands/skills/` |
| Ona | `ona` | `.ona/skills/` | `~/.ona/skills/` |
| Pi | `pi` | `.pi/skills/` | `~/.pi/agent/skills/` |
| Qoder | `qoder` | `.qoder/skills/` | `~/.qoder/skills/` |
| Qoder CN | `qoder-cn` | `.qoder/skills/` | `~/.qoder-cn/skills/` |
| Qwen Code | `qwen-code` | `.qwen/skills/` | `~/.qwen/skills/` |
| Reasonix | `reasonix` | `.reasonix/skills/` | `~/.reasonix/skills/` |
| Rovo Dev | `rovodev` | `.rovodev/skills/` | `~/.rovodev/skills/` |
| Roo Code | `roo` | `.roo/skills/` | `~/.roo/skills/` |
| Tabnine CLI | `tabnine-cli` | `.tabnine/agent/skills/` | `~/.tabnine/agent/skills/` |
| Terramind | `terramind` | `.terramind/skills/` | `~/.terramind/skills/` |
| Tinycloud | `tinycloud` | `.tinycloud/skills/` | `~/.tinycloud/skills/` |
| Trae | `trae` | `.trae/skills/` | `~/.trae/skills/` |
| Trae CN | `trae-cn` | `.trae/skills/` | `~/.trae-cn/skills/` |
| Windsurf | `windsurf` | `.windsurf/skills/` | `~/.codeium/windsurf/skills/` |
| Zencoder, Zenflow | `zencoder`, `zenflow` | `.zencoder/skills/` | `~/.zencoder/skills/` |
| Neovate | `neovate` | `.neovate/skills/` | `~/.neovate/skills/` |
| Pochi | `pochi` | `.pochi/skills/` | `~/.pochi/skills/` |
| PromptScript | `promptscript` | `.agents/skills/` | N/A (project-only) |
| AdaL | `adal` | `.adal/skills/` | `~/.adal/skills/` |
<!-- supported-agents:end -->

> [!NOTE]
> **Kiro CLI users:** The default agent automatically loads skills from `.kiro/skills/` and `~/.kiro/skills/` — no
> configuration needed. If you use a **custom agent**, add skills to its `resources` in `.kiro/agents/<agent>.json`:
>
> ```json
> {
>   "resources": ["skill://.kiro/skills/**/SKILL.md"]
> }
> ```

The CLI automatically detects which coding agents you have installed. If none are detected, you'll be prompted to select
which agents to install to.

## Creating Skills

Skills are directories containing a `SKILL.md` file with YAML frontmatter:

```markdown
---
name: my-skill
description: What this skill does and when to use it
---

# My Skill

Instructions for the agent to follow when this skill is activated.

## When to Use

Describe the scenarios where this skill should be used.

## Steps

1. First, do this
2. Then, do that
```

### Required Fields

- `name`: Unique identifier (lowercase, hyphens allowed)
- `description`: Brief explanation of what the skill does

### Optional Fields

- `metadata.internal`: Set to `true` to hide the skill from normal discovery. Internal skills are only visible and
  installable when `INSTALL_INTERNAL_SKILLS=1` is set. Useful for work-in-progress skills or skills meant only for
  internal tooling.

```markdown
---
name: my-internal-skill
description: An internal skill not shown by default
metadata:
  internal: true
---
```

### Skill Discovery

The CLI searches for skills in these locations within a repository. Each
skill container directory is walked one level deep for the common flat
layout (`skills/<name>/SKILL.md`) and one extra level deep for catalog
layouts (`skills/<category>/<name>/SKILL.md`). A `SKILL.md` discovered at
the shallower level shadows anything nested below it. Use `--full-depth`
to also discover `SKILL.md` files outside these container directories
(e.g. under `examples/` or `tests/`).

<!-- skill-discovery:start -->
- Root directory (if it contains `SKILL.md`)
- `skills/`
- `skills/.curated/`
- `skills/.experimental/`
- `skills/.system/`
- `.aider-desk/skills/`
- `.agents/skills/`
- `data/skills/`
- `.autohand/skills/`
- `.augment/skills/`
- `.bob/skills/`
- `.claude/skills/`
- `.codeartsdoer/skills/`
- `.codebuddy/skills/`
- `.codemaker/skills/`
- `.codestudio/skills/`
- `.commandcode/skills/`
- `.continue/skills/`
- `.cortex/skills/`
- `.crush/skills/`
- `.devin/skills/`
- `.factory/skills/`
- `.forge/skills/`
- `.goose/skills/`
- `.hermes/skills/`
- `.inferencesh/skills/`
- `.jazz/skills/`
- `.junie/skills/`
- `.iflow/skills/`
- `.kilocode/skills/`
- `.kiro/skills/`
- `.kode/skills/`
- `.lingma/skills/`
- `.mcpjam/skills/`
- `.vibe/skills/`
- `.moxby/skills/`
- `.mux/skills/`
- `.openhands/skills/`
- `.ona/skills/`
- `.pi/skills/`
- `.qoder/skills/`
- `.qwen/skills/`
- `.reasonix/skills/`
- `.rovodev/skills/`
- `.roo/skills/`
- `.tabnine/agent/skills/`
- `.terramind/skills/`
- `.tinycloud/skills/`
- `.trae/skills/`
- `.windsurf/skills/`
- `.zencoder/skills/`
- `.neovate/skills/`
- `.pochi/skills/`
- `.adal/skills/`
<!-- skill-discovery:end -->

### Plugin Manifest Discovery

If `.claude-plugin/marketplace.json` or `.claude-plugin/plugin.json` exists, skills declared in those files are also discovered:

```json
// .claude-plugin/marketplace.json
{
  "metadata": { "pluginRoot": "./plugins" },
  "plugins": [
    {
      "name": "my-plugin",
      "source": "my-plugin",
      "skills": ["./skills/review", "./skills/test"]
    }
  ]
}
```

This enables compatibility with the [Claude Code plugin marketplace](https://code.claude.com/docs/en/plugin-marketplaces) ecosystem. Skill paths declared in a manifest are searched at their declared depth and are not subject to the depth-2 catalog walk described above.

If no skills are found in standard locations, a recursive search is performed.

## Compatibility

Skills are generally compatible across agents since they follow a
shared [Agent Skills specification](https://agentskills.io). However, some features may be agent-specific:

| Feature         | OpenCode | OpenHands | Claude Code | Cline | CodeBuddy | Codex | Command Code | Kiro CLI | Cursor | Antigravity | Roo Code | Github Copilot | Amp | OpenClaw | Neovate | Pi  | Qoder | Zencoder |
| --------------- | -------- | --------- | ----------- | ----- | --------- | ----- | ------------ | -------- | ------ | ----------- | -------- | -------------- | --- | -------- | ------- | --- | ----- | -------- |
| Basic skills    | Yes      | Yes       | Yes         | Yes   | Yes       | Yes   | Yes          | Yes      | Yes    | Yes         | Yes      | Yes            | Yes | Yes      | Yes     | Yes | Yes   | Yes      |
| `allowed-tools` | Yes      | Yes       | Yes         | Yes   | Yes       | Yes   | Yes          | No       | Yes    | Yes         | Yes      | Yes            | Yes | Yes      | Yes     | Yes | Yes   | No       |
| `context: fork` | No       | No        | Yes         | No    | No        | No    | No           | No       | No     | No          | No       | No             | No  | No       | No      | No  | No    | No       |
| Hooks           | No       | No        | Yes         | Yes   | No        | No    | No           | Yes      | No     | No          | No       | No             | No  | No       | No      | No  | No    | No       |

## Troubleshooting

### "No skills found"

Ensure the repository contains valid `SKILL.md` files with both `name` and `description` in the frontmatter.

### Skill not loading in agent

- Verify the skill was installed to the correct path
- Check the agent's documentation for skill loading requirements
- Ensure the `SKILL.md` frontmatter is valid YAML

### Permission errors

Ensure you have write access to the target directory.

## Environment Variables

| Variable                  | Description                                                                |
| ------------------------- | -------------------------------------------------------------------------- |
| `INSTALL_INTERNAL_SKILLS` | Set to `1` or `true` to show and install skills marked as `internal: true` |
| `DISABLE_TELEMETRY`       | Set to disable anonymous usage telemetry                                   |
| `DO_NOT_TRACK`            | Alternative way to disable telemetry                                       |

```bash
# Install internal skills
INSTALL_INTERNAL_SKILLS=1 npx skills add vercel-labs/agent-skills --list
```

## Telemetry

This CLI collects anonymous usage data to help improve the tool. No personal information is collected.

Telemetry is automatically disabled in CI environments.

## Related Links

- [Agent Skills Specification](https://agentskills.io)
- [Skills Directory](https://skills.sh)
- [Amp Skills Documentation](https://ampcode.com/manual#agent-skills)
- [Antigravity Skills Documentation](https://antigravity.google/docs/skills)
- [Factory AI / Droid Skills Documentation](https://docs.factory.ai/cli/configuration/skills)
- [Claude Code Skills Documentation](https://code.claude.com/docs/en/skills)
- [OpenClaw Skills Documentation](https://docs.openclaw.ai/tools/skills)
- [Cline Skills Documentation](https://docs.cline.bot/features/skills)
- [CodeBuddy Skills Documentation](https://www.codebuddy.ai/docs/ide/Features/Skills)
- [Codex Skills Documentation](https://developers.openai.com/codex/skills)
- [Command Code Skills Documentation](https://commandcode.ai/docs/skills)
- [Crush Skills Documentation](https://github.com/charmbracelet/crush?tab=readme-ov-file#agent-skills)
- [Cursor Skills Documentation](https://cursor.com/docs/context/skills)
- [Firebender Skills Documentation](https://docs.firebender.com/multi-agent/skills)
- [Gemini CLI Skills Documentation](https://geminicli.com/docs/cli/skills/)
- [GitHub Copilot Agent Skills](https://docs.github.com/en/copilot/concepts/agents/about-agent-skills)
- [iFlow CLI Skills Documentation](https://platform.iflow.cn/en/cli/examples/skill)
- [Kimi Code CLI Skills Documentation](https://moonshotai.github.io/kimi-code/en/customization/skills)
- [Kiro CLI Skills Documentation](https://kiro.dev/docs/cli/custom-agents/configuration-reference/#skill-resources)
- [Kode Skills Documentation](https://github.com/shareAI-lab/kode/blob/main/docs/skills.md)
- [OpenCode Skills Documentation](https://opencode.ai/docs/skills)
- [Qwen Code Skills Documentation](https://qwenlm.github.io/qwen-code-docs/en/users/features/skills/)
- [OpenHands Skills Documentation](https://docs.openhands.ai/modules/usage/how-to/using-skills)
- [Pi Skills Documentation](https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/docs/skills.md)
- [Qoder Skills Documentation](https://docs.qoder.com/cli/Skills)
- [Replit Skills Documentation](https://docs.replit.com/replitai/skills)
- [Roo Code Skills Documentation](https://docs.roocode.com/features/skills)
- [Trae Skills Documentation](https://docs.trae.ai/ide/skills)
- [Vercel Agent Skills Repository](https://github.com/vercel-labs/agent-skills)

## License

MIT
