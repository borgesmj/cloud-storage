# Real time chat app  

Esto es uno de los tres proyectos propuestos a  realizar en Mayo-2024  
  

## Primera fase: Investigación y planificación  

### 1. Diseños de guía  

Buscando diseños UI en la web, encontré estos dos que me gustaron como guía.![](https://assets.materialup.com/uploads/ddee5e43-4aea-4c63-abf4-b08f7233d98c/preview.png)


![Fuente: https://assets.materialup.com/](https://assets.materialup.com/uploads/17232f9e-82f4-479b-a606-962876ce2751/preview.jpg)  
  

### 2. Selección de colores
#### Ligth Theme:
![#6AB7FF](https://placehold.co/15x15/6AB7FF/6AB7FF.png) `--primary-100: #6AB7FF`
![#479ae0](https://placehold.co/15x15/479ae0/479ae0.png) `--primary-200: #479ae0`
![#005b9a](https://placehold.co/15x15/005b9a/005b9a.png) `--primary-300: #005b9a`
![#FFD700](https://placehold.co/15x15/FFD700/FFD700.png) `--accent-100: #FFD700`
![#917800](https://placehold.co/15x15/917800/917800.png) `--accent-200: #917800`
![#333333](https://placehold.co/15x15/333333/333333.png) `--text-100: #333333`
![#5c5c5c](https://placehold.co/15x15/5c5c5c/5c5c5c.png) `--text-200: #5c5c5c`
![#FFFFFF](https://placehold.co/15x15/FFFFFF/FFFFFF.png) `--bg-100: #FFFFFF`
![#f5f5f5](https://placehold.co/15x15/f5f5f5/f5f5f5.png) `--bg-200: #f5f5f5`
![#cccccc](https://placehold.co/15x15/cccccc/cccccc.png) `--bg-300: #cccccc`


```CSS
    --primary-100:#6AB7FF;
    --primary-200:#479ae0;
    --primary-300:#005b9a;
    --accent-100:#FFD700;
    --accent-200:#917800;
    --text-100:#333333;
    --text-200:#5c5c5c;
    --bg-100:#FFFFFF;
    --bg-200:#f5f5f5;
    --bg-300:#cccccc;   
```

#### Dark theme:

![#64FFDA](https://placehold.co/15x15/64FFDA/64FFDA.png) `--primary-100: #64FFDA`
![#3ce0bc](https://placehold.co/15x15/3ce0bc/3ce0bc.png) `--primary-200: #3ce0bc`
![#00997a](https://placehold.co/15x15/00997a/00997a.png) `--primary-300: #00997a`
![#1E88E5](https://placehold.co/15x15/1E88E5/1E88E5.png) `--accent-100: #1E88E5`
![#dbffff](https://placehold.co/15x15/dbffff/dbffff.png) `--accent-200: #dbffff`
![#FFFFFF](https://placehold.co/15x15/FFFFFF/FFFFFF.png) `--text-100: #FFFFFF`
![#e0e0e0](https://placehold.co/15x15/e0e0e0/e0e0e0.png) `--text-200: #e0e0e0`
![#0A192F](https://placehold.co/15x15/0A192F/0A192F.png) `--bg-100: #0A192F`
![#1b283f](https://placehold.co/15x15/1b283f/1b283f.png) `--bg-200: #1b283f`
![#333f58](https://placehold.co/15x15/333f58/333f58.png) `--bg-300: #333f58`

```CSS
    --primary-100:#64FFDA;
    --primary-200:#3ce0bc;
    --primary-300:#00997a;
    --accent-100:#1E88E5;
    --accent-200:#dbffff;
    --text-100:#FFFFFF;
    --text-200:#e0e0e0;
    --bg-100:#0A192F;
    --bg-200:#1b283f;
    --bg-300:#333f58;   
```

### 3. Funciones que incluirá la primera versión del proyecto
1. Listado de chats
2. Login
3. Perfil de usuario
4. Emojis bar
5. Conectividad en tiempo real
6. Notificaciones push
7. Búsqueda de mensajes
8. Personalización de perfiles:

### 4. Stack a  utilizar:
#### FrontEnd: 
*  [![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
*  [![](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://es.vitejs.dev/)
*  [![](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/docs/)
*  [![](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](https://reactrouter.com/en/main)

#### Backend
* [![](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black)](https://console.firebase.google.com/)
## Segunda Fase: Diseño de la UI
Para el diseño de la UI utilice [Figma](https://www.figma.com/)

El diseño lo encuentra en el siguiente [link](https://www.figma.com/proto/DIx4uyuxmZ153npeyHleAC/real-time-chat-app?type=design&node-id=1-3&t=rjNXb5BIpje8IGmP-1&scaling=contain&page-id=0%3A1&starting-point-node-id=10%3A103&mode=design)


![alt text](<Preview-desktop.png>)


## Tercera fase: maquetación con react

### Creando el proyecto con Vite y React
1. Ejecutamos el comando `npm create vite@latest`
2. Configuramos nuestro proyecto a![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) y le damos un nombre.
3. Instalamos dependencias `npm install`
4. Y ejecutamos el proyecto `npm run dev`

![image](https://github.com/borgesmj/cloud-storage/assets/121818423/69c9f40c-fc1f-4c8a-a449-4a6c0eb7f04c)

