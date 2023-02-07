# maven-repository
Private Maven Repositories

usage:  
pom.xml  
<code>
\<repositories\>
&emsp;&emsp;\<repository\>
&emsp;&emsp;&emsp;&emsp;\<id\>nctsc\</id\>
&emsp;&emsp;&emsp;&emsp;\<url\>https://raw.github.com/nctsc/maven-repository/</url\>
&emsp;&emsp;\</repository\>
\</repositories\>

\<dependencies\>
&emsp;&emsp;\<dependency\>
&emsp;&emsp;&emsp;&emsp;\<groupId\>cp.mvnrepo\</groupId\>
&emsp;&emsp;&emsp;&emsp;\<artifactId\>testmvnrepo\</artifactId\>
&emsp;&emsp;&emsp;&emsp;\<version\>1.0-SNAPSHOT\</version\>
&emsp;&emsp;\</dependency\>
\</dependencies\>
</code>
