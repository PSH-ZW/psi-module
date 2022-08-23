#PSI OMOD
Omod for handling "Automatic Program Enrollment" and generation of UIC and PREP identifiers.

##Release 2 Update:
Added STI Auto program enrollment

##Building the omod.
Run `mvn clean install -DskipTests` from root project directory. The omod will be built in omod/target .
This needs to be copied to /opt/openmrs/modules in the server where openmrs is running. Openmrs needs to be restarted for the omod to be loaded.
