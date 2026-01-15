# 💰 Alke Wallet

**Repositorio:** [https://github.com/claubett17/Alke-Wallet](https://github.com/claubett17/Alke-Wallet)

## 📖 Descripción del Proyecto
Alke Wallet es una aplicación web de billetera digital desarrollada como proyecto académico individual del módulo Front End ejecutada con **HTML5, CSS3 (Bootstrap) y JavaScript (jQuery)**.

**Funcionalidades principales:**
* 🔐 **Autenticación:** Inicio de sesión validado (Usuario: `admin@wallet.com` / Pass: `123456`).
* 💵 **Gestión de Saldo:** Visualización y actualización en tiempo real usando `localStorage`.
* 📥 **Depósitos:** Ingreso de fondos con validación de montos positivos.
* 💸 **Transferencias:** Envío de dinero a contactos y registro de nuevos destinatarios (Manipulación del DOM).
* 📊 **Historial:** Visualización dinámica de los últimos movimientos (Ingresos y Egresos).

---

## 🛠️ Guía de Referencia Git
Resumen de comandos basado en las clases "Fundamentos de Git y GitHub (Parte I y II)" y los ejercicios prácticos.

### 🔹 1. Configuración Inicial (Setup)
Comandos para preparar el entorno antes de empezar.

| Comando | Descripción |
| :--- | :--- |
| `git --version` | Verifica la instalación de Git. |
| `git config --global user.name "Tu Nombre"` | Configura tu nombre de usuario global. |
| `git config --global user.email "mail@x.com"` | Configura tu correo electrónico global. |
| `git config --list` | Muestra toda la configuración actual para verificar. |

### 🔹 2. Control Local (Ciclo de vida básico)
Comandos para guardar tu trabajo en el historial local.

| Comando | Descripción |
| :--- | :--- |
| `git init` | Inicializa un repositorio nuevo en la carpeta actual. |
| `git clone <url>` | Descarga un repositorio existente desde GitHub a tu PC. |
| `git status` | Muestra el estado de los archivos (Rojos: modificados / Verdes: listos). |
| `git diff` | Muestra las diferencias exactas de los cambios dentro de los archivos. |
| `git add <archivo>` | Agrega un archivo específico al área de preparación (Stage). |
| `git add .` | Agrega **todos** los archivos modificados al área de preparación. |
| `git commit -m "mensaje"` | Confirma los cambios preparados con un mensaje descriptivo. |
| `git log` | Muestra el historial de commits realizados. |

### 🔹 3. Ramas y Repositorios Remotos
Comandos para trabajar con GitHub y versiones paralelas.

| Comando | Descripción |
| :--- | :--- |
| `git remote add origin <url>` | Vincula tu carpeta local con el repositorio en GitHub. |
| `git branch` | Lista las ramas locales. |
| `git branch <nombre>` | Crea una nueva rama (ej. `features`). |
| `git checkout <nombre>` | Te cambia a la rama especificada. |
| `git checkout -b <nombre>` | Crea una rama y te cambia a ella automáticamente. |
| `git merge <rama>` | Fusiona la rama especificada con la rama actual. |
| `git push -u origin main` | Sube tus cambios a GitHub (configura el rastreo inicial). |
| `git push` | Sube los nuevos cambios (después de la primera configuración). |
| `git pull` | Descarga cambios del remoto y los fusiona con tu local. |
| `git fetch` | Descarga información del remoto sin fusionar los cambios. |

### 🔹 4. Herramientas Avanzadas (Ejercitación Clase)
Comandos solicitados en las prácticas de "Live Coding" y "Momento de ejercitación".

| Comando | Descripción |
| :--- | :--- |
| `git stash` | Guarda temporalmente cambios sin hacer commit (ideal para cambiar de rama rápido). |
| `git stash pop` | Recupera y aplica los cambios guardados con stash. |
| `git rebase -i` | (Interactivo) Permite reescribir, unir o limpiar el historial de commits. |
| `git tag <version>` | Etiqueta un punto específico de la historia (ej. `v1.0`). |
| `git push --tags` | Sube las etiquetas creadas al repositorio remoto. |

---

### 🚀 Instrucciones para probar este proyecto
1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/badi11a/alky-wallet.git](https://github.com/badi11a/alky-wallet.git)