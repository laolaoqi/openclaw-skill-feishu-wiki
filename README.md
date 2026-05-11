# Feishu Wiki Navigator Skill Pack

## Description
Knowledge base navigation. Browse spaces, manage pages, create and organize wiki content.

## Quick Install
```
openclaw skills enable feishu-wiki
openclaw skills enable feishu-doc
```

## Features
- List accessible wiki spaces
- Browse page hierarchy
- Create wiki pages (docx, sheet, bitable, mindnote)
- Move and rename pages
- Read/edit workflow via feishu_doc

## Configuration
```yaml
channels:
  feishu:
    tools:
      wiki: true
      doc: true
```

## Dependency
Requires feishu-doc for content reading/writing.

## License MIT