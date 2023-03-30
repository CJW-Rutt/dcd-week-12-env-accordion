1. Create a file at the root of a project
```
.env
```
2. inside the .env file add the text:
- You must use `NEXT_PUBLIC` or else this will not work
```
NEXT_PUBLIC_TITLE = "Digital Design and Development"
```
3. On the page, in between the export and report write the variable:
```
var title = process.env.NEXT_PUBLIC_TITLE;
```
4. Then in between the main tag write:
```
{title}
```
5. Make sure the `.gitignore` file has the `.env` inside
-  you want to prevent the secret title to be shown

## BCIT Data from Digital Development and Design Diploma
[Digital Design and Development Diplomea](https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/)

