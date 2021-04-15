#### ![liquibase](https://www.liquibase.com/wp-content/themes/liquibase/assets/img/logo.svg) <h2>+</h2> ![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

<sub>(we can thinking about new logo for spesific repo)</sub>

# Node.js wrapper for Liquibase

[![Build Status](https://travis-ci.org/zachleat/BigText.png?branch=master)](https://travis-ci.org/zachleat/BigText)
![npm_version](https://img.shields.io/node/v/3)
![status](https://img.shields.io/uptimerobot/status/m778918918-3e92c097147760ee39d02d36)

## Requirements

1. Download Node.js from this [source](https://nodejs.org/en/)

## Installation

To install from the NPM directory type the following<br>

```$ npm install --save liquibase```

## Examples

### Simple Example
From the index.js (`/node-liquibase/lib`) file adjust "<>" fields accordingly:

```
//******** MSSQL default parameters template *********
liquibase: 'liquibase-4.0.0/liquibase',
changeLogFile: 'change-log-examples/mssql/changelog.mssql.sql',
url: '"jdbc:sqlserver://<IP OR HOSTNAME>:<port number>;database=<database name>;"',
username: '<username>',
password: '<password>',
liquibaseProLicenseKey: '<paste liquibase-pro-license-key here>',
classpath: 'Drivers/mssql-jdbc-7.4.1.jre8.jar
```
```
//******** postgreSQL default parameters template *********
// liquibase: 'liquibase-4.0.0/liquibase',
// changeLogFile: 'change-log-examples/postgreSQL/changelog.postgresql.sql',
// url: 'jdbc:postgresql://<host>:5432/MYDATABASE_TEST',
// username: 'postgres',
// password: 'password',
// liquibaseProLicenseKey: '<paste liquibase-pro-license-key here>',
// classpath: 'Drivers/postgresql-42.2.8.jar'
```
```
.run('<action>', '<action-params>')
.then(() => console.log('success'))
.catch((err) => console.error('fail', err));
```


## Development

### Build

If you need to build local code changes, you may do so with:<br>

```$npm run build```

### Tests
You can run test with:<br>

```$npm run test```

To substitute your own user/pass for a given environment, make a copy of .env.example in root directory as .env and update accordingly.

### For more references please use liquibase [documentation](https://docs.liquibase.com/home.html)
    
## Releases

* (e.g.`v0.1.0` Initial release)

## Author
* **Taylor Buckner** - *Software Engineer*

## Getting more knowledge about liquibase:

* Liquibase University [page](https://learn.liquibase.com/index)

## [Download Liquibase CLI](https://www.liquibase.org/download)

[![twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)][1][![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)][2][![stackoverflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)][3][![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)][4][![youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)][5]

[1]: https://twitter.com/liquibase
[2]: https://www.linkedin.com/company/liquibase
[3]: https://stackoverflow.com/tags/liquibase/
[4]: https://github.com/liquibase/liquibase
[5]: https://www.youtube.com/channel/UC5qMsRjObu685rTBq0PJX8w
