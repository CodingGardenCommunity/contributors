# Contributors

This repo holds the `contributors.json` file that is used to load contributor info into the app.

## Adding / updating a contributor

```sh
npm install # install prettier and pre-commit hooks
```

Create a pull request with the contributor info added at the end of the `contributors.json` file.

Format the file using the built in prettier rules before committing:

```sh
npm run format
```

## Contributor Info

### Name

Your name. The name to be displayed on the contributors page.

### Github

Your github username.

### Image

The URL to a square image to be used on the contributors page. Ideally, use your github image URL.

### Country Code

3 letter country code. Choose a code from the official ISO list: https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes

### Joined

The date when you joined the Coding Garden Community App team.

Joined date should use the format YEAR-MONTH-DAY e.g. 2018-12-16

### Team Ids

Team ids are:

* 0 - Planning
* 1 - Design
* 2 - Frontend
* 3 - Backend
* 4 - DevOps
* 5 - Functional Testing

### Format

Contributor info is in the following format:

```json
{
  "name": "CJ",
  "github": "w3cj",
  "image": "https://avatars1.githubusercontent.com/u/14241866",
  "country_code": "USA",
  "active": true,
  "joined": "2018-12-16",
  "team_ids": [0, 1, 2, 3, 4]
}
```