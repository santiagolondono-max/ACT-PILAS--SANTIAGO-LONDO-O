# 📝 Simulador Undo/Redo — Pilas (Stack)

## 🎯 Objetivo del proyecto

Implementar en Java una aplicación que simula el funcionamiento de **deshacer (Undo)** y **rehacer (Redo)** de un editor de texto, usando la estructura de datos **Pila (Stack)** implementada manualmente.

---

## 🧠 ¿Cómo funciona una Pila?

Una pila funciona como una torre de platos: solo puedes agregar o quitar por arriba.  
Esto se llama **LIFO** — Last In, First Out (último en entrar, primero en salir).

El proyecto usa **dos pilas**:
- **pilaAcciones** → guarda el texto escrito por el usuario
- **pilaDeshechas** → guarda lo que se deshizo, para poder rehacerlo

---

## 📁 Estructura del proyecto

```
Actividad_Pilas/
├── src/
│   ├── Main.java     ← menú principal y lógica Undo/Redo
│   └── Stack.java    ← estructura de pila implementada manualmente
└── README.md
```

---

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Java
- **IDE:** IntelliJ IDEA
- **JDK:** 17 o superior

---

## ▶️ Instrucciones de ejecución

### Requisitos
Tener instalado Java JDK 17 o superior: https://www.oracle.com/java/technologies/downloads/

### Desde IntelliJ IDEA
1. Clona o descarga el repositorio.
2. Abre IntelliJ → **File → Open** → selecciona la carpeta del proyecto.
3. Abre `src/Main.java`.
4. Clic en el triángulo ▶️ al lado de `public static void main` o presiona `Shift + F10`.

### Desde la terminal
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/nombre-del-repo.git

# Entrar a la carpeta
cd Actividad_Pilas

# Compilar
javac src/Main.java src/Stack.java -d out

# Ejecutar
java -cp out Main
```

---

## 💻 Ejemplo de ejecución

```
Seleccione una opción:
1. Escribir texto
2. Deshacer (Undo)
3. Rehacer (Redo)
4. Mostrar texto actual
5. Salir
1
Ingrese el texto: Hola mundo
Texto agregado: "Hola mundo"

Seleccione una opción:
1. Escribir texto
...
2
Deshecho: "Hola mundo"

Seleccione una opción:
...
3
Rehecho: "Hola mundo"
```

---

## 📸 Capturas de pantalla

> Agrega aquí las capturas después de ejecutar el programa.  
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/138dad67-a163-4576-b4f1-bf9e8211834e" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ee6bce69-5bf2-4bd4-a5f0-f0c0f83fc701" />

---

## 📚 Operaciones de la Pila implementadas

| Operación | Descripción |
|-----------|-------------|
| `push()`  | Agrega un elemento arriba de la pila |
| `pop()`   | Saca y retorna el elemento de arriba |
| `peek()`  | Mira el elemento de arriba sin sacarlo |
| `isEmpty()` | Dice si la pila está vacía |

---

## 👥 Contribuyentes

| Nombre | Rol |
|--------|-----|
| LONDOÑO RUA SANTIAGO | Desarrollador |

