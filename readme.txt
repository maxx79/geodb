1. To assemble the project, just use maven: <mvn package> in command line
2. To run the application, just type: <java -jar geodb-1.0-SNAPSHOT.jar> in command line
3. It needs to place the next files in the same directory, where you will run the application from:
	-operations.data,
	-shapes.db
4. updated.db is placed in db directory of the project root
5. Errors of running the application, you can see in console or you can redirect all messages into files, in such manner:
	java -jar geodb-1.0-SNAPSHOT.jar 1>out 2>err