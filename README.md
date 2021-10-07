# myexpress

Helloworld.js sisältää yksinkertaisesti helloworldin tulostavan ohjelman

Basic Routung.js sisältää eri vaihtoehtoja esim http://127.0.0.1:8081/ tulostaa hello get  sekä muut get komennot. Postmanilla pystyin testaan delete ja post komennot

Serving static files tulostaa kuvan osoitteesta http://127.0.0.1:8081/images/sample.jpeg

getMetohod kysyy käyttäjän nimen ja tulostaa sen.

postMethod kysyy käyttäjän nimen ja tulostaa sen 

FileUpload ei tominu joten muutin app.use(multer({ dest: '/tmp/'}) 
rivin ---> app.use(multer({ dest: '/tmp/'}).single('file'));

CoociesMAnangment tulostaa terminaaliin cookies: object null prototype