# Documentación 

## Pasos realizados

1. Al principio tuvimos muchos inconvenientes, así que decidimos crear una nueva rama `dev` para trabajar allí sin afectar `main`.
2. Observamos que los cambios no se aplicaban porque el enlace al `style.css` estaba mal en el documento HTML.
3. Cambiamos el nombre del archivo HTML y realizamos ajustes en `styles.css`.
4. Agregamos los cambios (`git add .`) y creamos commits (`git commit -m ""`), nos movimos a través de las carpetas ( `git ckeckout` )y luego al fusionar (`git merge`).
5. Al hacer `merge` con `main` surgió un conflicto por el nombre anterior y el nuevo del archivo; lo resolvimos quedándonos con `index.html`.
6. Finalmente confirmamos que los cambios se reflejaban correctamente en GitHub.

## Reflexión sobre el proceso
# ¿Cómo fue la colaboración utilizando control de versiones en el desarrollo web?
  Al principio fue difícil, ya que no teníamos mucha experiencia usando Git y trabajando en equipo.
  Nos costó coordinarnos y manejar los comandos correctamente. Sin embargo, a medida que avanzamos, aprendimos a crear ramas,
  hacer commits y fusionar cambios.
# ¿Qué desafíos encontrasteis al trabajar en diferentes partes de la página?
  Tuvimos conflictos al modificar archivos compartidos y problemas con los enlaces al CSS, lo que nos enseñó a revisar antes de
  fusionar cambios.
# ¿Qué aprendieron sobre la importancia de la separación entre HTML y CSS?
  Mantener separado HTML y CSS facilita trabajar de manera organizada y entender mejor los cambios, sin embargo, es vital estar revisando los cambios y comunicarse. 


