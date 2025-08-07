# 🔥 Wipe - Plugin para servidores Rust (Oxide/uMod)

## 📦 Descripción

Wipe es un plugin para servidores de Rust que permite realizar un wipe completo del servidor (mapa, blueprints, progreso, etc.) mediante un simple comando en el chat.
Además, envía automáticamente una notificación a Discord mediante un webhook con un mensaje embed personalizado, y reinicia el servidor automáticamente tras el wipe

---

## ⚙️ Requisitos

- Servidor de Rust con **Oxide/uMod** instalado.
- Permiso de administrador para ejecutar el comando `/wipe full`.

---

## 🚀 Instalación

1. Colocá el archivo Wipe.cs en la carpeta oxide/plugins/.
2. Configurá el plugin editando el archivo oxide/config/Wipe.json para poner tu webhook, rutas y mensajes personalizados.
3. Reiniciá el servidor o ejecutá:oxide.reload Wipe

---

## 💻 Comando

/wipe

-Solo los usuarios con permiso wipe.admin pueden usarlo.
-Ejecuta la cuenta regresiva configurable con avisos en el chat.
-Borra archivos y carpetas esenciales para hacer un wipe completo (blueprints, mapa, progreso).
-Envía un embed a Discord notificando el wipe.
-Reinicia el servidor automáticamente tras 5 segundos.

## ⚙️ Permisos

Para otorgar permisos, usar en consola o chat

Dar permiso a un grupo:
oxide.grant group <grupo> wipe.admin

Dar permiso a un usuario:
oxide.grant user <steamid> wipe.admin

## 📞 Soporte

¿Tenés dudas, sugerencias o necesitás ayuda con el plugin?  
Unite a nuestro Discord y te damos una mano:

🔗 **Discord:** [https://discord.gg/UK2e4aXq87](https://discord.gg/UK2e4aXq87)
