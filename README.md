# xtream-m3u
IPTV (Internet Protocol Television) es un servicio que transmite canales de televisión en vivo y contenido bajo demanda a través de internet de banda ancha, en lugar de métodos tradicionales como satélite o cable. Utiliza un protocolo IP para enviar la señal, permitiendo visualizarla en Smart TVs, TV Boxes, celulares o computadoras.
#
# ¿Que es Xtream?
Xtream (o Xtream Codes) es una plataforma y protocolo utilizado para gestionar y transmitir servicios de IPTV, permitiendo ver canales en vivo, películas y series (VOD) mediante internet. Utiliza credenciales específicas (API: URL, usuario y contraseña) para conectar reproductores multimedia con servidores de contenido
#
# ¿Sirve de algo IPTV?
El IPTV sirve para visualizar contenido en vivo o VOD, comunmente es usado en canales en vivo.
Unos son ilegales (Uso de canales de contenido restringido, premium o de paga), otros legales (Uso de canales de TV Abierta, gratuitos y no de paga)
y algunos por servicio (MegaGo, TVN Play o como CNTV).
#
# ¿Que se hará en este repositorio?
Aca, serviremos una Lista M3U con contenido de TV Chileno, con autenticacion. Si uno de ustedes recibe la contraseña, NO LA COMPARTAN.
Si la Contraseña es difundida en RR.SS. o en algun lado de internet, este repositorio dejara de existir.
Si usted es testigo de uno de estos casos, avisar con anticipacion.
#
# Listas M3U
Las listas M3U son listas de reproduccion multimedia, donde se organizan por el orden donde vayas escribiendo. P. Ej:

.#EXTM3U
.#EXTINF:-1 tvg-logo="logo1.png" tvg-id="pepitoserver.net" group-title="24/7",El canal de Pepito el mas capito
.http://pepitoserver.net/playlist.m3u8

.#EXTINF:-1 tvg-logo="logo2.png" tvg-id="pepitoserver.net" group-title="24/7",El canal de Pepito el mas capito 2
.http://pepitoserver.net/playlist.m3u8?channel=2

.#EXTINF:-1 tvg-logo="movie1.png" tvg-id="pepitoserver.net" group-title="Cortometrajes",Historia de Pepito
.http://pepitoserver.net/movie/h-i-s-t-o-r-i-a-_-d-e-_-p-e-p-i-t-o.mkv


Y al cargarla en un reproductor media como VLC, se ve primero el canal El canal de Pepito el mas capito.
#
# Canales de prueba
En Playlist, casi siempre existen canales de prueba con formato HLS o con formato de video (.mp4, .mkv o como .avi), algunas son:

Akamai: https://stream-akamai.castr.com/5b9352dbda7b8c769937e459/live_2361c920455111ea85db6911fe397b9e/index.fmp4.m3u8

Fastly: https://stream-fastly.castr.com/5b9352dbda7b8c769937e459/live_2361c920455111ea85db6911fe397b9e/index.fmp4.m3u8

VOD Url: https://bitdash-a.akamaihd.net/content/sintel/hls/playlist.m3u8

Big Buck Bunny: https://live-hls-abr-cdn.livepush.io/live/bigbuckbunnyclip/index.m3u8


# ¿Que es Mejor? ¿TV por Cable, Antena o Streaming?
En estas desiciones, se tiene que tomar el que usted quiera por caracteristicas como velocidad, calidad u otros.

Si quieres calidad: Usa Antena por TV Digital o Streaming

Si quieres velocidad: Usa Cable

Si quieres TV premium: Usa Cable o Streaming


A veces, es mejor tomar el streaming por calidad y contenido restringido, siempre como va tu internet o uso de datos.

# ¿Donde hay listas M3U de Chile?
Puedes encontrar listas M3U en internet usando palabras clave como:

IPTV, M3U Chile, IPTV Chile, TV Gratis, TV por internet, M3U, IPTV Premi...


Y otra opcion es usar un servicio por streaming como Zapping, VTR, Movistar, etc. O usar opciones de servicio IPTV Ilegal que filtra canales premium como:

TNT Sports 1, TNT Sports 2, TNT Sports 3, Canales ESPN, CDO, etc.

Listas M3U Legales que puedes usar:

M3U.cl => https://m3u.cl/lista/CL.m3u

iptv-org => https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/cl.m3u

json-teles => https://github.com/Alplox/json-teles/raw/refs/heads/main/canales.m3u


Esos son todos los que me se.

# Plataformas para servir streams
Una de las plataformas para servir stream de las que mas conozco, es MDSTRM. Hay otras como Digitalproserver, grupoz.cl, Twitch, Youtube, etc.
Siempre usa la mas confiable y segure.

#Outro
En fin, ya sabes que haremos en el repositorio, que es un iptv, que es una lista m3u, etc.
Entra a "novedades.html" desde la pagina ("index.html").

# Bye Bye :)
