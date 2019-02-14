# StravaPrediction


mvn install:install-file -Dfile=target/swagger-java-client-1.0.0.jar -DgroupId=io.swagger -DartifactId=swagger-java-client -Dversion=1.0.0 -Dpackaging=jar -DgeneratePom=true

mvn install:install-file -Dfile=target/strava-prediction-0.0.2-SNAPSHOT.jar -DgroupId=nikth.services -DartifactId=strava-prediction -Dversion=0.0.2 -Dpackaging=jar -DgeneratePom=true


lib/okhttp-2.7.5.jar was added for eclipse only. Maven handles all dependencies.
