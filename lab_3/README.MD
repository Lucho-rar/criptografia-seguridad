<p align="center">
  <img src="./img/portada.png"><br>
</p>

# Criptografía y seguridad 2024
# Firma Digital

## Configurar Thunderbird


Como primer paso se configura el cliente de thunderbird con nuestro correo.
<p align="center">
  <img src="./img/config_thunder.png"><br>
  <em>Fig. Configuracion inicial de thunderbird</em>
</p>

## Generar par de claves

Para generar las claves desde el key Manager generamos con el correo asociado.
<p align="center">
  <img src="./img/key_create.png"><br>
  <em>Fig. openPGP key manager</em>
</p>

## Exportar la clave para publicarla en servidores de referencia 

Utilizando servidores publicos de registro voluntario podremos intercambiar las claves públicas. Para esto se exporta el file y lo subimos a [Keys OpenPGP ORG](https://keys.openpgp.org/).

<p align="center">
  <img src="./img/keysopenpgp.png"><br>
  <em>Fig. Keys OpenPGP ORG</em>
</p>

## Configurar la cuenta para utilizar la clave generada

Para esto desde la configuracion del cliente

<p align="center">
  <img src="./img/endtoend.png"><br>
  <em>Fig. End to end</em>
</p>

## Enviar un mensaje firmado y encriptado

Para enviar correos necesitamos compartir las claves (entonces nos las enviamos a nosotros mismos). Al enviarlo seleccionamos la opcion Encrypted de OpenPGP

<p align="center">
  <img src="./img/pre-send.png"><br>
  <em>Fig. Envio</em>
</p>

<p align="center">
  <img src="./img/secret.png"><br>
  <em>Fig. Mensaje encriptado</em>
</p>

Se observa que desde el cliente puedo observar el mensaje pero desde el navegador no se puede.


## Firma digital provista por terceros

Para esto usamos Actalis que nos provee certificados de correos electronicos gratis. Para esto realizamos la configuracion paso a paso hasta que nos dan la clave y el file del ceritificado.

<p align="center">
  <img src="./img/actalis.png"><br>
  <em>Fig. Actalis</em>
</p>

Luego se configura el cliente agregando el certificado.

<p align="center">
  <img src="./img/certificado.png"><br>
  <em>Fig. Agrega certificado</em>
</p>

<p align="center">
  <img src="./img/certificado2.png"><br>
  <em>Fig. Agrega certificado</em>
</p>
Luego ya podemos enviar un correo firmandolo 

