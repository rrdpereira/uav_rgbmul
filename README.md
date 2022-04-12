# Projeto de Implementação 2 - uav_rgbmul

Neste repositório se encontra o pacote uav_rgbmul utilizado para a execução do Projeto de Implementação 2, da disciplina Robôs Móveis Autônomos (RMA) - DC UFSCar

## Dependências ROS 1 @ Ubuntu 20.4
Durante a disciplina foram instalados o `ROS 1 noetic` e os pacotes ROS necessários de acordo a lista a seguir ou no aquivo `ROS_requirements.txt`:

*	sudo apt-get install git-all
*	sudo apt install ros-noetic-hector-gazebo
*	sudo apt install ros-noetic-velodyne-description
*	
*	sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \
*	ros-noetic-teleop-twist-keyboard ros-noetic-laser-proc \
*	ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \
*	ros-noetic-rosserial-python ros-noetic-rosserial-client \
*	ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \
*	ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \
*	ros-noetic-compressed-image-transport ros-noetic-rqt* \
*   ros-noetic-rviz \
*	ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-markers
*	
*	sudo apt install ros-noetic-dynamixel-sdk
*	sudo apt install ros-noetic-turtlebot3-msgs
*	sudo apt install ros-noetic-turtlebot3
*	
*	sudo apt-get install ros-noetic-cmake-modules \
*	ros-noetic-velodyne-gazebo-plugins \
*	python3-wstool \
*	python3-catkin-tools \
*	ros-noetic-ompl \
*	ros-noetic-navfn \
*	ros-noetic-dwa-local-planner \
*	ros-noetic-costmap-2d \
*	ros-noetic-teb-local-planner \
*	ros-noetic-robot-self-filter \
*	ros-noetic-pointcloud-to-laserscan \
*	ros-noetic-ros-numpy
*	
*	sudo apt-get install ros-noetic-openslam-gmapping
*	sudo apt-get install ros-noetic-gazebo-ros-pkgs ros-noetic-gazebo-ros-control
*	
*	sudo apt-get install ros-noetic-kobuki ros-noetic-kobuki-core
*	sudo apt-get install ros-noetic-kobuki-gazebo


## Dependências Python3 @ Ubuntu 20.4

Além dos pacotes obtidos durante a execução da disciplina, um snapshot das dependências dos códigos python estão a seguir ou no arquivo `Python_requirements.txt`:

*	actionlib==1.13.2
*	alabaster==0.7.8
*	angles==1.9.13
*	apturl==0.5.2
*	argcomplete==2.0.0
*	attrs==19.3.0
*	autobahn==17.10.1
*	Automat==0.8.0
*	Babel==2.6.0
*	base-local-planner==1.17.1
*	bcrypt==3.1.7
*	beautifulsoup4==4.8.2
*	blinker==1.4
*	bloom==0.10.7
*	bondpy==1.8.6
*	breezy==3.0.2
*	Brlapi==0.7.0
*	cached-property==1.5.2
*	camera-calibration==1.16.0
*	camera-calibration-parsers==1.12.0
*	catkin==0.8.10
*	catkin-pkg==0.4.24
*	catkin-pkg-modules==0.4.24
*	catkin-tools==0.8.5
*	cbor==1.0.0
*	Cerberus==1.3.4
*	certifi==2019.11.28
*	chardet==3.0.4
*	classproperties==0.2.0
*	Click==7.0
*	colorama==0.4.3
*	command-not-found==0.3
*	configobj==5.0.6
*	constantly==15.1.0
*	controller-manager==0.19.5
*	controller-manager-msgs==0.19.5
*	coverage==6.3.2
*	crcmod==1.7
*	cryptography==2.8
*	cupshelpers==1.0
*	cv-bridge==1.16.0
*	cycler==0.10.0
*	Cython==0.29.14
*	datafiles==1.2
*	dbus-python==1.2.16
*	defer==1.0.6
*	defusedxml==0.6.0
*	Deprecated==1.2.7
*	diagnostic-analysis==1.11.0
*	diagnostic-common-diagnostics==1.11.0
*	diagnostic-updater==1.11.0
*	distro==1.4.0
*	distro-info===0.23ubuntu1
*	docutils==0.16
*	drone-wrapper==1.4.2
*	dulwich==0.19.15
*	duplicity==0.8.12.0
*	dynamic-reconfigure==1.7.2
*	dynamixel-sdk==3.7.51
*	empy==3.3.2
*	entrypoints==0.3
*	fasteners==0.14.1
*	fastimport==0.9.8
*	future==0.18.2
*	gazebo-plugins==2.9.2
*	gazebo-ros==2.9.2
*	gazebo-video-monitor-utils==0.7.0
*	gencpp==0.6.5
*	geneus==3.0.0
*	genlisp==0.4.18
*	genmsg==0.5.16
*	gennodejs==2.0.2
*	genpy==0.6.15
*	gitman==3.1
*	gnupg==2.3.1
*	gpg===1.13.1-unknown
*	html5lib==1.0.1
*	httplib2==0.14.0
*	hyperlink==19.0.0
*	idna==2.8
*	image-geometry==1.16.0
*	imagesize==1.2.0
*	importlib-metadata==1.5.0
*	importlib-resources==5.6.0
*	incremental==16.10.1
*	interactive-markers==1.12.0
*	Jinja2==2.10.1
*	joint-state-publisher==1.15.1
*	joint-state-publisher-gui==1.15.1
*	jsonschema==4.4.0
*	kconfiglib==14.1.0
*	keyring==18.0.1
*	kitchen==1.2.6
*	kiwisolver==1.0.1
*	language-selector==0.1
*	laser-geometry==1.6.7
*	launchpadlib==1.10.13
*	lazr.restfulclient==0.14.2
*	lazr.uri==1.0.3
*	lockfile==0.12.2
*	louis==3.12.0
*	lxml==4.5.0
*	lz4==3.0.2+dfsg
*	macaroonbakery==1.3.1
*	Mako==1.1.0
*	MarkupSafe==1.1.0
*	matplotlib==3.1.2
*	mavros==1.13.0
*	message-filters==1.15.14
*	minilog==2.1
*	monotonic==1.5
*	more-itertools==4.2.0
*	mpi4py==3.0.3
*	netifaces==0.10.4
*	nose==1.3.7
*	numpy==1.22.1
*	nunavut==1.7.5
*	oauthlib==3.1.0
*	olefile==0.46
*	opencv-contrib-python==3.4.8.29
*	opencv-python==3.4.8.29
*	osrf-pycommon==2.0.1
*	packaging==20.3
*	pandas==1.0.4
*	paramiko==2.6.0
*	parse==1.19.0
*	pexpect==4.6.0
*	Pillow==7.0.0
*	pkgconfig==1.5.5
*	pr2-power-board==1.1.10
*	prettytable==0.7.2
*	protobuf==3.6.1
*	psutil==5.5.1
*	py-trees==0.7.6
*	py-ubjson==0.14.0
*	pyasn1==0.4.2
*	pyasn1-modules==0.2.1
*	pycairo==1.16.2
*	pycryptodomex==3.6.1
*	pycups==1.9.73
*	pydot==1.4.1
*	pydsdl==1.14.1
*	pygame==2.1.2
*	PyGithub==1.43.7
*	Pygments==2.3.1
*	PyGObject==3.36.0
*	pygraphviz==1.5
*	PyHamcrest==1.9.0
*	PyICU==2.4.2
*	PyJWT==1.7.1
*	pymacaroons==0.13.0
*	pymavlink==2.4.29
*	PyNaCl==1.3.0
*	PyOpenGL==3.1.0
*	pyOpenSSL==19.0.0
*	pyparsing==2.4.6
*	pypng==0.0.20
*	PyQRCode==1.2.1
*	PyQt5==5.14.1
*	pyRFC3339==1.1
*	pyros-genmsg==0.5.8
*	pyrsistent==0.18.1
*	pyserial==3.4
*	python-apt==2.0.0+ubuntu0.20.4.7
*	python-dateutil==2.8.2
*	python-debian===0.1.36ubuntu1
*	python-gitlab==2.0.1
*	python-gnupg==0.4.5
*	python-qt-binding==0.4.4
*	python-snappy==0.5.3
*	PyTrie==0.2
*	pytz==2022.1
*	pyulog==0.9.0
*	pyxdg==0.26
*	PyYAML==5.3.1
*	qt-dotgraph==0.4.2
*	qt-gui==0.4.2
*	qt-gui-cpp==0.4.2
*	qt-gui-py-common==0.4.2
*	reportlab==3.5.34
*	requests==2.22.0
*	requests-unixsocket==0.2.0
*	resource-retriever==1.12.7
*	roman==2.0.0
*	ros-numpy==0.0.5
*	rosbag==1.15.14
*	rosboost-cfg==1.15.8
*	rosclean==1.15.8
*	roscreate==1.15.8
*	rosdep==0.21.0
*	rosdep-modules==0.21.0
*	rosdistro==0.8.3
*	rosdistro-modules==0.8.3
*	rosdoc-lite==0.2.10
*	rosgraph==1.15.14
*	roslaunch==1.15.14
*	roslib==1.15.8
*	roslint==0.12.0
*	roslz4==1.15.14
*	rosmake==1.15.8
*	rosmaster==1.15.14
*	rosmsg==1.15.14
*	rosnode==1.15.14
*	rosparam==1.15.14
*	rospkg==1.4.0
*	rospkg-modules==1.4.0
*	rospy==1.15.14
*	rosserial-arduino==0.9.2
*	rosserial-client==0.9.2
*	rosserial-python==0.9.2
*	rosservice==1.15.14
*	rostest==1.15.14
*	rostopic==1.15.14
*	rosunit==1.15.8
*	roswtf==1.15.14
*	rqt-action==0.4.9
*	rqt-bag==0.5.1
*	rqt-bag-plugins==0.5.1
*	rqt-console==0.4.11
*	rqt-controller-manager==0.19.5
*	rqt-dep==0.4.12
*	rqt-drone-teleop==1.4.2
*	rqt-ez-publisher==0.6.1
*	rqt-graph==0.4.14
*	rqt-ground-robot-teleop==1.4.2
*	rqt-gui==0.5.3
*	rqt-gui-py==0.5.3
*	rqt-image-view==0.4.16
*	rqt-joint-trajectory-controller==0.19.0
*	rqt-launch==0.4.9
*	rqt-logger-level==0.4.11
*	rqt-moveit==0.5.10
*	rqt-msg==0.4.10
*	rqt-multiplot==0.0.12
*	rqt-nav-view==0.5.7
*	rqt-plot==0.4.13
*	rqt-pose-view==0.5.11
*	rqt-pr2-dashboard==0.4.0
*	rqt-publisher==0.4.10
*	rqt-py-common==0.5.3
*	rqt-py-console==0.4.10
*	rqt-py-trees==0.4.1
*	rqt-reconfigure==0.5.4
*	rqt-robot-dashboard==0.5.8
*	rqt-robot-monitor==0.5.14
*	rqt-robot-steering==0.5.12
*	rqt-runtime-monitor==0.5.9
*	rqt-rviz==0.7.0
*	rqt-service-caller==0.4.10
*	rqt-shell==0.4.11
*	rqt-srv==0.4.9
*	rqt-tf-tree==0.6.2
*	rqt-top==0.4.10
*	rqt-topic==0.4.13
*	rqt-web==0.4.10
*	ruamel.yaml==0.17.21
*	ruamel.yaml.clib==0.2.6
*	rviz==1.14.14
*	scipy==1.8.0
*	screen-resolution-extra==0.0.0
*	SecretStorage==2.3.1
*	sensor-msgs==1.13.1
*	service-identity==18.1.0
*	simplejson==3.16.0
*	sip==4.19.21
*	six==1.14.0
*	smach==2.5.0
*	smach-ros==2.5.0
*	smach-viewer==3.0.1
*	smclib==1.8.6
*	soupsieve==1.9.5
*	Sphinx==1.8.5
*	systemd-python==234
*	termcolor==1.1.0
*	tf==1.13.2
*	tf-conversions==1.13.2
*	tf2-geometry-msgs==0.7.5
*	tf2-kdl==0.7.5
*	tf2-py==0.7.5
*	tf2-ros==0.7.5
*	tf2-sensor-msgs==0.7.5
*	toml==0.10.2
*	tomlkit==0.7.2
*	topic-tools==1.15.14
*	turtlebot3-example==1.2.5
*	turtlebot3-teleop==1.2.5
*	Twisted==18.9.0
*	txaio==2.10.0
*	typing-extensions==3.10.0.2
*	u-msgpack-python==2.1
*	ubuntu-advantage-tools==27.7
*	ubuntu-drivers-common==0.0.0
*	ufw==0.36
*	unattended-upgrades==0.1
*	unique-id==1.0.6
*	urllib3==1.25.8
*	usb-creator==0.3.7
*	vcstools==0.1.42
*	wadllib==1.3.3
*	webencodings==0.5.1
*	wrapt==1.11.2
*	wsaccel==0.6.2
*	wstool==0.1.18
*	xacro==1.14.13
*	xkit==0.0.0
*	zipp==3.8.0
*	zope.interface==4.7.1



As dependências python são verificadas na etapa de instalação a seguir

## Dataset
O conjunto de cenas utilizados no projeto podem ser baixados no [link](https://drive.google.com/drive/folders/1vk6gPcW1IOpSs3nB-Of2wlZHCOxYFdBx?usp=sharing).

Para pré-processamento do dataset foi utilizado a ferramenta computacional Labelbox [link](https://labelbox.com/).

## Instalação

Para a instalação desse pacote, é necessário criar um novo workspace para a instalação e construção do ambiente de simulação.
Os passos a seguir realizam a instalação do uav_rgbmul do projeto:

Criação do workspace:
``` sh
mkdir -p ~/workspace_projeto/src
cd ~/workspace_projeto/
catkin_make
source devel/setup.bash
catkin init
catkin clean
```

Instalação de dependências
``` sh
cd ~/workspace_projeto/src



catkin build
cd uav_rgbmul
pip3 install -r requirements.txt
```

## Execução


## Vídeo da execução

O vídeo da execução do projeto [link]().
