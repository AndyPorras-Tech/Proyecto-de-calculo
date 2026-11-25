# Las matemáticas detrás de la ciberseguridad y las telecomunicaciones
Sitio estático educativo. Abrir index.html directamente o publicar los tres archivos en GitHub Pages. No necesita dependencias ni conexión para el simulador.

## Exposición (20 minutos)
- 0–3 min: problema de disponibilidad, tráfico y DDoS; distinguir picos legítimos.
- 3–6 min: modelo R(t)=b+at², unidades y escenarios.
- 6–10 min: derivada, tangente, interpretar a=50, b=100, t=5 (500 solicitudes/s²).
- 10–14 min: integral, área acumulada (2583.33 solicitudes), volumen aproximado.
- 14–17 min: comparar escenarios y cambiar umbral; explicar que no confirma ataques.
- 17–19 min: muestras discretas, diferencia finita y trapecios.
- 19–20 min: conclusión y pregunta al grupo.

## Publicación
Crear repositorio público vacío llamado calculo-redes en GitHub. Desde esta carpeta:
```
git init
git add .
git commit -m "Proyecto de cálculo aplicado a redes"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/calculo-redes.git
git push -u origin main
```
En GitHub: Settings > Pages > Deploy from a branch > main > / (root) > Save. Esperar el despliegue y abrir la URL que aparece en Pages.

Modelo hipotético, no monitor de red real. Referencias de lectura incluidas en la página.
