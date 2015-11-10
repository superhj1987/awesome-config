# add this line to support remote debug
port=8900
export CATALINA_OPTS="-Xdebug -Xrunjdwp:transport=dt_socket,address=$port,server=y,suspend=n"
