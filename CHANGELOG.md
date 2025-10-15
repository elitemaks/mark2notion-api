## 2025-10-15

- Fix: Markdown with literal escaped newlines (`\n`, `\r\n`, `\r`) now properly splits into separate blocks. The API now accepts both actual newlines and escaped sequences.

## 2025-10-13

- Feature: Added `/api/notion-to-markdown` endpoint for exporting Notion pages to Markdown format. Supports all block types including tables, lists, code blocks, and child pages.

## 2025-10-02

- Fix: Quote blocks no longer display "Empty quote" labels in Notion. Simple quotes now render cleanly with content directly visible.

## 2025-10-01

- Fix: Financial amounts like $100 or $1-$3m are no longer incorrectly formatted as LaTeX equations.

## 2025-09-29

- Feature: Added `/api/append-blocks` endpoint for appending prebuilt Notion blocks.

## 2025-09-10

- Fix: Preserve table rows when appending tables nested inside lists. 


