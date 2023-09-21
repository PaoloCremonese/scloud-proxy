# scloud-proxy

Scloud with proxy structure for Dockered deploy

# Configurazione
1. va aggiunta la chiave privata teledata.website.key in WildflyContainerSrc_thirdtry
2. Nel FileSystem della macchina ospite si deve creare una cartella
        /home/teledata/scloud-proxy/TeleCLOUD/scloud/nginx/certificati
   dove vanno copiati i certificati letsencrypt:
        fullchain.pem
        privkey.pem
