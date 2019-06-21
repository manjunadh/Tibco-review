java -Dlog4j.configuration=file:"<Log4j file path>" -jar tibreview-0.0.4-jar-with-dependencies.jar -r < tibrules.xml  path> -c < config.properties  path> -i <project or process> -s <Project directory path> -o <format csv or pmd> -t <report generation path>

Sample commands:
java -Dlog4j.configuration=file:"D:/deployment/tmpTibco/TIBreview/target" -jar tibreview-0.0.4-jar-with-dependencies.jar -r D:/deployment/tmpTibco/TIBreview/target/tibrules.xml -c D:/deployment/tmpTibco/TIBreview/target/config.properties -i project -s C:/Users/p7111943/Downloads/DBPattern/DBPattern/DBEventPattern -o csv -t D:/deployment/tmpTibco/TIBreview/target

java -Dlog4j.configuration=file:"D:/deployment/tmpTibco/TIBreview/target" -jar tibreview-0.0.4-jar-with-dependencies.jar -r D:/deployment/tmpTibco/TIBreview/target/tibrules.xml -c D:/deployment/tmpTibco/TIBreview/target/config.properties -i project -s C:/Users/p7111943/Downloads/DBPattern/DBPattern/DBEventPattern -o pmd -t D:/deployment/tmpTibco/TIBreview/target



