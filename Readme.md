<p align="center">
	<img src="logo-team-21.png" width="40%"/>
</p>

# GUIAS DE USO EN NPM

## GLOBAL

<!-- Acciones -->

### Acciones

**Actualizacion de Npm**

- npm install -g _[paquete]@[version]_

**Configuracion Global de Npm**

- npm set init.author.name _@Nombre de usuario_
- npm set init.author.email _Email de usuario_
- npm set init.author.url _Url de Usuario_
- npm set init.license _Licencia_

**Cuenta de Npmjs.com**

- npm adduser _usuario y password_

**Flags**

**_Alias_**

- -i, add, install _Instalacion_
- -g, --global _Instalacion global_

**_Instalacion_**

- npm install [dir] _Instalacion desde directorio local o archivo comprimido_
- npm install [url] _Instalacion desde un repositorio remoto_
- npm install [paquete]@[version] _Instala paquete con su propia version (latest por defecto)_
- npm install [@]ev>[paquete]@[version] _Instala desde el registro del desarrollador del paquete_
- @latest _Ultima actualizacion del paquete_

**_Adicionales_** _(modificadores para package.json)_

- -S, --save _opcion por defecto, registrado en dependecies_
- -E, --save-exact _registra la version exacta_
- -E, --save-bundle _registra la version exacta_
- -D, --save-dev _en desarrollo, registrado en devDependecies_
- -P, --save-prod _produccion, registrado en dependecies_
- -O, --save-optional _opcional, registrado en optionalDependecies_
- --no-save _no guarda registro alguno_

**Configuracion Global de Git**

- git config --global user.name _@Nombre de usuario_
- git config --global user.email _Email de usuario_
- git config --global core.editor _Editor de git_
- git config --list _Visualizamos la configuracion de git_

<!-- Acciones -->

<!-- Command -->

### Command

```
npm install -g npm@latest
npm set init.author.name "@T3am."
npm set init.author.email "EngineLandTeam@gmail.com"
npm set init.author.url "https://EngineLand.dev"
npm set init.license "MIT"
npm adduser

git config --global user.name "@T3am."
git config --global user.email "EngineLandTeam@gmail.com"
git config --global core.editor "C:\\Program Files\\Microsoft VS Code\\Code.exe" --wait
```

<!-- Command -->

---

## INICIO DE REPOSITORIO

<!-- Acciones -->

### Acciones

- Creamos una nueva carpeta
- Inicializamos Git
- Inicializamos Npm
- Configuramos Package.json
- Creamos y adaptamos .gitignore

<!-- Acciones -->

<!-- Command -->

### Command

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

### Acciones

- Instalamos Bootstrap en modo de desarrollo
- Instalamos @Fontawesome free en modo de desarrollo
- Instalamos Webpack en modo de desarrollo
- Instalamos Webpack CLI en modo desarrollo

<!-- Acciones -->

<!-- Command -->

### Command

```
npm i -D bootstrap@latest
_npm i github:EngineLanTeam/Npm_
npm i -D @fortawesome/fontawesome-free
npm i -D webpack
npm i -D webpack-cli

git add .
git commit -m "Instalacion de Dependencias"
```

<!-- Command -->

---

## PUBLICACIOM EN NPM

<!-- Acciones -->

### Acciones

- Publicacion global de nuestro paquete en local
- Vinculamos a cuentas de Npmjs y Github
- Publicamos nuestro paquete en Npmjs
- Patch version en npmjs
- Actualizamos version de npm
- Actualizamos version de git
- Remote en github

<!-- Acciones -->

<!-- Command -->

### Command

```
npm link
_npm install -g C:\laragon\www\Npm_
npm adduser
npm version patch
git tag -a v1.0.0 -m "Version Inicial"
npm publish
npm install -g
git remote add origin https://github/EngineLandTeam/Npm.git

git add .
git commit -m "Publicacion en Npm"
git push origin master
git push origin --tags
```

<!-- Command -->

## README GLOBAL

<!-- Acciones -->

### Acciones

- Incluimos en Readme instrucciones mas usadas
- Actualizamos version de npm
- Actualizamos version de git
- Remote

<!-- Acciones -->

<!-- Command -->

### Command

```
npm link
npm version patch
npm publish
_git tag -a v1.0.2 -m "Readme Global"_

git add .
git commit -m "Readme Global"
git push origin master
git push origin --tags
```

<!-- Command -->

---

![Logo](logo-elt-15.png)
