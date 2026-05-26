# Notes API

## Create Note

POST /api/notes

### Request Body

```json
{
  "title": "Meeting Notes",
  "content": "Discuss backend architecture"
}

### Error Response

```json
{
  "error": "Unauthorized access"
}