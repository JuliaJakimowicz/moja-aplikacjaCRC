# moja-aplikacjaCRC

## Jak uruchomić i zbudować obraz aplikacji lokalnie

### Wymagania wstępne

1. Docker: Zainstalowanie dockera ze strony(https://www.docker.com/products/docker-desktop).

2. Klonowanie repozytorium

   **Klonowanie repozytorium**
   ```sh
   git clone https://github.com/twoje-konto/moja-aplikacjaCRC.git
   cd moja-aplikacjaCRC

3. Tworzenie pliku dockerfile
4. Budowanie obrazu Docker
 docker build -t moja-aplikacja
5. Wyświetlanie obrazów docker
docker images
6. tagowanie obrazu docker
 docker tag projektzaliczeniowycrc-hello-world projektzaliczeniowycrc.azurecr.io/projektzaliczeniowycrc:hello-world
7. wypychanie obrazu do docker hub
docker login
docker push projektzaliczeniowycrc.azurecr.io/projektzaliczeniowycrc:hello-world
8. uruchamoanie
docker run -d --name my_hello_world projektzaliczeniowycrc.azurecr.io/projektzaliczeniowycrc:hello-world


  
