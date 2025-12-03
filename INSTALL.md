# Guía de Instalación - Taller Molina

## Requisitos
- Windows 10 o superior
- Visual Studio 2019 o 2022
- .NET 7 SDK
- SQL Server o MySQL

## Instalación
1. Clonar el repositorio:  
   `git clone https://github.com/471-234/Taller_Molina_Manual_Tecnico.git`
2. Abrir la solución en Visual Studio (`TallerMolina.sln`) desde `src/TallerMolina/`.
3. Restaurar paquetes NuGet si los hubiera.
4. Configurar la cadena de conexión a la base de datos en `Data/DbContext.cs`.
5. Compilar y ejecutar la aplicación.

## Base de datos
- Ejecutar los scripts en `db/create_*` para crear la base de datos.
- Ejecutar los scripts en `db/seed_*` para poblarla con datos de ejemplo.
