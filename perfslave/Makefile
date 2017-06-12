
clean:
	@mvn clean

compile: clean
	@mvn package

run: compile
	@mvn hpi:run -Djetty.port=8090 -Pjenkins
