# WalmartVC

Aplicación web desarrollada en **ASP.NET Core MVC** para la gestión de información de eventos y webinars administrados por el área de Videoconferencias.

Nace como un proyecto propio para digitalizar y organizar el seguimiento de las sesiones que superviso en mi rol actual como Ingeniero de Sistemas de Videoconferencia.

## Tecnologías

- ASP.NET Core MVC (C#)
- HTML / CSS
- Patrón MVC (Controllers, Models, Views)

## Funcionalidad

El usuario puedo registrar los webinars, todos los datos necesarios para generar sus reportes, al mismo tiempo, puede generar los reportes y unas vista previa de como deberia mandarse el correo al usuario.

## Estructura del proyecto

```
WalmartVC/
├── Controllers/   # Lógica de manejo de peticiones
├── Models/        # Entidades y estructuras de datos
├── Views/         # Vistas Razor (interfaz de usuario)
└── Program.cs     # Punto de entrada de la aplicación
```

## Cómo ejecutarlo

```bash
git clone https://github.com/ezarathustra/WalmartVC.git
cd WalmartVC
dotnet restore
dotnet run
```

## Próximos pasos

Se planea exportar los reportes y agregar un dashboar.

---
Proyecto personal de aprendizaje y práctica profesional — no representa software oficial de Walmart.
