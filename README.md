Автоматизируем разработку на Angular с помощью Angular CLI
==========================================================
>> (Angular CLI) https://www.npmjs.com/package/@angular/cli
>> https://dou.ua/lenta/articles/angular-with-angular-cli/

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

>> http://devopspy.com/linux/install-node-js-npm-angular-on-centos-7-x/
(Step 0 – Install the pre-requisites)
> sudo yum remove -y nodejs npm
> sudo rm -fv /etc/yum.repos.d/nodesource*
> sudo yum clean all
> sudo yum -y install epel-release
> sudo yum -y install gcc c++ make

(Option 1: Install Node.js using yum)
> sudo yum -y install nodejs
> node -v
v6.17.1
> npm -v
3.10.10
(Option 2: Install latest Node.js)
> sudo yum remove -y nodejs npm
> sudo rm -fv /etc/yum.repos.d/nodesource*
> curl -sL https://rpm.nodesource.com/setup_7.x | bash -
> sudo yum clean all
> sudo yum install nodejs
> node -v
v7.10.1
> npm -v
4.2.0

> sudo yum remove -y nodejs npm
> sudo rm -fv /etc/yum.repos.d/nodesource*
> curl -sL https://rpm.nodesource.com/setup_8.x | bash -
> sudo yum clean all
> sudo yum install nodejs
> node -v
v8.16.0
> npm -v
6.4.1

> sudo yum remove -y nodejs npm
> sudo rm -fv /etc/yum.repos.d/nodesource*
> curl -sL https://rpm.nodesource.com/setup_10.x | bash -
> sudo yum clean all
> sudo yum install nodejs
> node -v
v10.16.0
> npm -v
6.9.0

>> (Installing Angular CLI) https://cli.angular.io/ >> https://angular.io/cli
> npm install -g @angular/cli
> ng version
Angular CLI: 8.1.1
Node: 10.16.0
OS: linux x64
Angular: 
... 

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.801.1
@angular-devkit/core         8.1.1
@angular-devkit/schematics   8.1.1
@schematics/angular          8.1.1
@schematics/update           0.801.1
rxjs                         6.4.0
> ng help


>> http://2centos.ru/stat/kak_smenit_vladelca_papki_na_linux_centos.htm
> su -
> chown -R alexandr:alexandr /usr/lib/node_modules


