<p align="center">
	<img src="logo-team-21.png" width="40%"/>
</p>

# GUIAS DE USO EN NPM

## VARIABLES GLOBALES

<!-- Acciones -->

#### Acciones

- Configuraciones Globales de Git
- Actualizacion de Npm
- Configuraciones Globales de Npm
- Vinculamos cuenta de Npm

<!-- Acciones -->

<!-- Command -->

#### Command

```
npm install -g npm@latest
npm set init.author.name "T3am."
npm set init.author.email "EngineLandTeam@gmail.com"
npm set init.author.url "https://EngineLand.dev"
npm set init.license "MIT"
npm adduser *user* - *pass*

git config --global user.name "T3am."
git config --global user.email "EngineLandTeam@gmail.com"
```

<!-- Command -->

---

## INICIO DE REPOSITORIO

<!-- Acciones -->

#### Acciones

- Creamos una nueva carpeta
- Inicializamos Git
- Inicializamos Npm
- Configuramos Package.json
- Creamos y adaptamos .gitignore

- Commit

<!-- Acciones -->

<!-- Command -->

#### Command

```
mkdir Npm && cd Npm
git init
npm init -y

git add .
git commit -m "Inicio de Repositorio"
```

<!-- Command -->

---

## INSTALACION DE DEPENDENCIAS

<!-- Acciones -->

#### Acciones

- Instalamos Bootstrap en modo de desarrollo con el flag -D
- Instalamos @Fontawesome free en modo de produccion
- Instalamos Webpack en modo de desarrollo con --save-dev o -D
- Instalamos Webpack interface de linea de comandos

<!-- Acciones -->

<!-- Command -->

#### Command

```
npm install -D bootstrap@latest
*npm install github:EngineLanTeam/Npm*
npm install -D @fortawesome/fontawesome-free
*npm install --save @fortawesome/fontawesome-free*
npm install -D webpack
npm install -D webpack-cli
*npm install webpack@latest --save-dev*

git add .
git commit -m "Instalacion de Dependencias"
```

<!-- Command -->

---

## PUBLICACIOM EN NPM

<!-- Acciones -->

#### Acciones

- Publicacion global de nuestro paquete en local
- Creamos cuentas en Npmjs y en Github
- Vinculamos las cuentas de Npmjs y en Github
- Publicamos nuestro paquete
- Patch version en npmjs
- Actualizamos version de npm
- Remote en github

<!-- Acciones -->

<!-- Command -->

#### Command

```
npm link
*npm install -g C:\laragon\www\Npm*
npm adduser *user* - *pass*
npm version patch
npm publish
npm install -g
git remote add origin https://github/EngineLandTeam/Npm.git

git add .
git commit -m "Publicacion en Npm"
```

<!-- Command -->

---

![Logo](logo-elt-15.png)
