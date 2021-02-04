<h2> Installation </h2>
<ul>
 <li>git init</li>
 <li>touch .gitignore file</li>
 <li>Remove duplicate dependency quartz</li>
 <li>Add missing dependency spring social</li>

    <dependency>
		    <groupId>org.springframework.social</groupId>
		    <artifactId>spring-social-facebook</artifactId>
		    <version>1.0.0.RELEASE</version>
		</dependency>
    
 <li>git commit</li>
 <li>git new branch dev</li>
</ul>

<h2> Run </h2>
<code>mvn clean install -Penterprise</code>
