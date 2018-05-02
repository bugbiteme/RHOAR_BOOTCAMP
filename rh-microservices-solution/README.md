Clone the source source code

git
clone 
https://github.com/gpe-mw-training/appmod_wildfly_swarm_experienced.git appmod_wildfly_swarm_experienced


3.
Move into directory

cd
appmod_wildfly_swarm_experienced


4.
Checkout the solution branch

git
checkout solution

cd
lab-01


5.
Run a prep command to seed local Maven repo. May take up to 10 minutes

mvn
clean package -DskipTests

Eventually,
you’ll see …
[INFO]
BUILD SUCCESS


6.
Run another prep command. May take up to 10 minutes

mvn
clean test

Eventually,
you’ll see …
[INFO]
BUILD SUCCESS