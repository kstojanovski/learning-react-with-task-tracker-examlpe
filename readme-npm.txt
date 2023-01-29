Run the build

1. Install simple server (global)
npm i -g serve

2. Start the build resources as production server where "build" is the folder with the resources
serve -s build -p 8000




Run JSON server

1. Install the JSON server
npm -i json-server

2. Create script in package.json under the "scripts"
"server": "json-server --watch db.json --port 5000"

3. Run the json server pretending it is your back-end with the command
npm run server