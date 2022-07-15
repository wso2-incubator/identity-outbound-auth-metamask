1. Add <servlet-mapping> and  <servlet> for metamask.jsp page to <IS_HOME>-> repository -> deployment -> server ->
   webapps -> authenticationendpoint -> web.xml

``` 
<servlet>
<servlet-name>metamask.do</servlet-name>
<jsp-file>/metamask.jsp</jsp-file>
</servlet>
<servlet-mapping>
<servlet-name>metamask.do</servlet-name>
<url-pattern>/metamask.do</url-pattern>
</servlet-mapping>
```