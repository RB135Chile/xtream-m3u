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
#Canales de prueba
En Playlist, casi siempre existen canales de prueba con formato HLS o con formato de video (.mp4, .mkv o como .avi), algunas son:

Akamai: https://stream-akamai.castr.com/5b9352dbda7b8c769937e459/live_2361c920455111ea85db6911fe397b9e/index.fmp4.m3u8
Fastly: https://stream-fastly.castr.com/5b9352dbda7b8c769937e459/live_2361c920455111ea85db6911fe397b9e/index.fmp4.m3u8
VOD Url: https://bitdash-a.akamaihd.net/content/sintel/hls/playlist.m3u8
Big Buck Bunny: https://live-hls-abr-cdn.livepush.io/live/bigbuckbunnyclip/index.m3u8

