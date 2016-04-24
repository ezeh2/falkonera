
# Commons CLI
The Apache Commons CLI library provides an API for parsing command line options passed to programs. It's also able to print help messages detailing the options available for a command line tool.

http://commons.apache.org/proper/commons-cli/usage.html

<dependency>
  <groupId>commons-cli</groupId>
  <artifactId>commons-cli</artifactId>
  <version>1.4-SNAPSHOT</version>
</dependency>

# Commons CSV
Commons CSV reads and writes files in variations of the Comma Separated Value (CSV) format.

http://commons.apache.org/proper/commons-csv/

<dependency>
  <groupId>org.apache.commons</groupId>
  <artifactId>commons-csv</artifactId>
  <version>1.2</version>
</dependency>

# Common Logging

http://commons.apache.org/proper/commons-logging/

# Dependency Injection Options for Java
https://keyholesoftware.com/2014/02/17/dependency-injection-options-for-java/

PicoContainer: Yes (seems to have some popularity)
http://picocontainer.com/introduction.html
<dependency>
	<groupId>picocontainer</groupId>
	<artifactId>picocontainer</artifactId>
	<version>3</version>
</dependency>




Using Spring DI: No
The upside is that if you are already using Spring, enabling and using DI is very easy and makes for a very well integrated approach.
The downside is that if Spring isn’t your thing or you are trying to add DI to an existing enterprise application, 
it may be challenging to isolate the small subset of features that you want to use.

Using Java EE8 CDI: No
It requires a EE-container


# templating engine

http://velocity.apache.org/


# Common Configuration

http://commons.apache.org/proper/commons-configuration/

# Common DbUtils

http://commons.apache.org/proper/commons-dbutils/

