# Only listen on http; disable ajp and https
# https://gist.github.com/jordansissel/2313443
web: java -jar jenkins.war --httpPort=$PORT --ajp13Port=-1 --httpsPort=-1