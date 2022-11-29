## **App and links**

### **student**


### **mechanism**
![[Pasted image 20221119110328.png]]

### **Dean**


### **Teacher**


### **check**


## Videos



## **Techs**
* Springboot
* Mybatis
* MySQL
* Redis
* Shiro
* Jwt
* Druid
* Swagger
* Vue



###  The project

The main idea of this project is to connect scientific research institutes, training institutions and employers of lifelong education archives to jointly maintain students' lifelong learning files and protect the privacy of students' files based on asymmetric encryption and proxy re-encryption. Any unauthorized checker cannot decipher the lifelong education archives.

### Main features
* Web version(For student)
	* Register user
	* Lifelong education archives
	* Authorization checker
* Web version(For mechanism admin)
	* Create a new teacher  and dean account
* Web version(For dean)
	* Create new majors and courses 
* Web version(For teacher)
	* Submit the achievement to the blockchain
	* Review achievement


### How to run this project

_**To run quickly**_

```
$ docker地址
```

_**To run Backend_
1.install fisco and webase to ubuntu system[FISCO BCOS](https://github.com/FISCO-BCOS/FISCO-BCOS)   [WeBase](https://github.com/WeBankBlockchain/WeBASE)   
**2.deploy four contracts on webase**
贴四个合约地址
**3.configure blockchain certificate link, contract address, MySQL database and Redis account password
4.configure system-manager's email in the yaml file**
**5.Start nginx after replacing nignix.conf with XX file**
**6.Start the three Springboot services of allianceService, checkService and personService in IDEA**


_**To run Frontend**_
The Vue projects of alliance, check and person are started as follows
```
$ npm install
$ npm run serve
```


### License

This project is unde MIT license. See the file [LICENSE](https://github.com/rodrigofolha/pack-food/blob/develop/LICENSE) to more details.

