https://byjose007.github.io/

# Documentación del proyecto

Se puede encontrar todos los documentos relativos a la documentación del proyecto en la carpeta ``CNPPartner-Service-API/docs``. 

Para la edición de los ficheros Markdown de documentación del proyecto se recomiendan los programas:

* Typora

# CNPFront

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0-rc.1.

## Guía de installación y ejecución

Para levantar el proyecto, es necesario descargar e instalar las siguientes herramientas:

- NODE JS 10.X (Incluye NPM) 

  Windows: https://nodejs.org/es/download/
  
  Linux:    
  ```
  curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
  ```
  ```
  sudo apt-get install -y nodejs
  ```


- GIT 		
  Windows: https://git-scm.com/downloads
  
  Linux:  
  ``` 
  apt-get install git
  ```

- CLI
  
  windows && Linux:
  ```
  npm install -g @angular/cli
  ```
### Ejecución 

Desde la terminal: 

  windows && Linux: 
  ```
  git clone https://gitlab.com/cnppartners/morningstar.git
  ```  
  ```
  cd <path project>/frontend
  ``` 
  ```
  npm install
  ``` 
  Copiar el fichero index.html que se encuentra en el directorio `resources-to-filter` al directorio  `src`
  
  ```
  cp /CNPPartner-Service-API/frontend/src/resources-to-filter/index.html /CNPPartner-Service-API/frontend/src/index.html'
  ```
  Levantar proyecto
  ```
  npm serve
  ```
