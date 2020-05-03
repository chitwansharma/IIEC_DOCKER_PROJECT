# IIEC_DOCKER_PROJECT
Under iiec rise1.0 compaign. I completed my training of DOCKER under the guidance of VIMAL DAGA SIR. 
here is my project using docker to set up a webapp Jhoomla.
# The setup of project is explained below.
 In redhat enterprise linux install the docker software.
# 2.set up the things--
*disabling firewall* becoz it might block some metworking stuffs.
                       *starting the docker* (command - systemctl start docker)
# 3. Download reqiured images -- 
*mysql image*
                               *jhoomla image*(by apply pull command)
# 4. Setting Up mysql -- 
use command --- docker run -it -e MYSQL_ROOT_PASSWORD=(any password you like) -e MYSQL_USER=(any user name) -e MYSQL_PASSWORD=(any password(recommended not to use root password) -e MYSQL_DATABASE=(any database name) --name joomladb mysql:5.6
                   --- then use command -- yum install mysql
# 5. Docker compose
.   before using docer compose you have to use the software *dockercompose*
     then you can create and edit file using command-- vim docker-compose.yml
      write all the command in the file and save it
   	#docker compose up
	use command docker -compose up to complete the setup
	# jhoomla started
# 6. Open Google and type -
	 -localhist:80 
	   then the jhoomla webapp opens
	# Docker container start stop
	 after completing docker compose up now in one click you can stop your whole setup
	 command-- docker-compose stop
	 #docker compose down:
	 you can easily stop the container using command --docker compose dow
	 
I learnt this technology on youtube by vimal daga sir and it is free of cst under IIEC RISE.
# THANK YOU
