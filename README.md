# LoadingPropertiesFilesAsPartOfApplicationConfiguration

db.driverClassName=com.mysql.cj.jdbc.Driver

db.url=jdbc:mysql://localhost:3306/springwithjdbcdb

db.username=root

db.password=root

 <bean id="dataSource" class="org.springframework.jdbc.datasource.DriverManagerDataSource">
 
    <property name="driverClassName" value="${db.driverClassName}"></property>
    
    <property name="url" value="${db.url}"></property>
    
    <property name="username" value="${db.username}"></property>
    
    <property name="password" value="${db.password}"></property>
    
    </bean>
