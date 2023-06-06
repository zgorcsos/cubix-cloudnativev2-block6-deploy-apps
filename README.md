# Cubix Cloud-Native Application Development Training: cloud-native requirements (app deployment)
Fork this repository for the practice session.

# How to start the api application
helm upgrade api spring-cubix --install -f api.yaml -n cubix

# How to start the db application
helm upgrade db spring-cubix --install -f db.yaml -n cubix --set env[2].value=<ENTER-PASSWORD>
