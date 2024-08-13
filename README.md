# Trello API Collection

This collection contains basic requests for creating, updating, and deleting items using the public Trello API through Postman. The methods used include `POST`, `GET`, `PUT`, and `DELETE`. Scripts are automated using collection variables and the `setNextRequest` method.

The requests include scripts and tests written in JavaScript.

## Automation
The collection can be run using Postman CLI or Newman. Additionally, simple jobs for CI/CD workflows have been created in Jenkins, implemented using Docker.

## API Keys and Tokens
API keys and tokens are not included in the collection variables due to security reasons. You can generate your own custom Trello API keys and tokens via the Trello API documentation: [Trello API](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions).

## Collection Import
1. Clone or download the Trello collection (in `.json` format) and import it into Postman.
2. Generate your own API key and API token [here](https://developer.atlassian.com/cloud/trello/power-ups/).
3. Add the values (API key and API token) to the collection variables (current values).
4. Run the collection using Postman CLI or Newman.
