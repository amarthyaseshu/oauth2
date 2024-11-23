# oauth2
Spring Boot Oauth Practice

To  create Oauth2 Google credentails

Go to GCP-> Search APIs & Services->Credentials->Create credentials->OAuthClient ID
Application type->Web app
Provide Authorized redirect url->add uri-> http://localhost:8080/login/oauth2/code/google & create

Copy client id & secret, paste in app.properties
