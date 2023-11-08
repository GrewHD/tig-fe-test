# Front End Coding Test

Time Spent: 8h

Deployed Site: https://grewhd.github.io/tig-fe-test/

## Description
For this Front End coding challenge, I have built two basic views that require querying a GraphQl API to retrieve necessary information. The first view is the Shipments View, which displays a list of shipments, and the second view is the Shipment Details View, which displays detailed information about a selected shipment along with its tracking events.

## Installation and Setup
1. Clone the repository: `git clone https://github.com/GrewHD/tig-fe-test`
2. Navigate to the project directory: `cd tig-fe-test`
3. Install dependencies: `yarn install`
4. Start the development server: `yarn dev`

## Usage
Once the development server is running, you can access the application by visiting `http://127.0.0.1:5173/tig-fe-test/` in your web browser.

## Technologies Used
- React
- TypeScript
- CSS3/HTML5
- Chakra UI
- GraphQL

## API Information
- GraphQL API URL: https://fe-coding-test-o6yezgstiq-km.a.run.app/graphql
- Header: `x-token: fe-test-2023`

## Views
### Shipments View
This view displays a list of shipments retrieved from the GraphQL query. Each shipment is displayed with its trackingId and status, ordered by lastUpdate.

### Shipment Details View
This view displays all fields of a selected shipment, along with its tracking events obtained from the `trackingEvents` GraphQL query.

## Design
The design for the application can be found [here](https://www.figma.com/proto/vj6TJcn2qt4NQVjAnSaNYN/Frontend-Candidate-Test?page-id=0%3A1&type=design&node-id=1-1746&viewport=502%2C508%2C0.5&t=pOViT7evKibaNxiv-1&scaling=scale-down&mode=design). (Password is `TIG2023`)
