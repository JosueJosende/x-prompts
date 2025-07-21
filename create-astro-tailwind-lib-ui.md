# Crea una biblioteca de componentes UI moderna utilizando Astro y Tailwind CSS con las siguientes especificaciones técnicas:
  
## Estructura del Proyecto  
Framework: Astro (last version)  
Estilos: Tailwind CSS (last version)  
Funcionalidad: Soporte completo para temas modo claro y oscuro  
  
## Configuraciones  
Para la configuración de Tailwind en Astro indexa la siguiente url con la documentación necesaria para una buena configuración: https://tailwindcss.com/docs/installation/framework-guides/astro  
  
## Terminal  
Utiliza pnpm en lugar de npm  
  
## Layout Principal  
Sidebar izquierdo: Menú de navegación para seleccionar componentes  
Área principal:  
Visualización del componente seleccionado  
Bloque de código debajo con funcionalidad de copia  
  
## Funcionalidades Requeridas ### Sistema de Temas  
Implementar toggle para alternar entre modo claro y oscuro  
Todos los componentes deben adaptarse automáticamente al tema seleccionado  
Usar las clases de Tailwind dark: para el modo oscuro  
  
## Funcionalidad de Copia de Código  
Botón de copia en la esquina superior derecha del bloque de código  
Al hacer clic: mostrar tooltip "¡Copiado!" durante exactamente 2 segundos  
Después del timeout, volver a mostrar el ícono de copia  
Implementar la funcionalidad real de copia al portapapeles  
  
Componente Inicial: Popover  
Desarrolla un componente popover que incluya:  
  
Trigger button personalizable  
Contenido del popover posicionable  
Animaciones suaves de entrada/salida  
Cierre al hacer clic fuera del popover  
Responsive design  
Compatibilidad con ambos temas (claro/oscuro)  
  
Requisitos Técnicos  
Código limpio y bien estructurado  
Componentes reutilizables 
Accesibilidad básica (ARIA labels, navegación por teclado)  
Responsive design para móviles y desktop 
Comentarios en español en el código para facilitar la comprensión  
Proporciona el código completo funcional con todos los archivos necesarios para el proyecto Astro.  
