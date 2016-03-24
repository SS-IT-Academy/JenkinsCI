# Only listen on http; disable ajp and https
web: java -jar jenkins.war --httpPort=$PORT --ajp13Port=-1 --httpsPort=-1 --argumentsRealm.passwd.user=$ADMIN_USER --argumentsRealm.roles.user=admin