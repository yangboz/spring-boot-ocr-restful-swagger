laughing-bear
=============

Spring-boot+SwaggerUI+Tesseract-ocr.

Tesseract
=============

https://github.com/tesseract-ocr/tesseract/wiki

Mvn
=============
`
mvn spring-boot:run -Dspring.profiles.active=dev
`

Swagger UI
=============

http://localhost:8083/api/static/index.html

Curl
=============
`
curl -i -X POST -H "Content-Type: multipart/form-data" -F "file=@raw_ocr.png" http://localhost:8083/api/info/smartkit/orc/file/upload
`
Reference
=============

https://code.google.com/p/tesseract-ocr/

http://tess4j.sourceforge.net/

