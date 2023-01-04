# Github Action to Sync Commits to Notion

## Database Properties
- Title - Title
- Description - Text
- Author - People
- Timestamp - Date
- SHA - Text
- Committer - People
- URL - URL

## Secrets
- NOTION_SECRET: Notion api secret key
- NOTION_DATABASE: Notion database id
- NOTION_USERS: email to Notion user id mapping (optional)

  ex) 
  
  first_user@email.com asdf1230-qwer23857-asdf123
  
  second_user@email.com 123asdf-2345zdfb-95287

## Notes
- `main` branch only. Edit the yaml file at your needs
- Notion api key: https://www.notion.so/my-integrations
- Connect your database page with the api key. Click ... > connect > select your api key
- Notion user id: https://dev.to/victoriaslocum/how-to-find-non-admin-notion-user-ids-5277
