# 📚 Programación Orientada a Objetos (POO)

Bienvenido al repositorio oficial del material de clase dictado por el profesor David Alberto Herrera Alvarez en la Universidad Nacional de Colombia. Este espacio contiene todos los notebooks interactivos y recursos utilizados durante el curso.

---

## 🔗 Repositorio principal

- URL: [https://github.com/dherreraal/object_oriented_programming](https://github.com/dherreraal/object_oriented_programming)
- Rama principal: `main`

---

## 🧭 Contenido

- 📓 **Notebooks en Google Colab** para prácticas y ejemplos interactivos en Java.
- 📂 **Material de apoyo** para teoría y ejercicios.
- 📝 **¿Qué es la Programación Orientada a Objetos?**
  De manera muy superficial, la Programación Orientada a Objetos (POO) es un paradigma o "estilo" de programación que organiza el código imitando el mundo real. En lugar de pensar en listas interminables de instrucciones matemáticas, se piensa en "Objetos" que tienen características (datos) y comportamientos (acciones) que interactúan entre sí. Este enfoque es el estándar en la industria moderna de desarrollo de software para crear programas organizados, robustos y fáciles de mantener.

---

## 🍴 Cómo hacer **fork**

1. Ingresa al repositorio principal:  
   👉 [https://github.com/dherreraal/object_oriented_programming](https://github.com/dherreraal/object_oriented_programming)  
2. Haz clic en **Fork** (arriba a la derecha).  
3. Selecciona tu cuenta de GitHub y confirma.  
4. (Opcional) Clona tu fork a tu PC:  
   ```bash
   git clone https://github.com/TU_USUARIO/object_oriented_programming.git
   cd object_oriented_programming
   ```

---

## 🔁 Cómo **actualizar tu fork**

### Desde la web (lo más fácil)

1. Ve a tu fork: `https://github.com/TU_USUARIO/object_oriented_programming`.
2. Haz clic en **Sync fork** o **Fetch upstream**.
3. Pulsa **Update branch / Sync fork**.

### Con Git en tu PC (línea de comandos)

Configura el remoto `upstream` (solo la primera vez):
```bash
git remote add upstream https://github.com/dherreraal/object_oriented_programming.git
git fetch upstream
```

Actualizar tu rama principal:
```bash
git checkout main
git merge upstream/main
git push origin main
```

---

## 🚀 Cómo **abrir los notebooks en Google Colab**

A lo largo del curso utilizaremos **Java**. Hemos adaptado Google Colab (una plataforma gratuita en la nube, originalmente diseñada para Python) para que actúe como nuestra pizarra interactiva de programación sin necesidad de instalar nada en su equipo inicial.

Existen distintas formas en las que puede abrir, visualizar y ejecutar estos archivos (`.ipynb`):

### Método 1: Abrir directamente desde Google Colab (Interfaz)
Esta es la forma más directa de conectar su Google Drive con el repositorio:
1. Ingrese a 👉 [Google Colab](https://colab.research.google.com/).
2. En la ventana emergente de bienvenida, seleccione la pestaña **GitHub**. (O Menú **Archivo → Abrir cuaderno**).
3. Pegue el enlace de este repositorio (o escriba `dherreraal/object_oriented_programming`).
4. Seleccione el notebook de la lista que desea abrir y haga clic sobre él.

### Método 2: El Botón "Open in Colab"
Si al explorar los archivos de este repositorio en GitHub ve un botón azul en la parte superior del notebook que dice **"Open in Colab"**, simplemente haga clic en él. Esto lo redirigirá inmediatamente a la plataforma.

### Método 3: Enlace directo
Usa esta URL como plantilla:  

```
https://colab.research.google.com/github/dherreraal/object_oriented_programming/blob/main/RUTA/AL/NOTEBOOK.ipynb
```

### Método 4: Modo Manual (Descargar y Subir)
Si prefiere tener el control total o guardarlo localmente:
1. En GitHub, abra el archivo del notebook que desea y haga clic en el botón de **Download raw file** (el ícono de flecha de descarga en la parte superior derecha) para guardarlo en su computadora.
2. Vaya a [Google Colab](https://colab.research.google.com/).
3. Vaya al menú superior: `Archivo > Subir notebook...` (File > Upload notebook).
4. Arrastre el archivo `.ipynb` que acaba de descargar.

---

## 💾 Cómo **guardar tus cambios desde Colab a tu fork**

1. Abre el notebook desde tu fork.  
2. En Colab: **Archivo → Guardar una copia en GitHub…**  
3. Selecciona tu repositorio (tu fork) y la rama.  
4. Escribe un mensaje de commit y confirma.  

---

## 🌟 Cómo proponer cambios al repositorio principal (Pull Request)

1. Asegúrate de que tu fork esté **actualizado** (ver arriba).
2. Crea una nueva rama y guarda tus cambios:
   ```bash
   git checkout -b mi-cambio
   git push -u origin mi-cambio
   ```
3. En tu fork en GitHub, pulsa **Compare & pull request**.
4. Envía el PR hacia `dherreraal/object_oriented_programming`.

---

## ❓ FAQ (Solución de Problemas Comunes)

### Error: "Unable to render code block" o "Sorry, something went wrong"
Es sumamente común que, al intentar **simplemente leer o previsualizar** un notebook directamente aquí en la página web de GitHub, aparezca un error diciendo que el archivo no pudo ser renderizado.

**¿Por qué pasa esto?** 
GitHub tiene un límite de tiempo de aproximadamente 5 segundos para procesar visualmente el archivo. Si el servidor de GitHub tiene tráfico alto, aborta la carga. Además, si usted usa extensiones en su navegador web (como bloqueadores de anuncios, traductores automáticos o plugins de *Modo Oscuro*), estos interfieren con GitHub y rompen la visualización. **Importante: El archivo no está dañado ni el código está roto.**

**¿Cómo leer el archivo cuando GitHub falla?**
Si se encuentra con este error, la solución es ignorar el visor de GitHub y **abrir el archivo directamente en Google Colab**.

Para ello, utilice cualquiera de las alternativas explicadas en la sección anterior:
*   **Método 1:** Ingrese a Colab, vaya a la pestaña GitHub y busque este repositorio.
*   **Método 4:** Descargue el archivo (botón *Download raw file*), vaya a Colab y súbalo manualmente.

Una vez abierto en Google Colab, todo el contenido se cargará y visualizará perfectamente sin importar qué extensiones tenga en su navegador.


- **¿Por qué no me aparece “Sync fork”?**  
  A veces está en la pestaña **Pull requests** de tu fork.  
- **Colab no me deja guardar en GitHub**  
  Asegúrate de estar logueado y de dar permisos a Colab.  
- **No encuentro el notebook en Colab**  
  Escribe `dherreraal/object_oriented_programming` en la pestaña GitHub de Colab o usa el enlace directo.  

---

## 📄 Licencia

Este repositorio se comparte con fines académicos y de aprendizaje.  
