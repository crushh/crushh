# Zoe / crushh

Frontend / Full Stack Engineer focused on React, Next.js, TypeScript, Vue.js, Node.js, MySQL, and WordPress plugin development.

Japan-focused profile: I build practical web applications from UI to API and database, and I am especially interested in frontend/full-stack roles where product quality, maintainable code, and fast iteration matter.

## Strengths

- React / Next.js: App Router projects, API routes, server/client component separation, search/detail pages, and production build flow
- TypeScript: typed frontend state, API response modeling, reusable utility functions, and safer data access
- Vue.js: Vue 2, Vue Router, Vuex, Axios, component-based mobile UI, location/search/filter/order flows
- Node.js: Express REST APIs, GitHub Actions, Notion API automation, static blog publishing workflow
- MySQL: schema design, relational modeling, indexed search, joins, pagination, and CSV-based data import
- WordPress / PHP: plugin structure, hooks, custom roles/capabilities, activation/deactivation cleanup

## Featured Projects

### RDC Drug Search Platform

Next.js + TypeScript + MySQL application for searching and displaying radioligand drug conjugate data.

- Built searchable drug and chemical entity pages with Next.js App Router
- Implemented API routes for RDC search, status filtering, detail pages, chemical entity lookup, and references
- Designed a normalized MySQL schema for drugs, targets, indications, chemical entities, in vitro data, references, and relationships
- Added CSV templates, validation reports, and import scripts for structured data operations
- Included GitHub Actions workflows for code deployment and database CSV patch workflow

Tech: Next.js, React, TypeScript, MySQL, mysql2, API Routes, GitHub Actions

Repository: https://github.com/crushh/drug

### Vue Ele App

Mobile food delivery style Vue application with location, address selection, shop listing, search, filters, and order/profile pages.

- Built route-based mobile screens using Vue Router
- Managed location and user state with Vuex
- Used Axios to fetch shopping data, filters, restaurant lists, and paginated results
- Implemented UI flows for login guard, city/address selection, search, shop list, filtering, sorting, pull-to-refresh, and load-more behavior
- Integrated Mint UI and better-scroll for mobile interaction patterns

Tech: Vue 2, Vue Router, Vuex, Axios, Mint UI, JavaScript

Repository: https://github.com/crushh/Vue-ele-app

### Notion Blog GitHub Action

Custom GitHub Action that exports Notion database posts to Markdown for static blog systems such as Hexo or Hugo.

- Uses the Notion API to query unpublished posts from a database
- Converts Notion blocks to Markdown and generates YAML front matter
- Supports image migration through PicGo and Aliyun OSS
- Updates Notion publish status after successful export
- Packages the action with `@vercel/ncc` for GitHub Actions usage

Tech: Node.js, GitHub Actions, Notion API, Markdown, YAML, PicGo, Aliyun OSS

Repository: https://github.com/crushh/crushh-blog-actions

### WordPress User Manager Plugin

WordPress plugin prototype for managing custom user roles and capabilities.

- Defines a plugin entry point with WordPress metadata and lifecycle hooks
- Registers custom roles such as student, family, and consultant
- Uses WordPress hooks to initialize role registration
- Includes deactivation cleanup for custom roles, capabilities, user metadata, options, and transient data
- Uses a namespace/autoload structure for plugin classes

Tech: PHP, WordPress Plugin API, Hooks, Roles, Capabilities

Repository: https://github.com/crushh/php-user-manager-01

### Express Recipe API

Small Express REST API for recipe CRUD operations.

- Implements create, list, detail, update, delete endpoints
- Parses JSON request bodies
- Uses predictable JSON response formats
- Includes 404 fallback handling

Tech: Node.js, Express, JavaScript, REST API

Repository: https://github.com/crushh/express-server

### JavaScript Canvas Sketchpad

Browser-based canvas drawing tool.

- Implements drawing with mouse and touch events
- Supports color selection, clear, undo, and redo
- Stores canvas snapshots with `toDataURL`
- Demonstrates direct DOM/canvas interaction and event handling

Tech: JavaScript, HTML Canvas, jQuery, CSS

Repository: https://github.com/crushh/js-sketchpad

## Technical Stack

| Area | Technologies |
| --- | --- |
| Frontend | React, Next.js, TypeScript, Vue.js, JavaScript, HTML, CSS |
| Backend | Node.js, Express, Next.js API Routes |
| Database | MySQL, relational schema design, SQL joins, indexes |
| CMS / Plugin | WordPress, PHP, custom roles/capabilities |
| Automation | GitHub Actions, Notion API, Markdown generation |
| UI / Product | Search UI, detail pages, mobile app flows, filtering, pagination |

## What I Can Contribute

- Build frontend features with React, Next.js, TypeScript, or Vue.js
- Connect UI, API, and database into working product flows
- Improve existing web applications with better structure, typed data, and clearer user experience
- Create internal tools, CMS integrations, and automation workflows
- Work across frontend and backend when teams need flexible implementation support

## Currently Improving

- Japanese engineering communication for interview and team collaboration
- Testing coverage for frontend and backend projects
- Production-ready documentation, deployment notes, and live demos for portfolio repositories

## Contact

- GitHub: https://github.com/crushh
- Portfolio / Blog: https://github.com/crushh/blog
