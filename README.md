# KariKids
Download Ecliple EE.
Firstly, you can create next project:
New-Maven project - (choose "create a simple project") - Enter Group ID and Artifact Id (it's just like a folder name. It doesn't matter for us now) - press Finish.
In the end of the Project explorer you can find "pom file." Please, add next lines above </project> :

<dependencies>
	  <dependency>
	    <groupId>junit</groupId>
	    <artifactId>junit</artifactId>
	    <version>4.13.2</version>
	    <scope>test</scope>
	</dependency>
</dependencies>

Now you can use @Test annotations. Good luck.
