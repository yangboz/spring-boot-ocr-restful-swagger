laughing-bear
=============

Spring-boot+SwaggerUI+Tesseract-ocr.

Tesseract
=============

`
brew install tesseract
`

`
mkdir -p ./tessdata
`

`
cd ./tessdata
`

`
wget http://tesseract-ocr.googlecode.com/files/chi_sim.traineddata.gz
`

`
wget http://tesseract-ocr.googlecode.com/files/chi_tra.traineddata.gz
`

`
gunzip chi_sim.traineddata.gz chi_tra.traineddata.gz
`

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

https://github.com/tesseract-ocr/tesseract/wiki

