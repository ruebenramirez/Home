I've created a Vagrantfile that will allow you to build and run this docker container from any platform that vagrant will run on.  (windows/mac os x/linux)

### prerequisites 

* install virtualbox for your platform from: https://www.virtualbox.org/wiki/Downloads
* install vagrant for your platform from: https://www.vagrantup.com/downloads.html
* install git https://git-scm.herokuapp.com/book/en/v2/Getting-Started-Installing-Git

### run the container!

Do these steps from a command-prompt/terminal:

* clone the repo down with
`git clone https://github.com/ruebenramirez/Home`

* nav into the ./samples/HelloWeb/ directory

* run vagrant
`vagrant up`

* wait for vagrant to build the proxy vm (that will serve as the docker container host vm) and then to pull down the base docker image and to finally build out and run the docker container...

* open up your browser to [http://127.0.0.1:8181](http://127.0.0.1:8181) to see the ASP.NET HelloWeb sample app running in a linux container.

