### Pipeliny wymagają do działania dwóch plików

1. keystora z kluczem do podpisywania [ ./keystore.jks ]
`keytool -genkeypair -storepass 123456 -keypass 123456 -file server.cer -keystore keystore.jks -keyalg RSA -validity 20000`

2. kluczy do publishowania w google play [ ./api-codes.json ]
