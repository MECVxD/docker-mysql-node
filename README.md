## Docker+MySql+node
1. Debe tener instalado docker.
2. Correr el contenedor de docker mediante el siguiente comando:

    `sudo docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=<password> -p 3306:3306 -d mysql:5.6`

3. Sustituir `<password>` por una contraseña propia.
4. Copiar el codigo del archivo **_"index.js"_**, con node instalar **_"mysql"_** y **_"dotenv"_**.
5. Crear un archivo **_".env"_** con los datos del **_".env.example"_** y sustituir por los valores porpios.
