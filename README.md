# lifecycle
Command to create project.

mvn archetype:generate
  -DgroupId=com.app
  -DartifactId=Lifecycle
  -Dname=Lifecycle
  -Dpackage=com.app.services
  -DarchetypeGroupId=io.dropwizard.archetypes
  -DarchetypeArtifactId=java-simple
  -DinteractiveMode=false
  
 #Annotations like @GET
 are part of "Java API for RESTful Web Services (JAX-RS)", and its reference implementation "Jersey"  is the cornerstone of Dropwizard.Other annotations include @POST for HTTP POST method, @DELETE for DELETE and so on and media types include MediaType.APPLICATION_JSON etc.
