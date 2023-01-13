Changes in version 3.0.0-SNAPSHOT

1. Modified spring-parent groupId to com.nextgen.pxp
2. Upgraded spring-boot-starter-parent version to 2.6.3
3. Upgraded spring-boot-release.version to 2.6.3 in properties to match the spring-boot-starter-parent version
4. The major version number is changed (2.4.0 to 3.0.0) because of following changes
    1. Replaced io.springfox:springfox-boot-starter:3.0.0 with org.springdoc:springdoc-openapi-ui:1.6.4
    2. Moved following to [spring-data](https://bitbucket.nextgen.com/projects/MFPLAT/repos/spring-data/browse) wrapper for separation of concerns.
        1. org.springframework.boot:spring-boot-starter-data-jpa
        2. org.springframework.boot:spring-boot-starter-data-jdbc
        3. org.springframework.boot:spring-boot-starter-data-mongodb
        4. org.springframework.boot:spring-boot-starter-data-cassandra

