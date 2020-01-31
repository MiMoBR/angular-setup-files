1- install node
Open a command prompt (or PowerShell), and enter the following:

	node –v

The system should display the Node.js version installed on your system. You can do the same for NPM:

	npm –v


2- install npm


3- install cli Angular
npm install -g @angular/cli

3.1 - re-install project builted
npm install -g @angular/cli 


4- criar um novo projeto angular
ng new "namo_of_project"


5- run server
abrir a pasta do projeto

ng serve --open


6- executar um projeto existente

    1- install as dependecias
    aceder à raiz do projecto onde esta o package.json
    - npm install

    2- criar uma pasta node_modules necessrio para toda a applicação.

    3- trabalhar de forma normal


7- install bootstrap
npm install --save bootstrap@3


8- change css source
angular.json > architect > "styles"

to add news
node_modules > node_modules\bootstrap\dist\css\bootstrap.min.css


9- copy component
ng g c servers  (servers that will be the name of new component)


10- update
ng update
