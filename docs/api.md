# Notes API

## Create Note

POST /api/notes

### Request Body

```json
{
  "title": "Meeting Notes",
  "content": "Discuss backend architecture along with high level system design"
}

### Error Response

```json
{
  "error": "Unauthorized access. Access can't be granted"
}