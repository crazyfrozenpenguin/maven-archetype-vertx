Maven Archetype for Vertx 
=========================

This archetype would help in setting up project structure for vertx module.


# Building the Archetype

  `mvn clean deploy`

# Creating a project using the Archetype

  `mvn archetype:generate  -DarchetypeRepository=file:///tmp/mvn-repo/ \
   -DarchetypeGroupId=org.vertx.build  -DarchetypeArtifactId=maven-archetype-vertx -DarchetypeVersion=2.0`

# To dos.

 * Get the created project to compile! :)
 * Replace all com.mycompany stuff to proper groupId / package name.
 * See if lang parameter can be added, so that we can generate only language specific files.

