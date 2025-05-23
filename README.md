# parchate
proyecto/parchate
# Parchate 🎉

**Parchate** es un proyecto web desarrollado con Laravel. Su propósito es [aquí puedes poner una breve descripción del objetivo del proyecto].

---

## 🚀 Requisitos

Asegúrate de tener instalados los siguientes componentes:

- PHP ^8.1
- Composer
- Laravel ^10
- MySQL o MariaDB
- Node.js & NPM (para assets)

---

## 🔧 Instalación

Sigue estos pasos para instalar el proyecto:

```bash
# Clonar el repositorio
git clone https://github.com/juancol2326/parchate.git

# Entrar al directorio
cd parchate

# Instalar dependencias de PHP
composer install

# Copiar archivo de entorno y configurar
cp .env.example .env

# Generar la clave de la app
php artisan key:generate

# Configurar tu base de datos en .env y luego ejecutar
php artisan migrate

# Instalar dependencias frontend
npm install && npm run dev


#comandos utiles para usar
# Servidor local
php artisan serve

# Compilar assets
npm run dev   # Para desarrollo
npm run build # Para producción



####
#usar github

---

### 2. **Subir a GitHub**

#### Paso a paso (si ya tienes el proyecto local):

```bash
# Inicializar repositorio Git si aún no lo has hecho
git init

# Agregar archivos
git add .

# Crear primer commit
git commit -m "Primer commit del proyecto parchate"

# Conectar con repositorio de GitHub
git remote add origin https://github.com/juancol2326/parchate.git

# Subir los archivos
git push -u origin master  # o 'main' si tu rama principal se llama así
