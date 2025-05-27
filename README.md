# tomcat-users


<?xml version='1.0' encoding='cp1252'?>
<tomcat-users xmlns="http://tomcat.apache.org/xml"
              xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
              xsi:schemaLocation="http://tomcat.apache.org/xml tomcat-users.xsd"
              version="1.0">


  <!-- Roles Declaration -->
  <role rolename="manager-gui"/>
  <role rolename="manager-script"/>


  <!-- Users with assigned roles -->
  <user username="admin" password="admin" roles="manager-gui"/>
  <user username="tomcat" password="tomcat" roles="manager-script"/>


  <!-- Example roles and users for the examples app (optional, not active) -->
  <!--
  <role rolename="tomcat"/>
  <role rolename="role1"/>
  <user username="tomcat" password="changeit" roles="tomcat"/>
  <user username="both" password="changeit" roles="tomcat,role1"/>
  <user username="role1" password="changeit" roles="role1"/>
  -->


</tomcat-users>
