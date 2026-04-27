Ubuntu

LVM Snapsots Создание снапшота (Точка восстановления) 


openssl req -x509 -out igwik.ru.crt -keyout igwik.ru.key \
  -newkey rsa:2048 -nodes -sha256 \
  -subj '/CN=igwik.ru' -extensions EXT -config <( \
   printf "[dn]\nCN=igwik.ru\n[req]\ndistinguished_name = dn\n[EXT]\nsubjectAltName=DNS:igwik.ru\nkeyUsage=digitalSignature\nextendedKeyUsage=serverAuth")
