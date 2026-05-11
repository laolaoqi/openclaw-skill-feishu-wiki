# Feishu Wiki Tool

Single tool `feishu_wiki` for knowledge base operations.

## Actions
- spaces - List knowledge spaces
- nodes - List nodes (with optional parent_node_token)
- get - Get node details
- create - Create node (obj_type: docx, sheet, bitable, mindnote, file, doc, slides)
- move - Move node
- rename - Rename node

## Wiki-Doc Workflow
1. Navigate: feishu_wiki -> get obj_token
2. Read: feishu_doc -> read document content
3. Edit: feishu_doc -> write/append content

## Dependency
Requires feishu_doc for content reading/writing.

## Permissions
Required: wiki:wiki or wiki:wiki:readonly