laughing-bear
=============

Spring-boot+SwaggerUI+Tesseract-ocr.

Tesseract
=============

`
brew install tesseract --with-all-languages 
`

Mvn
=============

`
mvn spring-boot:run -Dspring.profiles.active=dev
`

MicroService
=============



Swagger UI
=============

http://localhost:8083/api/swagger-ui.html

Curl
=============

`
curl -i -X POST -H "Content-Type: multipart/form-data" -F "file=@raw_ocr.png" http://localhost:8083/api/info/smartkit/orc/tesseract
`

Reference
=============

https://code.google.com/p/tesseract-ocr/

http://tess4j.sourceforge.net/

https://github.com/tesseract-ocr/tesseract/wiki

http://www.baeldung.com/swagger-2-documentation-for-spring-rest-api

