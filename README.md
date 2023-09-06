<p align="center"> 
<a href="https://instagram.com/benjaexe7">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>

PÁGINA DE BENJAEXE-BOT:
> Bienvenido a mi página, aquí
> encontraras todos los recursos
> necesarios para usar a BenjaExe-Bot
  
#### DISPONIBLE EN:
> - [x] TERMUX, REPLIT, WINDOWS, ZIPPONODES, BOXMINE-HOST


[`♻️ App Termux`](https://f-droid.org/es/packages/com.termux/)
###  INSTALACIÓN AUTOMÁTICA DE BENJAEXE-BOT - TERMUX 

```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBotLite-MD/master/gatalite.sh | bash
```

###  INSTALACIÓN MANUAL DE BENJAEXE-BOT - 

###  TERMUX 24/7  
> Comandos para realizar una ejecución 24/7
- INICIAR
> Use estos comandos dentro de la carpeta BenjaExe-Bot
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
```
- DETENER PM2
> Detener todos los procesos del bot
```bash
pm2 stop all && pm2 unstartup
```
- REANUDAR 
> Reanudar los procesos, usar dentro de la carpeta BenjaExe-Bot
```bash
pm2 start index.js 
```
- VISUALIZAR EL PROCESO
> Usar dentro de la carpeta BenjaExe-Bot para ver en tiempo real
```bash
pm2 logs 
```
- ELIMINAR PROCESOS PM2
> Eliminar todos los procesos del bot. Para volver a usar PM2 debe volver a usar los comandos de INICIAR
```bash
pm2 delete all
```
### 💠 [`IDIOMAS DISPONIBLES PARA GATABOTLITE`](https://github.com/GataNina-Li/GataBotLite-MD/blob/f406e0f1bba1ca7cd6ee4ef3208e156135a24dce/config.js#L31) 
#### ✨ Español  [`Editar Idioma`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/espanol.js)

### CREADOR
BENJAEXE-BOT
@benjaexe7
